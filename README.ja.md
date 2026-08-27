<div align="center">

# 🏆 Best Skills

**毎日更新される Agent Skills Top 100 ランキング——skills.sh、ClawHub、Tencent SkillHub、GitHub、X などからインストール数、成長率、ソーシャルでの話題性を集約。オープンデータ（CSV）。**

[![データ更新](https://img.shields.io/github/last-commit/LinklyAI/best-skills?label=data%20updated&color=brightgreen)](data/latest)
[![更新頻度](https://img.shields.io/badge/refresh-daily-blue)](#ランキング)
[![ランキング](https://img.shields.io/badge/rankings-9-orange)](#ランキング)
[![追跡中の Skills](https://img.shields.io/badge/skills%20tracked-2%2C500%2B-blueviolet)](data/latest)
[![ライセンス：CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](LICENSE)

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md)

</div>

## このプロジェクトの目的

各 Skills レジストリが把握できるのは、それぞれのエコシステムだけです。skills.sh は Claude/Vercel CLI のインストール数、ClawHub は OpenClaw のダウンロード数、Tencent SkillHub は中国でのインストール数を集計していますが、いずれもソーシャルでの話題性は捉えていません。**Best Skills はこれらの視点を統合し、エコシステム横断の全体像を提供します**。Skill ごとに、世界のインストール数、中国でのインストール数、ソーシャルでの言及数を並べて確認できます。このようなランキングはほかにありません。

- **9 種類のランキング**を毎日更新
- **元の数値を保持**——各 CSV にはプラットフォームごとの元データが残り、誰でも検証や再ランキングが可能
- **比較できない数値は合算しない**——プラットフォーム横断の数値は並べて表示し、各プラットフォーム内のパーセンタイル複合値で順位付け（[方法論](docs/methodology.md)を参照）

## ランキング

<!-- RANKINGS:START -->

> 最終更新：**2026-08-27**（UTC）· 各リストの Top 10 を表示——完全な Top 100 は CSV を参照してください。

<details open>
<summary><b>🏆 Best 100（導入価値スコア）</b></summary>

| # | Skill | ベンダー | WIS | カバレッジ |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 80.9 | C |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 79.4 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76.4 | C |
| 4 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | 71.1 | C |
| 5 | [azure-ai](https://www.skills.sh/microsoft/azure-skills/azure-ai) | [microsoft](https://www.skills.sh/microsoft) | 68.6 | C |
| 6 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 68 | C |
| 7 | [azure-storage](https://www.skills.sh/microsoft/azure-skills/azure-storage) | [microsoft](https://www.skills.sh/microsoft) | 67.9 | C |
| 8 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 67.9 | C |
| 9 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 66.5 | C |
| 10 | [microsoft-foundry](https://www.skills.sh/microsoft/azure-skills/microsoft-foundry) | [microsoft](https://www.skills.sh/microsoft) | 65.5 | C |

➡️ 完全版：[best-100.csv](data/2026-08-27/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 インストール数上位（全エコシステム）</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub 中国 |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,132,637 | — | — |
| 2 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 476,371 | 1,141,042 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 982,738 | — | — |
| 4 | find-skills | — | — | 816,352 |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 837,456 | — | — |
| 6 | agent-browser | — | — | 645,566 |
| 7 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 824,789 | — | — |
| 8 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 806,348 | — | — |
| 9 | summarize | — | — | 592,958 |
| 10 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | — | 207,964 | 387,598 |

➡️ 完全版：[top-installs.csv](data/2026-08-27/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 トレンド（7 日間）</b></summary>

| # | Skill | インストール数 | 週間 Δ% |
| --- | --- | --- | --- |
| 1 | [ai-video-generation](https://www.skills.sh/skills-101/superpowers/ai-video-generation) | 391,669 | -5.3 |
| 2 | [ai-image-generation](https://www.skills.sh/skills-101/superpowers/ai-image-generation) | 391,322 | -5.3 |
| 3 | [ai-avatar-video](https://www.skills.sh/skills-101/superpowers/ai-avatar-video) | 391,235 | -5.2 |
| 4 | [twitter-automation](https://www.skills.sh/skills-101/superpowers/twitter-automation) | 391,119 | -5.2 |
| 5 | [anti-ui-slop](https://www.skills.sh/uizze.com/anti-ui-slop) | 513,438 | 1.5 |
| 6 | [reddit-automation](https://www.skills.sh/flowkit-labs/skills/reddit-automation) | 160,230 | — |
| 7 | [video-edit](https://www.skills.sh/genmedia-labs/skills/video-edit) | 192,738 | — |
| 8 | [ai-music](https://www.skills.sh/genmedia-labs/skills/ai-music) | 192,290 | — |
| 9 | [ai-image-generation](https://www.skills.sh/genmedia-labs/skills/ai-image-generation) | 192,724 | — |
| 10 | [ai-video-generation](https://www.skills.sh/genmedia-labs/skills/ai-video-generation) | 193,006 | — |

➡️ 完全版：[trending-7d.csv](data/2026-08-27/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 ソーシャルでの話題性（X · HN · Bluesky · GitHub、7 日間）</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 100+ | 1 | 8 | 21 |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 71 | 2 | 6 | 64 |
| 3 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 100+ | 1 | 34 | 3 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 100+ | 0 | 8 | 31 |
| 5 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 72 | 0 | 2 | 127 |
| 6 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 30 | 0 | 1 | 143 |
| 7 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 1 | 26 | 9 |
| 8 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | — | 1 | 34 | 2 |
| 9 | [word-docx](https://clawhub.ai/ivangdavila/skills/word-docx) | 3 | 0 | 1 | 2 |
| 10 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | 2 | 0 | 1 | 1 |

➡️ 完全版：[social-buzz.csv](data/2026-08-27/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 最も活発（人気があり更新頻度が高い）</b></summary>

| # | Skill | 更新日 | バージョン数 |
| --- | --- | --- | --- |
| 1 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-08-26 | 151 |
| 2 | [cellcog](https://clawhub.ai/nitishgargiitd/skills/cellcog) | 2026-08-24 | 49 |
| 3 | [stripe-api](https://clawhub.ai/byungkyu/skills/stripe-api) | 2026-08-26 | 14 |
| 4 | [linkedin-api](https://clawhub.ai/byungkyu/skills/linkedin-api) | 2026-08-26 | 12 |
| 5 | [gmail](https://clawhub.ai/byungkyu/skills/gmail) | 2026-08-26 | 11 |
| 6 | [google-sheets](https://clawhub.ai/byungkyu/skills/google-sheets) | 2026-08-26 | 11 |
| 7 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-08-26 | 11 |
| 8 | [google-analytics](https://clawhub.ai/byungkyu/skills/google-analytics) | 2026-08-26 | 11 |
| 9 | [image-generation-cellcog](https://clawhub.ai/nitishgargiitd/skills/image-generation-cellcog) | 2026-08-24 | 18 |
| 10 | creative-writing-cellcog | 2026-08-24 | 16 |

➡️ 完全版：[most-active.csv](data/2026-08-27/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100（認証済みパブリッシャー）</b></summary>

| # | Skill | ベンダー | 認証元 |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 3 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 4 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 5 | [github](https://clawhub.ai/steipete/skills/github) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 6 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 7 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |
| 8 | [gog](https://clawhub.ai/steipete/skills/gog) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 9 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 10 | [obsidian](https://clawhub.ai/steipete/skills/obsidian) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ 完全版：[official-100.csv](data/2026-08-27/rankings/official-100.csv)

</details>

<details>
<summary><b>🏢 公式ベンダー（プラットフォーム別）</b></summary>

| # | プラットフォーム | ベンダー | Skills 数 | インストール/ダウンロード数 |
| --- | --- | --- | --- | --- |
| 1 | [skills.sh](https://www.skills.sh) | [microsoft](https://www.skills.sh/microsoft) | 582 | 7,098,914 |
| 2 | [skills.sh](https://www.skills.sh) | [vercel-labs](https://www.skills.sh/vercel-labs) | 252 | 3,192,306 |
| 3 | [skills.sh](https://www.skills.sh) | [github](https://www.skills.sh/github) | 406 | 2,002,106 |
| 4 | [skills.sh](https://www.skills.sh) | [anthropics](https://www.skills.sh/anthropics) | 605 | 1,942,411 |
| 5 | [skills.sh](https://www.skills.sh) | [firebase](https://www.skills.sh/firebase) | 55 | 685,617 |
| 6 | [skills.sh](https://www.skills.sh) | [firecrawl](https://www.skills.sh/firecrawl) | 286 | 482,310 |
| 7 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 8 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 9 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |
| 10 | [skills.sh](https://www.skills.sh) | [google-labs-code](https://www.skills.sh/google-labs-code) | 30 | 260,911 |

➡️ 完全版：[official-vendors.csv](data/2026-08-27/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ 上位リポジトリ</b></summary>

| # | リポジトリ | Stars | 最終プッシュ |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 278,372 | 2026-08-19 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 238,509 | 2026-08-24 |
| 3 | [microsoft/vscode](https://github.com/microsoft/vscode) | 189,710 | 2026-08-27 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | 171,969 | 2026-08-21 |
| 5 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 143,151 | 2026-08-26 |
| 6 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 122,252 | 2026-08-26 |
| 7 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 121,625 | 2026-08-27 |
| 8 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 113,365 | 2026-08-07 |
| 9 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 111,369 | 2026-08-26 |
| 10 | [fastapi/fastapi](https://github.com/fastapi/fastapi) | 101,873 | 2026-08-26 |

➡️ 完全版：[top-repos.csv](data/2026-08-27/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 注目の新星（公開から 30 日未満）</b></summary>

| # | Skill | 経過日数 | 人気度 |
| --- | --- | --- | --- |
| 1 | paperless-business-system-from-files | 27 | 0.981 |
| 2 | anti-fraud | 10 | 0.98 |
| 3 | multi-search-engine | 8 | 0.975 |
| 4 | beatra | 11 | 0.957 |
| 5 | sbkj-ztb | 11 | 0.889 |
| 6 | sbkj | 11 | 0.873 |
| 7 | national-bid-company-profile | 10 | 0.867 |
| 8 | national-bid-ai-analyzer | 10 | 0.866 |
| 9 | bid-data-radar-ai-query | 10 | 0.865 |
| 10 | bid-quick-search-engine | 10 | 0.864 |

➡️ 完全版：[rising-stars.csv](data/2026-08-27/rankings/rising-stars.csv)

</details>

<!-- RANKINGS:END -->

### 各リストの意味

| リスト | ランキング対象 |
| --- | --- |
| `best-100` | 総合的な導入価値スコア（人気度 + 勢い + 話題性 + メンテナンス + 信頼性） |
| `top-installs` | 全エコシステムを統合したインストール数上位 |
| `trending-7d` | 過去 7 日間で最も成長した Skills |
| `social-buzz` | X、Hacker News、Bluesky、GitHub で最も話題になった Skills（言及を特定できない一般名称の Skills は除外） |
| `most-active` | 人気の Skills のうち最も頻繁に更新されているもの |
| `official-100` | 認証済みパブリッシャーが公開する人気 Skills |
| `official-vendors` | 総インストール数による認証済みベンダーの順位 |
| `top-repos` | Skills の GitHub リポジトリを Stars 数で順位付け |
| `rising-stars` | 初めて確認されてから 30 日未満の優れた新規 Skills |

## データ

```text
data/
├── YYYY-MM-DD/
│   ├── raw/                # プラットフォームごとの元データ（未加工）
│   │   ├── skills-sh.csv · clawhub.csv · skillhub.csv · github-repos.csv
│   │   └── buzz.csv · x-posts.csv · …
│   └── rankings/           # raw/ から算出した 9 種類のランキング
│       ├── best-100.csv · top-installs.csv · trending-7d.csv
│       └── social-buzz.csv · … · rising-stars.csv
├── latest/                 # 常に最新日のコピー
└── index/
    └── first-seen.csv      # 初回確認日の累積データ（注目の新星に使用）
```

1 日につき 1 フォルダーで、内容は CSV のみです。複合スコアには、その算出元となったプラットフォーム別の元データが必ず併記されています。今日のリストだけを見たい場合は `data/latest/` から始めてください。

データソース、正規化ルール、既知の制約については [docs/methodology.md](docs/methodology.md) を参照してください。

## データソースと帰属表示

インストール/ダウンロード数は、[skills.sh](https://www.skills.sh)、[ClawHub](https://clawhub.ai)（同サービスのサードパーティディレクトリポリシーに準拠し、Skill ページから正規の ClawHub 掲載ページへリンク）、[Tencent SkillHub](https://skillhub.cn)、[GitHub API](https://docs.github.com) の公開エンドポイントから収集しています。ソーシャルシグナルは X、[Hacker News (Algolia)](https://hn.algolia.com)、[Bluesky](https://bsky.app)、GitHub 検索から取得しています。本プロジェクトはこれらのプラットフォームから承認を受けたものではなく、提携関係もありません。数値は各プラットフォーム独自の集計方法に基づき、プラットフォームをまたいで合算することはありません。

## ライセンス

データとドキュメントは [CC BY 4.0](LICENSE) で公開されており、帰属表示をすれば自由に利用できます。データを利用する際は、このリポジトリへのリンクを掲載し、各プラットフォームへの帰属表示を維持してください。

---

[Linkly AI](https://linkly.ai) が運営——Agent Skills に対応した AI ローカルナレッジベース。
