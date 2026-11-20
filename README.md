<div align="center">

# 🏆 Best Agent Skills

**Daily-updated Top 100 Agent Skills rankings — installs, growth, and social buzz aggregated from skills.sh, ClawHub, Tencent SkillHub, GitHub, X and more. Open data (CSV).**

[![Data updated](https://img.shields.io/badge/dynamic/regex?url=https%3A%2F%2Fraw.githubusercontent.com%2FLinklyAI%2Fbest-skills%2Fmain%2FREADME.md&search=Last%20updated%3A%20%5C%2A%5C%2A%28%5Cd%7B4%7D-%5Cd%7B2%7D-%5Cd%7B2%7D%29%5C%2A%5C%2A&replace=%241&label=data%20updated&color=brightgreen)](data/latest)
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

> Last updated: **2026-11-20** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 81.5 | C |
| 2 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.3 | C |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 75 | C |
| 4 | [microsoft-foundry](https://www.skills.sh/microsoft/azure-skills/microsoft-foundry) | [microsoft](https://www.skills.sh/microsoft) | 67.2 | C |
| 5 | [azure-diagnostics](https://www.skills.sh/microsoft/azure-skills/azure-diagnostics) | [microsoft](https://www.skills.sh/microsoft) | 67.1 | C |
| 6 | [azure-prepare](https://www.skills.sh/microsoft/azure-skills/azure-prepare) | [microsoft](https://www.skills.sh/microsoft) | 67.1 | C |
| 7 | [azure-ai](https://www.skills.sh/microsoft/azure-skills/azure-ai) | [microsoft](https://www.skills.sh/microsoft) | 67.1 | C |
| 8 | [azure-deploy](https://www.skills.sh/microsoft/azure-skills/azure-deploy) | [microsoft](https://www.skills.sh/microsoft) | 67.1 | C |
| 9 | [azure-validate](https://www.skills.sh/microsoft/azure-skills/azure-validate) | [microsoft](https://www.skills.sh/microsoft) | 66.9 | C |
| 10 | [azure-storage](https://www.skills.sh/microsoft/azure-skills/azure-storage) | [microsoft](https://www.skills.sh/microsoft) | 66.8 | C |

➡️ Full list: [best-100.csv](data/2026-11-20/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,447,283 | — | — |
| 2 | dev-god | — | — | 12,129,610 |
| 3 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,638,232 | — | — |
| 4 | multi-search-engine | — | — | 11,166,531 |
| 5 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,610,830 | — | — |
| 6 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,602,837 | — | — |
| 7 | aigccerts | — | — | 6,875,770 |
| 8 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,579,926 | — | — |
| 9 | dev-expert-pro | — | — | 6,333,266 |
| 10 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,524,059 | — | — |

➡️ Full list: [top-installs.csv](data/2026-11-20/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [ai-video-generation](https://www.skills.sh/beltsh/superpowers/ai-video-generation) | 28,920 | — |
| 2 | [ai-image-generation](https://www.skills.sh/beltsh/superpowers/ai-image-generation) | 28,902 | — |
| 3 | [ai-avatar-video](https://www.skills.sh/beltsh/superpowers/ai-avatar-video) | 28,901 | — |
| 4 | [twitter-automation](https://www.skills.sh/beltsh/superpowers/twitter-automation) | 28,901 | — |
| 5 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,524,059 | -1.8 |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,610,830 | -0.3 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,447,283 | -0.3 |
| 8 | [website-builder](https://www.skills.sh/flowkit-labs/skills/website-builder) | 125,772 | — |
| 9 | [ai-image-generation](https://www.skills.sh/gencraft-labs/skills/ai-image-generation) | 633,903 | -2.1 |
| 10 | [image-to-video](https://www.skills.sh/gencraft-labs/skills/image-to-video) | 633,584 | -1.9 |

➡️ Full list: [trending-7d.csv](data/2026-11-20/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 70+ | 8 | 17 | 43 |
| 2 | self-improving | 33+ | 4 | 39 | 3 |
| 3 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 31 | 1 | 12 | 2 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 72+ | 0 | 6 | 29 |
| 5 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 69+ | 0 | 1 | 98 |
| 6 | proactive-agent | 87+ | 0 | 7 | 2 |
| 7 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 8 | 33 | 11 |
| 8 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 16 | 0 | 2 | 247 |
| 9 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 23 | 0 | 18 | 33 |
| 10 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 23 | 0 | 2 | 7 |

➡️ Full list: [social-buzz.csv](data/2026-11-20/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | ai-insurance-advisor | 2026-11-19 | 300 |
| 2 | insurance-advisor-china | 2026-11-19 | 289 |
| 3 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-11-19 | 176 |
| 4 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-11-17 | 53 |
| 5 | [free-ride](https://clawhub.ai/shaivpidadi/skills/free-ride) | 2026-11-18 | 10 |
| 6 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-11-10 | 30 |
| 7 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-11-07 | 191 |
| 8 | opentwitter-mcp | 2026-11-16 | 4 |
| 9 | scrapling-official | 2026-11-05 | 17 |
| 10 | cellcog | 2026-11-01 | 54 |

➡️ Full list: [most-active.csv](data/2026-11-20/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100 (verified publishers)</b></summary>

| # | Skill | Vendor | Verified by |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | dev-god | 阿客（北京）科技有限公司 | skillhub |
| 3 | multi-search-engine | 成都智创未来教育管理合伙企业（有限合伙） | skillhub |
| 4 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 5 | aigccerts | 上海国信公链数据科技有限公司 | skillhub |
| 6 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 7 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 8 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 9 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |
| 10 | [obsidian](https://clawhub.ai/steipete/skills/obsidian) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ Full list: [official-100.csv](data/2026-11-20/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1329 | 444,969 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-11-20/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [mattpocock/skills](https://github.com/mattpocock/skills) | 328,161 | 2026-11-19 |
| 2 | [obra/superpowers](https://github.com/obra/superpowers) | 322,072 | 2026-11-03 |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 307,289 | 2026-11-20 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | 197,705 | 2026-11-16 |
| 5 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 194,845 | 2026-10-29 |
| 6 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 156,340 | 2026-11-20 |
| 7 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 151,770 | 2026-11-19 |
| 8 | [vercel/next.js](https://github.com/vercel/next.js) | 143,601 | 2026-11-20 |
| 9 | [stablyai/orca](https://github.com/stablyai/orca) | 129,903 | 2026-11-20 |
| 10 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 128,588 | 2026-11-19 |

➡️ Full list: [top-repos.csv](data/2026-11-20/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | cic | 4 | 0.93 |
| 2 | patent-search-i | 26 | 0.888 |
| 3 | proactive-agent | 24 | 0.861 |
| 4 | design-image-search | 26 | 0.85 |
| 5 | patent-novelty-i | 25 | 0.809 |
| 6 | dy-search | 22 | 0.803 |
| 7 | xiaohs-search | 22 | 0.802 |
| 8 | xiaohs-profile | 22 | 0.795 |
| 9 | dy-comments | 22 | 0.794 |
| 10 | b-profile | 21 | 0.793 |

➡️ Full list: [rising-stars.csv](data/2026-11-20/rankings/rising-stars.csv)

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
