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

> Last updated: **2026-09-27** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 80.8 | C |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 78.5 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 73.4 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.6 | C |
| 5 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 68.7 | C |
| 6 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | [mattpocock](https://www.skills.sh/mattpocock) | 68 | C |
| 7 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 66.7 | B |
| 8 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 66.5 | C |
| 9 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | 64.5 | B |
| 10 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 64.4 | C |

➡️ Full list: [best-100.csv](data/2026-09-27/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,580,878 | — | — |
| 2 | dev-expert | — | — | 1,604,525 |
| 3 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 481,361 | 1,255,463 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,230,025 | — | — |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,051,055 | — | — |
| 6 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 998,434 | — | — |
| 7 | tencent-docs | — | — | 1,241,398 |
| 8 | [tdd](https://www.skills.sh/mattpocock/skills/tdd) | 970,404 | — | — |
| 9 | parenting-expert | — | — | 1,054,663 |
| 10 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 951,194 | — | — |

➡️ Full list: [top-installs.csv](data/2026-09-27/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 164,538 | — |
| 2 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 508,015 | 231.4 |
| 3 | [ai-avatar-video](https://www.skills.sh/101-skills/superpowers/ai-avatar-video) | 507,369 | 236.4 |
| 4 | [ai-image-generation](https://www.skills.sh/101-skills/superpowers/ai-image-generation) | 507,630 | 233.8 |
| 5 | [twitter-automation](https://www.skills.sh/101-skills/superpowers/twitter-automation) | 507,666 | 235.1 |
| 6 | [ios-design](https://www.skills.sh/uizze.sh/ios-design) | 69,751 | — |
| 7 | [google-agents-cli-adk-code](https://www.skills.sh/google/agents-cli/google-agents-cli-adk-code) | 405,327 | 26.7 |
| 8 | [google-agents-cli-workflow](https://www.skills.sh/google/agents-cli/google-agents-cli-workflow) | 404,904 | 26.6 |
| 9 | [google-agents-cli-eval](https://www.skills.sh/google/agents-cli/google-agents-cli-eval) | 404,871 | 26.7 |
| 10 | [google-agents-cli-scaffold](https://www.skills.sh/google/agents-cli/google-agents-cli-scaffold) | 404,803 | 26.6 |

➡️ Full list: [trending-7d.csv](data/2026-09-27/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 79+ | 4 | 12 | 41 |
| 2 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 80 | 7 | 2 | 26 |
| 3 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 48 | 1 | 2 | 149 |
| 4 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 61+ | 1 | 33 | 8 |
| 5 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 38 | 2 | 2 | 80 |
| 6 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 14 | 1 | 1 | 14 |
| 7 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 16 | 1 | 3 | 1 |
| 8 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 4 | 22 | 8 |
| 9 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 41 | 0 | 1 | 4 |
| 10 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 8 | 0 | 0 | 199 |

➡️ Full list: [social-buzz.csv](data/2026-09-27/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-09-26 | 132 |
| 2 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-09-24 | 176 |
| 3 | web-search-plus | 2026-09-24 | 62 |
| 4 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-09-24 | 47 |
| 5 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-09-24 | 21 |
| 6 | [stripe-api](https://clawhub.ai/byungkyu/skills/stripe-api) | 2026-09-24 | 20 |
| 7 | [linear-api](https://clawhub.ai/byungkyu/skills/linear-api) | 2026-09-24 | 19 |
| 8 | google-workspace-admin | 2026-09-24 | 18 |
| 9 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-09-23 | 25 |
| 10 | [linkedin-api](https://clawhub.ai/byungkyu/skills/linkedin-api) | 2026-09-24 | 17 |

➡️ Full list: [most-active.csv](data/2026-09-27/rankings/most-active.csv)

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
| 7 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 8 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 9 | mysteel-datasearch | 上海钢联电子商务股份有限公司 | skillhub |
| 10 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |

➡️ Full list: [official-100.csv](data/2026-09-27/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1063 | 428,742 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-09-27/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 291,956 | 2026-09-26 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 270,274 | 2026-09-24 |
| 3 | [anthropics/skills](https://github.com/anthropics/skills) | 178,562 | 2026-09-24 |
| 4 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 148,214 | 2026-09-26 |
| 5 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 146,500 | 2026-09-14 |
| 6 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 130,846 | 2026-09-26 |
| 7 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 124,639 | 2026-09-24 |
| 8 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 116,412 | 2026-09-26 |
| 9 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 107,961 | 2026-09-26 |
| 10 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 99,287 | 2026-09-26 |

➡️ Full list: [top-repos.csv](data/2026-09-27/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | parenting-expert | 11 | 0.996 |
| 2 | mysteel-datasearch | 26 | 0.989 |
| 3 | luhe-paper-free-pro | 11 | 0.981 |
| 4 | talking-avatar-video | 25 | 0.969 |
| 5 | tencent-meeting-mcp | 23 | 0.963 |
| 6 | gongwen-writting-2 | 6 | 0.944 |
| 7 | poster-design-studio | 17 | 0.94 |
| 8 | ai-podcast-voiceover | 25 | 0.938 |
| 9 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 27 | 0.937 |
| 10 | [twitter-automation](https://www.skills.sh/101-skills/superpowers/twitter-automation) | 27 | 0.936 |

➡️ Full list: [rising-stars.csv](data/2026-09-27/rankings/rising-stars.csv)

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
