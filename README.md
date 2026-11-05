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

> Last updated: **2026-11-05** (UTC) · Top 10 preview per list — full Top 100 in the CSVs.

<details open>
<summary><b>🏆 Best 100 (Worth-Installing Score)</b></summary>

| # | Skill | Vendor | WIS | Cov |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 81.8 | C |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 78.1 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.4 | C |
| 4 | [microsoft-foundry](https://www.skills.sh/microsoft/azure-skills/microsoft-foundry) | [microsoft](https://www.skills.sh/microsoft) | 67.3 | C |
| 5 | [azure-prepare](https://www.skills.sh/microsoft/azure-skills/azure-prepare) | [microsoft](https://www.skills.sh/microsoft) | 67.3 | C |
| 6 | [azure-ai](https://www.skills.sh/microsoft/azure-skills/azure-ai) | [microsoft](https://www.skills.sh/microsoft) | 67.3 | C |
| 7 | [azure-diagnostics](https://www.skills.sh/microsoft/azure-skills/azure-diagnostics) | [microsoft](https://www.skills.sh/microsoft) | 67.2 | C |
| 8 | [azure-deploy](https://www.skills.sh/microsoft/azure-skills/azure-deploy) | [microsoft](https://www.skills.sh/microsoft) | 67 | C |
| 9 | [azure-validate](https://www.skills.sh/microsoft/azure-skills/azure-validate) | [microsoft](https://www.skills.sh/microsoft) | 67 | C |
| 10 | [azure-compliance](https://www.skills.sh/microsoft/azure-skills/azure-compliance) | [microsoft](https://www.skills.sh/microsoft) | 67 | C |

➡️ Full list: [best-100.csv](data/2026-11-05/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Top Installs (all ecosystems)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub CN |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,210,038 | — | — |
| 2 | dev-god | — | — | 11,248,599 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,496,846 | — | — |
| 4 | multi-search-engine | — | — | 10,748,906 |
| 5 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,420,220 | — | — |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,381,646 | — | — |
| 7 | dev-expert-pro | — | — | 6,267,019 |
| 8 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,381,361 | — | — |
| 9 | dev-expert | — | — | 6,003,164 |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 490,574 | 1,598,822 |

➡️ Full list: [top-installs.csv](data/2026-11-05/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 Trending (7 days)</b></summary>

| # | Skill | Installs | Weekly Δ% |
| --- | --- | --- | --- |
| 1 | [ai-image-generation](https://www.skills.sh/skills-shell/superpowers/ai-image-generation) | 660,250 | 60 |
| 2 | [ai-video-generation](https://www.skills.sh/skills-shell/superpowers/ai-video-generation) | 660,222 | 60 |
| 3 | [twitter-automation](https://www.skills.sh/skills-shell/superpowers/twitter-automation) | 660,157 | 60 |
| 4 | [ai-avatar-video](https://www.skills.sh/skills-shell/superpowers/ai-avatar-video) | 659,870 | 60 |
| 5 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 982,513 | 87.2 |
| 6 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,233,455 | 0 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,210,038 | -5.2 |
| 8 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,381,646 | 10.3 |
| 9 | [media-use](https://www.skills.sh/heygen-com/hyperframes/media-use) | 1,292,467 | -16.7 |
| 10 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,420,220 | -13.2 |

➡️ Full list: [trending-7d.csv](data/2026-11-05/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Social Buzz (X · HN · Bluesky · GitHub, 7 days)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 73+ | 2 | 9 | 53 |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 57+ | 1 | 8 | 104 |
| 3 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 72+ | 4 | 4 | 2 |
| 4 | [proactive-agent](https://clawhub.ai/halthelobster/skills/proactive-agent) | 82+ | 1 | 7 | 1 |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 23 | 1 | 1 | 16 |
| 6 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 85+ | 0 | 8 | 38 |
| 7 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 56 | 0 | 3 | 175 |
| 8 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 19 | 0 | 5 | 182 |
| 9 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 4 | 19 | 7 |
| 10 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 28 | 0 | 9 | 1 |

➡️ Full list: [social-buzz.csv](data/2026-11-05/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Most Active (popular & frequently updated)</b></summary>

| # | Skill | Updated | Versions |
| --- | --- | --- | --- |
| 1 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-11-04 | 190 |
| 2 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-11-04 | 163 |
| 3 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-11-04 | 51 |
| 4 | [ai-persona-os](https://clawhub.ai/jeffjhunter/skills/ai-persona-os) | 2026-11-04 | 23 |
| 5 | tencent-cos-skill | 2026-11-04 | 16 |
| 6 | [cellcog](https://clawhub.ai/nitishgargiitd/skills/cellcog) | 2026-11-01 | 54 |
| 7 | video-generation-cellcog | 2026-11-01 | 20 |
| 8 | image-generation-cellcog | 2026-11-01 | 19 |
| 9 | creative-writing-cellcog | 2026-11-01 | 17 |
| 10 | [neural-memory](https://clawhub.ai/nhadaututtheky/skills/neural-memory) | 2026-10-23 | 57 |

➡️ Full list: [most-active.csv](data/2026-11-05/rankings/most-active.csv)

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

➡️ Full list: [official-100.csv](data/2026-11-05/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1281 | 437,912 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Full list: [official-vendors.csv](data/2026-11-05/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Top Repositories</b></summary>

| # | Repository | Stars | Pushed |
| --- | --- | --- | --- |
| 1 | [mattpocock/skills](https://github.com/mattpocock/skills) | 313,308 | 2026-11-04 |
| 2 | [obra/superpowers](https://github.com/obra/superpowers) | 312,441 | 2026-11-03 |
| 3 | [anthropics/skills](https://github.com/anthropics/skills) | 187,417 | 2026-10-28 |
| 4 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 184,543 | 2026-10-29 |
| 5 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 154,553 | 2026-11-04 |
| 6 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 145,229 | 2026-11-04 |
| 7 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 127,368 | 2026-11-04 |
| 8 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 120,042 | 2026-11-02 |
| 9 | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) | 117,511 | 2026-11-04 |
| 10 | [stablyai/orca](https://github.com/stablyai/orca) | 115,464 | 2026-11-05 |

➡️ Full list: [top-repos.csv](data/2026-11-05/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Rising Stars (under 30 days old)</b></summary>

| # | Skill | Age (days) | Popularity |
| --- | --- | --- | --- |
| 1 | dev-god | 28 | 0.999 |
| 2 | dev-expert-pro | 20 | 0.997 |
| 3 | aigccerts | 19 | 0.995 |
| 4 | xique-tender-pay | 28 | 0.904 |
| 5 | course-video-studio | 24 | 0.883 |
| 6 | [ai-music](https://www.skills.sh/gencraft-labs/skills/ai-music) | 29 | 0.86 |
| 7 | [video-edit](https://www.skills.sh/gencraft-labs/skills/video-edit) | 29 | 0.86 |
| 8 | course-narration-studio | 24 | 0.859 |
| 9 | [ai-video-generation](https://www.skills.sh/gencraft-labs/skills/ai-video-generation) | 29 | 0.859 |
| 10 | [ai-image-generation](https://www.skills.sh/gencraft-labs/skills/ai-image-generation) | 29 | 0.858 |

➡️ Full list: [rising-stars.csv](data/2026-11-05/rankings/rising-stars.csv)

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
