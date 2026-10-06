<div align="center">

# 🏆 Best Agent Skills

**Daily-updated Top 100 Agent Skills rankings — installs, growth, and social buzz aggregated from skills.sh, ClawHub, Tencent SkillHub, GitHub, X and more. Open data (CSV).**

[![Data updated](https://img.shields.io/github/last-commit/LinklyAI/best-skills?label=data%20updated&color=brightgreen)](data/latest)
[![Refresh](https://img.shields.io/badge/refresh-daily-blue)](#rankings)
[![Rankings](https://img.shields.io/badge/rankings-9-orange)](#rankings)
[![Skills tracked](https://img.shields.io/badge/skills%20tracked-10%2C000%2B-blueviolet)](data/latest)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](LICENSE)
[![Stars](https://img.shields.io/github/stars/LinklyAI/best-skills?color=yellow)](https://github.com/LinklyAI/best-skills)
[![Follow @BlueeonY on X](https://img.shields.io/badge/X-%40BlueeonY-000000?logo=x&logoColor=white)](https://x.com/BlueeonY)

[English](README.md) | [简体中文](docs/README.zh-CN.md) | [日本語](docs/README.ja.md) | [한국어](docs/README.ko.md) | [Español](docs/README.es.md) | [Deutsch](docs/README.de.md) | [Русский](docs/README.ru.md)

Rankings shift daily — ⭐ **Star** for updates, or follow [**@BlueeonY**](https://x.com/BlueeonY) on X for the daily movers.

</div>

<p align="center">
  <a href="https://linkly.ai/skills">
    <img src="docs/assets/best-skills-rankings.webp" alt="Best Agent Skills Rankings web preview">
  </a>
  <br>
  <a href="https://linkly.ai/skills">Explore the live, interactive rankings →</a>
</p>

## Why this exists

Every skills registry only sees its own ecosystem. skills.sh counts Claude/Vercel CLI installs, ClawHub counts OpenClaw downloads, Tencent SkillHub counts installs from China — and none of them see social buzz. **Best Skills merges all of these views into one cross-ecosystem picture**: for each skill you can see global installs, China installs, and social mentions side by side. No other ranking does this.

- **9 rankings**, refreshed daily
- **Raw numbers preserved** — every CSV keeps per-platform original counts so anyone can verify or re-rank
- **Never adds apples to oranges** — cross-platform numbers are shown side by side, ranked by within-platform percentile composite (see [methodology](docs/methodology.md))
- **Judged by [jev](https://openrouter.ai/typesafe/jev-1.13), not keyword counts** — TypeSafe's decision model checks whether each social post is really about the skill, whether a listing is a real, maintained skill, and which category it belongs to; placeholders, deprecated and harmful listings are left out of the rankings, and every probability is published (see [methodology](docs/methodology.md#judgements-jev))

## How to use the rankings

**Reading it yourself.** Each list answers one question (see [What each list means](#what-each-list-means)); `best-100` is the place to start. The tables below show each list's Top 10, the CSVs hold the full Top 100, and [linkly.ai/skills](https://linkly.ai/skills) renders them for browsing. `Cov` tells you how many registries a score rests on (A = all three, C = one), and every CSV keeps the per-platform counts next to the score, so any number can be checked against its source.

**Giving it to an AI agent.** Paste one line into Claude Code, Codex, Cursor, OpenClaw or any agent that can fetch a URL:

```text
Read https://linkly.ai/skills/llms.txt
```

[llms.txt](llms.txt) tells the agent where the CSVs are, what every column means, how to go from a question to the right file, and the rules for using the numbers. To make the rankings part of an agent's standing knowledge instead, install this repository as a skill:

```bash
npx skills add https://github.com/LinklyAI/best-skills --skill best-skills
```

## Rankings

<!-- RANKINGS:START -->

> Last updated: **2026-10-06** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 80.9 | C |
| 2 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.4 | C |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 71.9 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.8 | C |
| 5 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | 67.6 | C |
| 6 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 67 | B |
| 7 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 66.5 | C |
| 8 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 66.2 | C |
| 9 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 66.2 | B |
| 10 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 65.9 | C |

➡️ Full list: [best-100.csv](data/2026-10-06/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,704,728 | — | — |
| 2 | dev-expert | — | — | 2,416,779 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,283,766 | — | — |
| 4 | parenting-expert | — | — | 1,814,272 |
| 5 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 482,797 | 1,322,501 |
| 6 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,098,377 | — | — |
| 7 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 1,046,225 | — | — |
| 8 | tencent-docs | — | — | 1,463,641 |
| 9 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,033,791 | — | — |
| 10 | [tdd](https://www.skills.sh/mattpocock/skills/tdd) | 1,017,905 | — | — |

➡️ Full list: [top-installs.csv](data/2026-10-06/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 417,388 | — |
| 2 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 634,617 | 1 |
| 3 | [ai-image-generation](https://www.skills.sh/magentosh/superpowers/ai-image-generation) | 286,322 | 81.8 |
| 4 | [ai-avatar-video](https://www.skills.sh/magentosh/superpowers/ai-avatar-video) | 286,156 | 81.8 |
| 5 | [ai-video-generation](https://www.skills.sh/magentosh/superpowers/ai-video-generation) | 286,187 | 81.8 |
| 6 | [twitter-automation](https://www.skills.sh/magentosh/superpowers/twitter-automation) | 286,045 | 81.7 |
| 7 | [hyperframes-animation](https://www.skills.sh/heygen-com/hyperframes/hyperframes-animation) | 663,927 | 36.4 |
| 8 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,704,728 | 3.5 |
| 9 | [hyperframes-creative](https://www.skills.sh/heygen-com/hyperframes/hyperframes-creative) | 633,618 | 60.5 |
| 10 | [hyperframes-registry](https://www.skills.sh/heygen-com/hyperframes/hyperframes-registry) | 701,415 | 19.7 |

➡️ Full list: [trending-7d.csv](data/2026-10-06/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 72+ | 1 | 2 | 50 |
| 2 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 60 | 6 | 5 | 27 |
| 3 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 66+ | 4 | 48 | 8 |
| 4 | [proactive-agent](https://clawhub.ai/halthelobster/skills/proactive-agent) | 76 | 1 | 2 | 1 |
| 5 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 26 | 2 | 9 | 8 |
| 6 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 32 | 0 | 6 | 145 |
| 7 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 46 | 1 | 0 | 2 |
| 8 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 14 | 0 | 1 | 227 |
| 9 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 2 | 13 | 14 |
| 10 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 11 | 0 | 3 | 11 |

➡️ Full list: [social-buzz.csv](data/2026-10-06/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-10-05 | 140 |
| 2 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 2026-10-04 | 40 |
| 3 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-10-02 | 182 |
| 4 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-10-02 | 23 |
| 5 | [stripe-api](https://clawhub.ai/byungkyu/skills/stripe-api) | 2026-10-02 | 22 |
| 6 | [linear-api](https://clawhub.ai/byungkyu/skills/linear-api) | 2026-10-02 | 21 |
| 7 | google-workspace-admin | 2026-10-02 | 20 |
| 8 | [linkedin-api](https://clawhub.ai/byungkyu/skills/linkedin-api) | 2026-10-02 | 20 |
| 9 | [salesforce-api](https://clawhub.ai/byungkyu/skills/salesforce-api) | 2026-10-02 | 19 |
| 10 | notion-api-skill | 2026-10-02 | 19 |

➡️ Full list: [most-active.csv](data/2026-10-06/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100 (verified publishers)</b></summary>

| # | Skill | Vendor | Verified by |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 3 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 4 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 5 | multi-search-engine | 成都智创未来教育管理合伙企业（有限合伙） | skillhub |
| 6 | [github](https://clawhub.ai/steipete/skills/github) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 7 | mysteel-datasearch | 上海钢联电子商务股份有限公司 | skillhub |
| 8 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 9 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 10 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |

➡️ Full list: [official-100.csv](data/2026-10-06/rankings/official-100.csv)

</details>

<details>
<summary><b>🏢 Official Vendors (grouped by platform)</b></summary>

| # | Platform | Vendor | Skills | Installs/Downloads |
| --- | --- | --- | --- | --- |
| 1 | [skills.sh](https://www.skills.sh) | [microsoft](https://www.skills.sh/microsoft) | 582 | 7,098,914 |
| 2 | [skills.sh](https://www.skills.sh) | [vercel-labs](https://www.skills.sh/vercel-labs) | 252 | 3,192,303 |
| 3 | [skills.sh](https://www.skills.sh) | [github](https://www.skills.sh/github) | 406 | 2,002,122 |
| 4 | [skills.sh](https://www.skills.sh) | [anthropics](https://www.skills.sh/anthropics) | 605 | 1,942,412 |
| 5 | [skills.sh](https://www.skills.sh) | [firebase](https://www.skills.sh/firebase) | 55 | 685,617 |
| 6 | [skills.sh](https://www.skills.sh) | [firecrawl](https://www.skills.sh/firecrawl) | 286 | 482,310 |
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1160 | 426,916 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-10-06/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 295,661 | 2026-09-27 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 277,095 | 2026-10-05 |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 273,652 | 2026-10-05 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | 179,792 | 2026-10-05 |
| 5 | [langgenius/dify](https://github.com/langgenius/dify) | 157,898 | 2026-10-05 |
| 6 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 155,979 | 2026-10-05 |
| 7 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 149,524 | 2026-10-05 |
| 8 | [vercel/next.js](https://github.com/vercel/next.js) | 143,195 | 2026-10-06 |
| 9 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 133,349 | 2026-10-03 |
| 10 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 125,163 | 2026-10-05 |

➡️ Full list: [top-repos.csv](data/2026-10-06/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | parenting-expert | 20 | 0.998 |
| 2 | project-explanation | 6 | 0.977 |
| 3 | demo-material-generation | 6 | 0.976 |
| 4 | luhe-paper-free-pro | 20 | 0.973 |
| 5 | cic | 8 | 0.968 |
| 6 | rosemond-contract-compliance | 7 | 0.965 |
| 7 | from-ldeas-to-requirements-logic | 6 | 0.958 |
| 8 | public-opinion-monitoring | 6 | 0.956 |
| 9 | flowchart-generation | 6 | 0.954 |
| 10 | ai-writing | 6 | 0.952 |

➡️ Full list: [rising-stars.csv](data/2026-10-06/rankings/rising-stars.csv)

</details>

<!-- RANKINGS:END -->

### What each list means

| List               | What it ranks                                                                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| `best-100`         | Overall Worth-Installing Score (popularity + momentum + buzz + maintenance + trust)                                          |
| `top-installs`     | Most installed, all ecosystems merged                                                                                        |
| `trending-7d`      | Fastest growing over the last 7 days                                                                                         |
| `social-buzz`      | Most talked about on X, Hacker News, Bluesky, and GitHub (generic-name skills excluded — their mentions can't be attributed) |
| `most-active`      | Most frequently updated among popular skills                                                                                 |
| `official-100`     | Most popular skills from verified publishers (platform-verified orgs and individuals)                                        |
| `official-vendors` | Verified vendors ranked by total installs                                                                                    |
| `top-repos`        | GitHub repositories behind the skills, by stars                                                                              |
| `rising-stars`     | Best newcomers (first seen under 30 days)                                                                                    |

## Data

```text
data/
├── YYYY-MM-DD/
│   ├── raw/                # per-platform original counts, untouched
│   │   ├── skills-sh.csv · clawhub.csv · skillhub.csv · github-repos.csv
│   │   └── buzz.csv · x-posts.csv · judgments.csv · …
│   └── rankings/           # the 9 ranking lists computed from raw/
│       ├── best-100.csv · top-installs.csv · trending-7d.csv
│       └── social-buzz.csv · … · rising-stars.csv
├── latest/                 # always a copy of the most recent day
└── index/
    └── first-seen.csv      # cumulative first-seen dates (powers rising-stars)
```

One folder per day, CSV only. Composite scores are always accompanied by the raw per-platform numbers they were derived from — start from `data/latest/` if you just want today's lists.

See [docs/methodology.md](docs/methodology.md) for data sources, normalization rules, and known limitations.

## Data sources & attribution

Install/download counts are collected from public endpoints of [skills.sh](https://www.skills.sh), [ClawHub](https://clawhub.ai) (per its third-party directory policy; skill pages link back to their canonical ClawHub listing), [Tencent SkillHub](https://skillhub.cn), and the [GitHub API](https://docs.github.com). Social signals come from X, [Hacker News (Algolia)](https://hn.algolia.com), [Bluesky](https://bsky.app), and GitHub search. This project is not endorsed by or affiliated with any of these platforms. Counts reflect each platform's own methodology and are never summed across platforms.

## License

Data and documentation are released under [CC BY 4.0](LICENSE) — free to use, republish, and build on, commercial use included.

### How to attribute

Include this line wherever the data appears:

> Data from [Best Skills](https://github.com/LinklyAI/best-skills) by [@BlueeonY](https://x.com/BlueeonY) — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Keep the link to this repository intact, and keep the per-platform attributions listed above. That is the whole requirement — no separate permission is needed.

Built something with it? [@BlueeonY](https://x.com/BlueeonY) would love to see it — not required by the license, just appreciated.

---

Built by [@BlueeonY](https://x.com/BlueeonY) at [Linkly AI](https://linkly.ai) — an AI-powered local knowledge base with agent skills support.

Found this useful? A ⭐ helps more people find it.
