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

> Last updated: **2026-09-23** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 81.2 | C |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 78.7 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.3 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.9 | C |
| 5 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | 68.6 | C |
| 6 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 67.5 | B |
| 7 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | 65.6 | B |
| 8 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 65.4 | C |
| 9 | [gog](https://clawhub.ai/steipete/skills/gog) | [steipete](https://clawhub.ai/steipete) | 65.2 | B |
| 10 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 64.7 | C |

➡️ Full list: [best-100.csv](data/2026-09-23/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,525,095 | — | — |
| 2 | dev-expert | — | — | 1,314,314 |
| 3 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 480,727 | 1,231,161 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,203,681 | — | — |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,028,308 | — | — |
| 6 | tencent-docs | — | — | 1,153,653 |
| 7 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 977,955 | — | — |
| 8 | [tdd](https://www.skills.sh/mattpocock/skills/tdd) | 950,099 | — | — |
| 9 | find-skills | — | — | 1,018,825 |
| 10 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 913,352 | — | — |

➡️ Full list: [top-installs.csv](data/2026-09-23/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [ai-image-generation](https://www.skills.sh/101-skills/superpowers/ai-image-generation) | 370,962 | 233.8 |
| 2 | [ai-avatar-video](https://www.skills.sh/101-skills/superpowers/ai-avatar-video) | 370,737 | 236.4 |
| 3 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 371,344 | 231.4 |
| 4 | [twitter-automation](https://www.skills.sh/101-skills/superpowers/twitter-automation) | 371,041 | 235.1 |
| 5 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 376,991 | -1.2 |
| 6 | [ai-video-generation](https://www.skills.sh/qu-skills/superpowers/ai-video-generation) | 180,004 | 234.3 |
| 7 | [ai-avatar-video](https://www.skills.sh/qu-skills/superpowers/ai-avatar-video) | 180,545 | 228.9 |
| 8 | [ai-image-generation](https://www.skills.sh/qu-skills/superpowers/ai-image-generation) | 179,986 | 234.8 |
| 9 | [twitter-automation](https://www.skills.sh/qu-skills/superpowers/twitter-automation) | 180,177 | 231.5 |
| 10 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,525,095 | 3.7 |

➡️ Full list: [trending-7d.csv](data/2026-09-23/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 87+ | 3 | 12 | 21 |
| 2 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 66 | 2 | 5 | 33 |
| 3 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 63+ | 1 | 41 | 9 |
| 4 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 41 | 3 | 3 | 47 |
| 5 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 16 | 1 | 5 | 3 |
| 6 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 50 | 0 | 1 | 93 |
| 7 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 2 | 29 | 6 |
| 8 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 9 | 0 | 1 | 130 |
| 9 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 36 | 0 | 1 | 2 |
| 10 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 15 | 0 | 2 | 4 |

➡️ Full list: [social-buzz.csv](data/2026-09-23/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-09-22 | 128 |
| 2 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-09-21 | 23 |
| 3 | [youtube-full](https://clawhub.ai/therohitdas/skills/youtube-full) | 2026-09-21 | 16 |
| 4 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-09-18 | 173 |
| 5 | [openclaw-token-optimizer](https://clawhub.ai/asif2bd/skills/openclaw-token-optimizer) | 2026-09-19 | 25 |
| 6 | polymarket-weather-trader | 2026-09-18 | 56 |
| 7 | email-gmail-outlook | 2026-09-20 | 8 |
| 8 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-09-13 | 20 |
| 9 | [stripe-api](https://clawhub.ai/byungkyu/skills/stripe-api) | 2026-09-13 | 19 |
| 10 | [linear-api](https://clawhub.ai/byungkyu/skills/linear-api) | 2026-09-13 | 18 |

➡️ Full list: [most-active.csv](data/2026-09-23/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100 (verified publishers)</b></summary>

| # | Skill | Vendor | Verified by |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 4 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 5 | [github](https://clawhub.ai/steipete/skills/github) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 6 | multi-search-engine | 成都智创未来教育管理合伙企业（有限合伙） | skillhub |
| 7 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 8 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 9 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |
| 10 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ Full list: [official-100.csv](data/2026-09-23/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1036 | 425,728 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-09-23/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 290,282 | 2026-09-22 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 267,976 | 2026-09-18 |
| 3 | [anthropics/skills](https://github.com/anthropics/skills) | 177,683 | 2026-09-22 |
| 4 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 147,688 | 2026-09-22 |
| 5 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 144,527 | 2026-09-14 |
| 6 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 129,941 | 2026-09-21 |
| 7 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 124,441 | 2026-09-21 |
| 8 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 115,985 | 2026-09-18 |
| 9 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 107,420 | 2026-09-22 |
| 10 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 98,509 | 2026-09-23 |

➡️ Full list: [top-repos.csv](data/2026-09-23/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | parenting-expert | 7 | 0.994 |
| 2 | mysteel-datasearch | 22 | 0.984 |
| 3 | luhe-paper-free-pro | 7 | 0.981 |
| 4 | tencent-meeting-mcp | 19 | 0.967 |
| 5 | talking-avatar-video | 21 | 0.966 |
| 6 | poster-design-studio | 13 | 0.943 |
| 7 | ai-podcast-voiceover | 21 | 0.937 |
| 8 | gh-cli-readonly-agent | 10 | 0.933 |
| 9 | suno-lyrics-to-song | 12 | 0.929 |
| 10 | gpt-image-2-5-studio | 10 | 0.927 |

➡️ Full list: [rising-stars.csv](data/2026-09-23/rankings/rising-stars.csv)

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
