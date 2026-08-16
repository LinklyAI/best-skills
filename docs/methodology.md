# Methodology

This document explains where the numbers come from, how rankings are computed, and what the known limitations are. The collection pipeline is open source at [LinklyAI/best-skills-runner](https://github.com/LinklyAI/best-skills-runner), and every ranking CSV preserves the raw per-platform numbers it was derived from, and all time-based scores reference the end of the data date (UTC) rather than the wall clock — so published scores can be reproduced from the CSVs alone.

## Data sources

| Source                                  | What we take                                                            | Notes on their methodology                                                                                                                                                                                      |
| --------------------------------------- | ----------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [skills.sh](https://www.skills.sh)      | Skill-level install counts, 8-week weekly install series, official flag | Counts deduplicated installs reported by the skills CLI's anonymous telemetry. Manual `git clone` installs are not counted. Installs are **bundle-level**: installing a repo counts once for every skill in it. |
| [ClawHub](https://clawhub.ai)           | Skill-level downloads/installs/stars/versions, official publisher feed  | Platform's own counters for the OpenClaw ecosystem. Used per ClawHub's third-party directory policy. Note: bare slugs are ambiguous on ClawHub itself (several publishers can share one slug).                  |
| [Tencent SkillHub](https://skillhub.cn) | Skill-level downloads/installs, verified-enterprise flag                | **Independent counters measuring China-region activity.** For skills synced from ClawHub, SkillHub numbers are _additional local activity_, not a mirror — which is why we never sum them with ClawHub numbers. |
| GitHub API                              | Repository stars, push recency, topics                                  | Stars are repository-level and are never attributed to individual skills.                                                                                                                                       |
| X, Hacker News, Bluesky, GitHub search  | Mention counts in a rolling 7-calendar-day window; X post links         | Platform search APIs; English-dominant coverage. Post texts never leave the pipeline — only links and per-post engagement metrics are published.                                                                |

## Core rules

1. **Numbers are never summed across platforms.** Each platform counts different things (different ecosystems, different regions, different dedup rules). Rankings that merge ecosystems are ordered by a _within-platform percentile composite_: every raw number is first log-transformed and converted to a percentile **inside its own platform**, then combined. The raw numbers stay in the CSV, side by side.
2. **Repository stars never rank individual skills.** A monorepo with 17 skills shares one star count; attributing it to each skill would be meaningless. Stars get their own repository ranking (`top-repos`).
3. **Joins are disclosed.** Every skill ranking carries a `match` column stating how cross-platform rows were joined: `upstream` = exact SkillHub→ClawHub `upstream_url` evidence, `upstream-unresolved` = an upstream was claimed but could not be resolved, `single` = one source only. `best-100` and `top-installs` additionally carry a coverage grade (A/B/C = number of registries with install data).
4. **Social counts are filtered where filtering works, and excluded where it can't.** HN and Bluesky candidates are relevance-checked by an LLM before counting; their published counts are estimates extrapolated from the checked sample (raw pre-filter totals are published alongside as `hn_raw_7d` / `bsky_raw_7d`). X and GitHub counts are keyword-constrained but **not** LLM-checked (X uses context-word queries, GitHub uses title-exact match plus the word "skill"). Skills whose name is an everyday word (no hyphen — github, weather, prototype…) are **excluded from the social-buzz ranking entirely** and their X/HN/Bluesky signals are ignored in scoring, because mentions of everyday words cannot be attributed to the skill. `llm_filtered=true` means the HN/Bluesky counts of that row passed the LLM check; `false` means there was nothing to filter (zero candidates) or the filter was unavailable. Judgement-based rankings (e.g. sentiment) are intentionally NOT published — only countable facts.
5. **Same-name skills are different skills.** Entities are keyed by fully-qualified ids (owner/repo/skill on skills.sh, platform-unique slugs elsewhere); cross-platform merging happens only on exact evidence (SkillHub → ClawHub `upstream_url`). Social mentions, searched by short name, are attributed to the most popular same-name entry and flagged `buzz_shared` when names collide.
6. **Missing dimensions never inflate a score.** Unmeasured WIS dimensions are filled with a neutral prior (0.3) instead of being dropped from the weighted mean. The same rule applies **inside** the reputation dimension: channels that were not measured for an entity (X only covers the top-50 buzz targets) are filled with the neutral prior, never re-normalized away — so "unmeasured" can never outrank "measured zero". Popularity is the one deliberate exception: it is the install percentile _within the platforms where the skill exists_, so a single-platform skill is scored against its own platform rather than penalized for not existing elsewhere. A percentile of zero signal is zero, not the tie-block mass.
7. **Anomalies are penalized, not silently kept.** The current detector flags identical install counts shared by 3+ skills of one publisher and reduces their composite score; it does **not** yet catch near-identical clusters, and bundle-level install counting (rule: see skills.sh row above) legitimately produces tightly clustered counts for multi-skill repos — including official ones. Statistical-outlier detection is on the roadmap. Exact thresholds are intentionally not published.

## Worth-Installing Score (best-100)

The overall score combines five dimensions (weights in parentheses, subject to calibration):

- **Popularity (0.30)** — weighted average of install percentiles within the platforms where the skill exists (skills.sh 0.5 / ClawHub 0.3 / SkillHub 0.2, re-normalized to present platforms)
- **Momentum (0.15)** — position in the skills.sh trending list, linearly scaled; skills.sh entities absent from the list score 0; entities outside skills.sh use the neutral prior. (A true growth percentile from our own snapshots will replace this as history accumulates.)
- **Reputation (0.20)** — social mention percentile composite: X 0.4 / GitHub 0.25 / HN 0.2 / Bluesky 0.15, with HN/Bluesky LLM-confirmed and generic-name skills scored on GitHub only (see rule 4)
- **Maintenance (0.15)** — ClawHub update recency (exponential decay, 45-day half-life) + ClawHub version-count percentile; ClawHub is the only source with content-update timestamps, so skills without a ClawHub presence use the neutral prior
- **Trust (0.20)** — official/verified publisher flags only: 0.2 base + 0.5 if in the skills.sh official list or ClawHub official feed + 0.3 if SkillHub verified-enterprise (capped at 1.0). No security scanning yet.

`WIS = 100 × Σ(weight_d × value_d) × anomaly_penalty` — unmeasured dimensions use the neutral prior 0.3; popularity is required. Empty dimension cells in `best-100.csv` mean "not measured — neutral prior 0.3 was used in the WIS".

Weight changes are recorded in the changelog section below.

## Known limitations

- skills.sh telemetry only counts CLI installs and can be disabled by users; CI installs may inflate some counts. Installs are bundle-level, so all skills of a popular multi-skill repo rank high together — the current lists do not fold same-repo skills.
- Star growth (`stars_1d`) is computed from our own daily snapshots (GitHub restricted the stargazers history API in July 2026); the launch day has no growth data.
- `rising-stars` currently cannot include skills.sh entities: skills.sh provides no created-at date, and our own first-seen index only becomes meaningful after its first day. skills.sh newcomers will join as the index accumulates; until then they are also not excluded from `best-100` by age.
- X counts are collected for the top-50 buzz targets only, paginate up to 5 pages (100 posts), and a capped value is published with `x_truncated=true` (rendered as "100+" in previews). The window is 7 calendar days.
- HN/Bluesky published counts are sample-extrapolated estimates (30/25-item samples); raw totals are published alongside.
- Social coverage is currently English-dominant (X / HN / Bluesky / GitHub). Non-English community signals are on the roadmap.
- New skills (under 30 days, where age is known) are listed in `rising-stars` instead of `best-100` to avoid penalizing them for missing history.

## Changelog

- **2026-08** — Initial methodology (v1). Same month: v1.1 — fully-qualified entity keys (same-name skills no longer merged), neutral-prior dimension filling, zero-signal percentile = 0, LLM relevance filtering for HN/Bluesky, X pagination past the 20/page cap, `most-positive` withdrawn (judgement-based rankings deferred), X post texts replaced by links in public data.
- **2026-08 (v1.2)** — Post-audit corrections: neutral-prior filling extended inside the reputation dimension (re-normalization made unmeasured channels outrank measured zeros); generic-name skills excluded from social-buzz and from X/HN/Bluesky scoring; launch-week partial buckets no longer produce growth percentages; raw install counts added to `best-100.csv`; `hn_raw_7d`/`bsky_raw_7d` and `tracked_skills` columns added; time-based scores now reference the data date for reproducibility; dimension descriptions in this document rewritten to match the implementation exactly.
