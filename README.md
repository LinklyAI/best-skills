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

> Last updated: **2026-10-29** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 78.1 | C |
| 2 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 77.9 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.1 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.5 | C |
| 5 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 66.9 | B |
| 6 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 66.8 | C |
| 7 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | 65.7 | C |
| 8 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 65.5 | C |
| 9 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 64.9 | C |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 64.9 | B |

➡️ Full list: [best-100.csv](data/2026-10-29/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,096,323 | — | — |
| 2 | dev-god | — | — | 10,593,525 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,454,486 | — | — |
| 4 | multi-search-engine | — | — | 10,344,851 |
| 5 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,306,005 | — | — |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,286,412 | — | — |
| 7 | dev-expert | — | — | 5,590,279 |
| 8 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,272,089 | — | — |
| 9 | dev-expert-pro | — | — | 5,278,771 |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 489,264 | 1,541,644 |

➡️ Full list: [top-installs.csv](data/2026-10-29/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,096,727 | -2.5 |
| 2 | [hyperframes-registry](https://www.skills.sh/heygen-com/hyperframes/hyperframes-registry) | 1,068,028 | 12.4 |
| 3 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,306,005 | -8.6 |
| 4 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,272,089 | 0.5 |
| 5 | [media-use](https://www.skills.sh/heygen-com/hyperframes/media-use) | 1,176,875 | 2.2 |
| 6 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 798,802 | -13.9 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,096,323 | 0.4 |
| 8 | [ai-image-generation](https://www.skills.sh/skills-shell/superpowers/ai-image-generation) | 485,208 | 33.6 |
| 9 | [ai-video-generation](https://www.skills.sh/skills-shell/superpowers/ai-video-generation) | 485,244 | 33.6 |
| 10 | [twitter-automation](https://www.skills.sh/skills-shell/superpowers/twitter-automation) | 485,201 | 33.6 |

➡️ Full list: [trending-7d.csv](data/2026-10-29/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 76+ | 1 | 5 | 36 |
| 2 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 70+ | 2 | 58 | 7 |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 48 | 1 | 2 | 92 |
| 4 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 26 | 1 | 16 | 12 |
| 5 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 80+ | 0 | 6 | 54 |
| 6 | [proactive-agent](https://clawhub.ai/halthelobster/skills/proactive-agent) | 82+ | 0 | 46 | 5 |
| 7 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 55 | 0 | 2 | 132 |
| 8 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 37 | 1 | 0 | 2 |
| 9 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 12 | 0 | 3 | 184 |
| 10 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 1 | 19 | 5 |

➡️ Full list: [social-buzz.csv](data/2026-10-29/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-10-28 | 160 |
| 2 | [cellcog](https://clawhub.ai/nitishgargiitd/skills/cellcog) | 2026-10-25 | 53 |
| 3 | [neural-memory](https://clawhub.ai/nhadaututtheky/skills/neural-memory) | 2026-10-23 | 57 |
| 4 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 2026-10-22 | 42 |
| 5 | cloudbase | 2026-10-19 | 238 |
| 6 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-10-20 | 29 |
| 7 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-10-19 | 50 |
| 8 | scrapling-official | 2026-10-17 | 16 |
| 9 | web-search-plus | 2026-10-10 | 63 |
| 10 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-10-02 | 182 |

➡️ Full list: [most-active.csv](data/2026-10-29/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100 (verified publishers)</b></summary>

| # | Skill | Vendor | Verified by |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | dev-god | 阿客（北京）科技有限公司 | skillhub |
| 3 | multi-search-engine | 成都智创未来教育管理合伙企业（有限合伙） | skillhub |
| 4 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 5 | aigccerts | 成都国信公链科技有限公司 | skillhub |
| 6 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 7 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 8 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 9 | cic | 成都国信公链科技有限公司 | skillhub |
| 10 | [obsidian](https://clawhub.ai/steipete/skills/obsidian) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ Full list: [official-100.csv](data/2026-10-29/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1257 | 435,454 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-10-29/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 307,434 | 2026-10-23 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 305,767 | 2026-10-27 |
| 3 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 291,763 | 2026-10-26 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | 184,517 | 2026-10-28 |
| 5 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 179,188 | 2026-10-29 |
| 6 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 153,747 | 2026-10-27 |
| 7 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 142,081 | 2026-10-26 |
| 8 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 126,836 | 2026-10-27 |
| 9 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 119,400 | 2026-10-27 |
| 10 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 115,815 | 2026-10-28 |

➡️ Full list: [top-repos.csv](data/2026-10-29/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | dev-god | 21 | 0.999 |
| 2 | dev-expert-pro | 13 | 0.996 |
| 3 | aigccerts | 12 | 0.994 |
| 4 | xique-tender-pay | 21 | 0.912 |
| 5 | course-video-studio | 17 | 0.892 |
| 6 | course-narration-studio | 17 | 0.869 |
| 7 | telehot-tender-review | 29 | 0.836 |
| 8 | slide-narration-studio | 14 | 0.823 |
| 9 | skill-creator | 16 | 0.821 |
| 10 | xique-bid-review-pay | 17 | 0.813 |

➡️ Full list: [rising-stars.csv](data/2026-10-29/rankings/rising-stars.csv)

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
