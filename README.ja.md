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

> 最終更新：**2026-08-26**（UTC）· 各リストの Top 10 を表示——完全な Top 100 は CSV を参照してください。

<details open>
<summary><b>🏆 Best 100（導入価値スコア）</b></summary>

| # | Skill | ベンダー | WIS | カバレッジ |
| --- | --- | --- | --- | --- |
| 1 | frontend-design | anthropics | 79.3 | C |
| 2 | agent-browser | vercel-labs | 77.1 | C |
| 3 | find-skills | vercel-labs | 76.5 | C |
| 4 | vercel-react-best-practices | vercel-labs | 70.7 | C |
| 5 | azure-ai | microsoft | 68.4 | C |
| 6 | skill-creator | anthropics | 68.2 | C |
| 7 | grill-me | mattpocock | 68 | C |
| 8 | azure-storage | microsoft | 67.8 | C |
| 9 | web-design-guidelines | vercel-labs | 66.6 | C |
| 10 | microsoft-foundry | microsoft | 65.1 | C |

➡️ 完全版：[best-100.csv](data/2026-08-26/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 インストール数上位（全エコシステム）</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub 中国 |
| --- | --- | --- | --- | --- |
| 1 | find-skills | 3,110,349 | — | — |
| 2 | self-improving-agent | — | 476,145 | 1,135,666 |
| 3 | grill-me | 967,722 | — | — |
| 4 | find-skills | — | — | 797,391 |
| 5 | grill-with-docs | 824,665 | — | — |
| 6 | agent-browser | — | — | 630,874 |
| 7 | frontend-design | 818,889 | — | — |
| 8 | improve-codebase-architecture | 794,554 | — | — |
| 9 | summarize | — | — | 590,811 |
| 10 | self-improving | — | 207,860 | 386,305 |

➡️ 完全版：[top-installs.csv](data/2026-08-26/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 トレンド（7 日間）</b></summary>

| # | Skill | インストール数 | 週間 Δ% |
| --- | --- | --- | --- |
| 1 | ai-video-generation | 366,871 | -5.3 |
| 2 | ai-avatar-video | 366,488 | -5.2 |
| 3 | ai-image-generation | 366,570 | -5.3 |
| 4 | twitter-automation | 366,375 | -5.2 |
| 5 | anti-ui-slop | 489,413 | 1.5 |
| 6 | reddit-automation | 137,815 | — |
| 7 | ai-image-generation | 170,403 | — |
| 8 | ai-music | 169,982 | — |
| 9 | video-edit | 170,336 | — |
| 10 | ai-video-generation | 170,631 | — |

➡️ 完全版：[trending-7d.csv](data/2026-08-26/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 ソーシャルでの話題性（X · HN · Bluesky · GitHub、7 日間）</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | self-improving | 100+ | 2 | 27 | 5 |
| 2 | frontend-design | 68 | 1 | 6 | 54 |
| 3 | grill-me | 100+ | 0 | 8 | 30 |
| 4 | agent-browser | 100+ | 0 | 7 | 18 |
| 5 | skill-creator | 73 | 0 | 3 | 123 |
| 6 | find-skills | 26 | 0 | 1 | 144 |
| 7 | api-gateway | — | 1 | 32 | 1 |
| 8 | self-improving-agent | 59 | 0 | 3 | 1 |
| 9 | grill-with-docs | 24 | 0 | 0 | 7 |
| 10 | vercel-react-best-practices | 2 | 0 | 1 | 1 |

➡️ 完全版：[social-buzz.csv](data/2026-08-26/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 最も活発（人気があり更新頻度が高い）</b></summary>

| # | Skill | 更新日 | バージョン数 |
| --- | --- | --- | --- |
| 1 | api-gateway | 2026-08-26 | 151 |
| 2 | cellcog | 2026-08-24 | 49 |
| 3 | image-generation-cellcog | 2026-08-24 | 18 |
| 4 | creative-writing-cellcog | 2026-08-24 | 16 |
| 5 | scrapling-official | 2026-08-23 | 15 |
| 6 | getnote | 2026-08-19 | 45 |
| 7 | planning-with-files | 2026-08-19 | 17 |
| 8 | neural-memory | 2026-08-16 | 56 |
| 9 | self-improving-agent | 2026-08-06 | 39 |
| 10 | polymarket-weather-trader | 2026-07-22 | 48 |

➡️ 完全版：[most-active.csv](data/2026-08-26/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100（認証済みパブリッシャー）</b></summary>

| # | Skill | ベンダー | 認証元 |
| --- | --- | --- | --- |
| 1 | find-skills | vercel-labs | skills.sh |
| 2 | frontend-design | anthropics | skills.sh |
| 3 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 4 | agent-browser | vercel-labs | skills.sh |
| 5 | github | steipete | clawhub |
| 6 | vercel-react-best-practices | vercel-labs | skills.sh |
| 7 | weather | steipete | clawhub |
| 8 | gog | steipete | clawhub |
| 9 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |
| 10 | obsidian | steipete | clawhub |

➡️ 完全版：[official-100.csv](data/2026-08-26/rankings/official-100.csv)

</details>

<details>
<summary><b>🏢 公式ベンダー（プラットフォーム別）</b></summary>

| # | プラットフォーム | ベンダー | Skills 数 | インストール/ダウンロード数 |
| --- | --- | --- | --- | --- |
| 1 | skills.sh | microsoft | 582 | 7,098,914 |
| 2 | skills.sh | vercel-labs | 252 | 3,192,306 |
| 3 | skills.sh | github | 406 | 2,002,106 |
| 4 | skills.sh | anthropics | 605 | 1,942,411 |
| 5 | skills.sh | firebase | 55 | 685,617 |
| 6 | skills.sh | firecrawl | 286 | 482,310 |
| 7 | skills.sh | remotion-dev | 19 | 305,359 |
| 8 | skills.sh | flutter | 88 | 286,211 |
| 9 | skills.sh | expo | 18 | 283,306 |
| 10 | skills.sh | google-labs-code | 30 | 260,911 |

➡️ 完全版：[official-vendors.csv](data/2026-08-26/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ 上位リポジトリ</b></summary>

| # | リポジトリ | Stars | 最終プッシュ |
| --- | --- | --- | --- |
| 1 | obra/superpowers | 277,608 | 2026-08-19 |
| 2 | mattpocock/skills | 236,829 | 2026-08-24 |
| 3 | anthropics/skills | 171,601 | 2026-08-21 |
| 4 | anthropics/claude-code | 143,017 | 2026-08-25 |
| 5 | shadcn-ui/ui | 122,128 | 2026-08-25 |
| 6 | nextlevelbuilder/ui-ux-pro-max-skill | 120,956 | 2026-08-25 |
| 7 | DietrichGebert/ponytail | 111,174 | 2026-08-07 |
| 8 | browser-use/browser-use | 110,525 | 2026-08-26 |
| 9 | pytorch/pytorch | 102,601 | 2026-08-26 |
| 10 | JuliusBrussee/caveman | 100,960 | 2026-08-24 |

➡️ 完全版：[top-repos.csv](data/2026-08-26/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 注目の新星（公開から 30 日未満）</b></summary>

| # | Skill | 経過日数 | 人気度 |
| --- | --- | --- | --- |
| 1 | anti-fraud | 9 | 0.98 |
| 2 | paperless-business-system-from-files | 26 | 0.975 |
| 3 | multi-search-engine | 7 | 0.973 |
| 4 | sbkj-ztb | 10 | 0.892 |
| 5 | sbkj | 10 | 0.877 |
| 6 | beatra | 10 | 0.868 |
| 7 | sbkj-official-en | 10 | 0.866 |
| 8 | sbkj-official-sales | 9 | 0.857 |
| 9 | ai-audiobook-narration | 6 | 0.837 |
| 10 | ai-video-generation | 10 | 0.819 |

➡️ 完全版：[rising-stars.csv](data/2026-08-26/rankings/rising-stars.csv)

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
