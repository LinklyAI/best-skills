<div align="center">

# 🏆 Best Agent Skills

**毎日更新される Agent Skills Top 100 ランキング——skills.sh、ClawHub、Tencent SkillHub、GitHub、X などからインストール数、成長率、ソーシャルでの話題性を集約。オープンデータ（CSV）。**

[![データ更新](https://img.shields.io/github/last-commit/LinklyAI/best-skills?label=data%20updated&color=brightgreen)](../data/latest)
[![更新頻度](https://img.shields.io/badge/refresh-daily-blue)](#ランキング)
[![ランキング](https://img.shields.io/badge/rankings-9-orange)](#ランキング)
[![追跡中の Skills](https://img.shields.io/badge/skills%20tracked-10%2C000%2B-blueviolet)](../data/latest)
[![ライセンス：CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](../LICENSE)
[![Star 数](https://img.shields.io/github/stars/LinklyAI/best-skills?color=yellow)](https://github.com/LinklyAI/best-skills)
[![X で @BlueeonY をフォロー](https://img.shields.io/badge/X-%40BlueeonY-000000?logo=x&logoColor=white)](https://x.com/BlueeonY)

[English](../README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Русский](README.ru.md)

ランキングは毎日更新。⭐ **Star** で更新を受け取り、X の [**@BlueeonY**](https://x.com/BlueeonY) が日々の変動を発信。

</div>

<p align="center">
  <a href="https://linkly.ai/skills">
    <img src="assets/best-skills-rankings.webp" alt="Best Agent Skills Rankings web preview">
  </a>
  <br>
  <a href="https://linkly.ai/skills">ライブのインタラクティブランキングを見る →</a>
</p>

## このプロジェクトの目的

各 Skills レジストリが把握できるのは、それぞれのエコシステムだけです。skills.sh は Claude/Vercel CLI のインストール数、ClawHub は OpenClaw のダウンロード数、Tencent SkillHub は中国でのインストール数を集計していますが、いずれもソーシャルでの話題性は捉えていません。**Best Skills はこれらの視点を統合し、エコシステム横断の全体像を提供します**。Skill ごとに、世界のインストール数、中国でのインストール数、ソーシャルでの言及数を並べて確認できます。このようなランキングはほかにありません。

- **9 種類のランキング**を毎日更新
- **元の数値を保持**——各 CSV にはプラットフォームごとの元データが残り、誰でも検証や再ランキングが可能
- **比較できない数値は合算しない**——プラットフォーム横断の数値は並べて表示し、各プラットフォーム内のパーセンタイル複合値で順位付け（[方法論](methodology.md)を参照）
- **キーワード件数ではなく [jev](https://openrouter.ai/typesafe/jev-1.13) が判定**——TypeSafe の判定モデルが、各 SNS 投稿が本当にそのスキルについてのものか、掲載が実際に使える保守中のスキルか、どのカテゴリに属するかを判定。プレースホルダー・非推奨・有害な掲載はランキングから除外し、判定確率はすべて公開（[方法論](methodology.md#judgements-jev)を参照）

## ランキング

<!-- RANKINGS:START -->

> 最終更新：**2026-10-05**（UTC）· 各リストの Top 10 を表示——完全な Top 100 は CSV を参照してください。

<details open>
<summary><b>🏆 Best 100（導入価値スコア）</b></summary>

| # | Skill | ベンダー | WIS | カバレッジ |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 80.8 | C |
| 2 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76 | C |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 71.9 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.1 | C |
| 5 | [vercel-react-best-practices](https://www.skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | [vercel-labs](https://www.skills.sh/vercel-labs) | 67.5 | C |
| 6 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 66.5 | C |
| 7 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 65.8 | C |
| 8 | [code-review](https://www.skills.sh/mattpocock/skills/code-review) | [mattpocock](https://www.skills.sh/mattpocock) | 65.4 | C |
| 9 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 65 | C |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 65 | B |

➡️ 完全版：[best-100.csv](../data/2026-10-05/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 インストール数上位（全エコシステム）</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub 中国 |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,701,160 | — | — |
| 2 | dev-expert | — | — | 2,409,862 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,284,025 | — | — |
| 4 | parenting-expert | — | — | 1,812,658 |
| 5 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 482,621 | 1,314,954 |
| 6 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,097,878 | — | — |
| 7 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 1,045,075 | — | — |
| 8 | tencent-docs | — | — | 1,438,984 |
| 9 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,028,776 | — | — |
| 10 | [tdd](https://www.skills.sh/mattpocock/skills/tdd) | 1,017,059 | — | — |

➡️ 完全版：[top-installs.csv](../data/2026-10-05/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 トレンド（7 日間）</b></summary>

| # | Skill | インストール数 | 週間 Δ% |
| --- | --- | --- | --- |
| 1 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 397,232 | — |
| 2 | [ai-image-generation](https://www.skills.sh/magentosh/superpowers/ai-image-generation) | 268,827 | 81.8 |
| 3 | [ai-avatar-video](https://www.skills.sh/magentosh/superpowers/ai-avatar-video) | 268,669 | 81.8 |
| 4 | [ai-video-generation](https://www.skills.sh/magentosh/superpowers/ai-video-generation) | 268,701 | 81.8 |
| 5 | [twitter-automation](https://www.skills.sh/magentosh/superpowers/twitter-automation) | 268,560 | 81.7 |
| 6 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 615,498 | 1 |
| 7 | [reddit-automation](https://www.skills.sh/flowkit-labs/skills/reddit-automation) | 783,225 | 0.4 |
| 8 | [ios-design](https://www.skills.sh/uizze.sh/ios-design) | 209,565 | — |
| 9 | [media-use](https://www.skills.sh/heygen-com/hyperframes/media-use) | 673,407 | 30 |
| 10 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 662,196 | -45.6 |

➡️ 完全版：[trending-7d.csv](../data/2026-10-05/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 ソーシャルでの話題性（X · HN · Bluesky · GitHub、7 日間）</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 67+ | 1 | 4 | 37 |
| 2 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 67+ | 4 | 55 | 5 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 60 | 7 | 8 | 28 |
| 4 | [proactive-agent](https://clawhub.ai/halthelobster/skills/proactive-agent) | 66 | 1 | 2 | 1 |
| 5 | [code-review](https://www.skills.sh/mattpocock/skills/code-review) | — | 51 | 121 | 264 |
| 6 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 33 | 0 | 6 | 143 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 16 | 0 | 1 | 200 |
| 8 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 29 | 0 | 9 | 8 |
| 9 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 2 | 16 | 7 |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 52 | 0 | 3 | 1 |

➡️ 完全版：[social-buzz.csv](../data/2026-10-05/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 最も活発（人気があり更新頻度が高い）</b></summary>

| # | Skill | 更新日 | バージョン数 |
| --- | --- | --- | --- |
| 1 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-10-04 | 139 |
| 2 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 2026-10-04 | 40 |
| 3 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-10-02 | 182 |
| 4 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-10-02 | 23 |
| 5 | [stripe-api](https://clawhub.ai/byungkyu/skills/stripe-api) | 2026-10-02 | 22 |
| 6 | [linear-api](https://clawhub.ai/byungkyu/skills/linear-api) | 2026-10-02 | 21 |
| 7 | google-workspace-admin | 2026-10-02 | 20 |
| 8 | [linkedin-api](https://clawhub.ai/byungkyu/skills/linkedin-api) | 2026-10-02 | 20 |
| 9 | [salesforce-api](https://clawhub.ai/byungkyu/skills/salesforce-api) | 2026-10-02 | 19 |
| 10 | notion-api-skill | 2026-10-02 | 19 |

➡️ 完全版：[most-active.csv](../data/2026-10-05/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Official 100（認証済みパブリッシャー）</b></summary>

| # | Skill | ベンダー | 認証元 |
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

➡️ 完全版：[official-100.csv](../data/2026-10-05/rankings/official-100.csv)

</details>

<details>
<summary><b>🏢 公式ベンダー（プラットフォーム別）</b></summary>

| # | プラットフォーム | ベンダー | Skills 数 | インストール/ダウンロード数 |
| --- | --- | --- | --- | --- |
| 1 | [skills.sh](https://www.skills.sh) | [microsoft](https://www.skills.sh/microsoft) | 582 | 7,098,914 |
| 2 | [skills.sh](https://www.skills.sh) | [vercel-labs](https://www.skills.sh/vercel-labs) | 252 | 3,192,303 |
| 3 | [skills.sh](https://www.skills.sh) | [github](https://www.skills.sh/github) | 406 | 2,002,122 |
| 4 | [skills.sh](https://www.skills.sh) | [anthropics](https://www.skills.sh/anthropics) | 605 | 1,942,412 |
| 5 | [skills.sh](https://www.skills.sh) | [firebase](https://www.skills.sh/firebase) | 55 | 685,617 |
| 6 | [skills.sh](https://www.skills.sh) | [firecrawl](https://www.skills.sh/firecrawl) | 286 | 482,310 |
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1159 | 436,347 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ 完全版：[official-vendors.csv](../data/2026-10-05/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ 上位リポジトリ</b></summary>

| # | リポジトリ | Stars | 最終プッシュ |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 295,293 | 2026-09-27 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 276,182 | 2026-10-04 |
| 3 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 216,866 | 2026-04-20 |
| 4 | [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | 188,612 | 2026-10-04 |
| 5 | [anthropics/skills](https://github.com/anthropics/skills) | 179,653 | 2026-10-03 |
| 6 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 154,872 | 2026-10-04 |
| 7 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 149,422 | 2026-10-03 |
| 8 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 133,041 | 2026-10-03 |
| 9 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 125,109 | 2026-10-02 |
| 10 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 117,142 | 2026-10-03 |

➡️ 完全版：[top-repos.csv](../data/2026-10-05/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 注目の新星（公開から 30 日未満）</b></summary>

| # | Skill | 経過日数 | 人気度 |
| --- | --- | --- | --- |
| 1 | parenting-expert | 19 | 0.998 |
| 2 | luhe-paper-free-pro | 19 | 0.976 |
| 3 | project-explanation | 5 | 0.972 |
| 4 | demo-material-generation | 5 | 0.97 |
| 5 | cic | 7 | 0.965 |
| 6 | rosemond-contract-compliance | 6 | 0.963 |
| 7 | from-ldeas-to-requirements-logic | 5 | 0.953 |
| 8 | public-opinion-monitoring | 5 | 0.952 |
| 9 | flowchart-generation | 5 | 0.951 |
| 10 | ai-writing | 5 | 0.95 |

➡️ 完全版：[rising-stars.csv](../data/2026-10-05/rankings/rising-stars.csv)

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
│   │   └── buzz.csv · x-posts.csv · judgments.csv · …
│   └── rankings/           # raw/ から算出した 9 種類のランキング
│       ├── best-100.csv · top-installs.csv · trending-7d.csv
│       └── social-buzz.csv · … · rising-stars.csv
├── latest/                 # 常に最新日のコピー
└── index/
    └── first-seen.csv      # 初回確認日の累積データ（注目の新星に使用）
```

1 日につき 1 フォルダーで、内容は CSV のみです。複合スコアには、その算出元となったプラットフォーム別の元データが必ず併記されています。今日のリストだけを見たい場合は `data/latest/` から始めてください。

データソース、正規化ルール、既知の制約については [docs/methodology.md](methodology.md) を参照してください。

## データソースと帰属表示

インストール/ダウンロード数は、[skills.sh](https://www.skills.sh)、[ClawHub](https://clawhub.ai)（同サービスのサードパーティディレクトリポリシーに準拠し、Skill ページから正規の ClawHub 掲載ページへリンク）、[Tencent SkillHub](https://skillhub.cn)、[GitHub API](https://docs.github.com) の公開エンドポイントから収集しています。ソーシャルシグナルは X、[Hacker News (Algolia)](https://hn.algolia.com)、[Bluesky](https://bsky.app)、GitHub 検索から取得しています。本プロジェクトはこれらのプラットフォームから承認を受けたものではなく、提携関係もありません。数値は各プラットフォーム独自の集計方法に基づき、プラットフォームをまたいで合算することはありません。

## ライセンス

データとドキュメントは [CC BY 4.0](../LICENSE) で公開しています。商用を含め、自由に利用・再配布・二次利用できます。

### 帰属表示の書き方

データを掲載する箇所に、次の一行を添えてください：

> Data from [Best Skills](https://github.com/LinklyAI/best-skills) by [@BlueeonY](https://x.com/BlueeonY) — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

このリポジトリへのリンクと、上記の各プラットフォームへの帰属表示は維持してください。要件はこれだけで、別途の許諾は不要です。

作ったものがあれば [@BlueeonY](https://x.com/BlueeonY) がぜひ見てみたいです。ライセンス上の義務ではありませんが、教えていただけると嬉しいです。

---

[@BlueeonY](https://x.com/BlueeonY) が [Linkly AI](https://linkly.ai) で開発・運営——Agent Skills に対応した AI ローカルナレッジベース。

お役に立てましたら、⭐ をいただけると多くの方に届きます。
