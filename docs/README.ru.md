<div align="center">

# 🏆 Best Agent Skills

**Ежедневно обновляемые рейтинги Top 100 Agent Skills — установки, рост и обсуждаемость, собранные из skills.sh, ClawHub, Tencent SkillHub, GitHub, X и других источников. Открытые данные (CSV).**

[![Данные обновлены](https://img.shields.io/github/last-commit/LinklyAI/best-skills?label=data%20updated&color=brightgreen)](../data/latest)
[![Обновление](https://img.shields.io/badge/refresh-daily-blue)](#рейтинги)
[![Рейтинги](https://img.shields.io/badge/rankings-9-orange)](#рейтинги)
[![Skills в выборке](https://img.shields.io/badge/skills%20tracked-10%2C000%2B-blueviolet)](../data/latest)
[![Лицензия: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](../LICENSE)
[![Stars](https://img.shields.io/github/stars/LinklyAI/best-skills?color=yellow)](https://github.com/LinklyAI/best-skills)
[![Подписаться на @BlueeonY в X](https://img.shields.io/badge/X-%40BlueeonY-000000?logo=x&logoColor=white)](https://x.com/BlueeonY)

[English](../README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Русский](README.ru.md)

Рейтинги меняются каждый день — поставьте ⭐ **Star**, чтобы следить за обновлениями, или подпишитесь на [**@BlueeonY**](https://x.com/BlueeonY) в X.

</div>

<p align="center">
  <a href="https://linkly.ai/skills">
    <img src="assets/best-skills-rankings.webp" alt="Best Agent Skills Rankings web preview">
  </a>
  <br>
  <a href="https://linkly.ai/skills">Открыть интерактивные рейтинги →</a>
</p>

## Зачем нужен этот проект

Каждый каталог skills видит только собственную экосистему. skills.sh считает установки через Claude/Vercel CLI, ClawHub — загрузки OpenClaw, Tencent SkillHub — установки в Китае, но ни один из них не отражает обсуждаемость в сообществе. **Best Skills объединяет эти источники в единую межплатформенную картину**: для каждого skill рядом показаны глобальные установки, установки в Китае и упоминания в социальных сетях. Другого рейтинга с таким охватом нет.

- **9 рейтингов**, обновляются ежедневно
- **Исходные значения сохраняются** — каждый CSV содержит оригинальные показатели по платформам, поэтому данные можно проверить или пересчитать
- **Несопоставимые показатели не складываются** — данные разных платформ показаны рядом, а итоговый рейтинг строится по составному перцентильному баллу внутри каждой платформы (см. [методологию](methodology.md))
- **Оценивает [jev](https://openrouter.ai/typesafe/jev-1.13), а не подсчёт ключевых слов** — модель принятия решений TypeSafe проверяет, действительно ли пост в соцсетях посвящён навыку, является ли запись настоящим поддерживаемым навыком и к какой категории он относится; заглушки, устаревшие и вредоносные записи не попадают в рейтинги, а все вероятности публикуются (см. [методологию](methodology.md#judgements-jev))

## Рейтинги

<!-- RANKINGS:START -->

> Последнее обновление: **2026-09-27** (UTC) · Предпросмотр Top 10 для каждого рейтинга — полный Top 100 доступен в CSV.

<details open>
<summary><b>🏆 Лучшие 100 (рейтинг целесообразности установки)</b></summary>

| # | Skill | Издатель | WIS | Охват |
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

➡️ Полный список: [best-100.csv](../data/2026-09-27/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Лидеры по установкам (все экосистемы)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub Китай |
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

➡️ Полный список: [top-installs.csv](../data/2026-09-27/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 В тренде (7 дней)</b></summary>

| # | Skill | Установки | Недельный Δ% |
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

➡️ Полный список: [trending-7d.csv](../data/2026-09-27/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Обсуждаемость (X · HN · Bluesky · GitHub, 7 дней)</b></summary>

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

➡️ Полный список: [social-buzz.csv](../data/2026-09-27/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Самые активные (популярные и регулярно обновляемые)</b></summary>

| # | Skill | Обновлено | Версии |
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

➡️ Полный список: [most-active.csv](../data/2026-09-27/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Официальные 100 (проверенные издатели)</b></summary>

| # | Skill | Издатель | Проверено |
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

➡️ Полный список: [official-100.csv](../data/2026-09-27/rankings/official-100.csv)

</details>

<details>
<summary><b>🏢 Официальные издатели (по платформам)</b></summary>

| # | Платформа | Издатель | Skills | Установки/скачивания |
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

➡️ Полный список: [official-vendors.csv](../data/2026-09-27/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Лучшие репозитории</b></summary>

| # | Репозиторий | Stars | Последний push |
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

➡️ Полный список: [top-repos.csv](../data/2026-09-27/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Восходящие звёзды (младше 30 дней)</b></summary>

| # | Skill | Возраст (дни) | Популярность |
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

➡️ Полный список: [rising-stars.csv](../data/2026-09-27/rankings/rising-stars.csv)

</details>

<!-- RANKINGS:END -->

### Что означает каждый список

| Список             | Что он ранжирует                                                                                                              |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| `best-100`         | Общий Worth-Installing Score: популярность, динамика, обсуждаемость, поддержка и доверие к издателю                            |
| `top-installs`     | Самые устанавливаемые skills во всех экосистемах                                                                              |
| `trending-7d`      | Skills с самым быстрым ростом за последние 7 дней                                                                             |
| `social-buzz`      | Самые обсуждаемые skills в X, Hacker News, Bluesky и GitHub; skills с общими названиями исключены из-за неточной атрибуции     |
| `most-active`      | Популярные skills, которые обновляются чаще всего                                                                              |
| `official-100`     | Самые популярные skills от проверенных издателей                                                                               |
| `official-vendors` | Проверенные издатели по суммарным установкам                                                                                   |
| `top-repos`        | GitHub-репозитории, стоящие за skills, по количеству stars                                                                     |
| `rising-stars`     | Лучшие новые skills, впервые замеченные менее 30 дней назад                                                                    |

## Данные

```text
data/
├── YYYY-MM-DD/
│   ├── raw/                # исходные показатели по платформам без изменений
│   │   ├── skills-sh.csv · clawhub.csv · skillhub.csv · github-repos.csv
│   │   └── buzz.csv · x-posts.csv · judgments.csv · …
│   └── rankings/           # 9 рейтингов, рассчитанных из raw/
│       ├── best-100.csv · top-installs.csv · trending-7d.csv
│       └── social-buzz.csv · … · rising-stars.csv
├── latest/                 # копия данных за последний доступный день
└── index/
    └── first-seen.csv      # накопленные даты первого появления для rising-stars
```

На каждый день создаётся отдельная папка только с CSV. Составные оценки всегда публикуются вместе с исходными показателями по платформам, из которых они рассчитаны. Если нужны сегодняшние списки, начните с `data/latest/`.

Источники данных, правила нормализации и известные ограничения описаны в [методологии](methodology.md).

## Источники и атрибуция

Количество установок и загрузок собирается из открытых API [skills.sh](https://www.skills.sh), [ClawHub](https://clawhub.ai) (в соответствии с политикой сторонних каталогов; страницы skills содержат ссылки на оригинальные страницы ClawHub), [Tencent SkillHub](https://skillhub.cn) и [GitHub API](https://docs.github.com). Социальные сигналы поступают из X, [Hacker News (Algolia)](https://hn.algolia.com), [Bluesky](https://bsky.app) и поиска GitHub. Проект не связан с этими платформами и не поддерживается ими. Показатели следуют методологии каждой платформы и никогда не складываются между платформами.

## Лицензия

Данные и документация опубликованы по лицензии [CC BY 4.0](../LICENSE): их можно свободно использовать, распространять и применять в коммерческих проектах.

### Как указать источник

Добавьте эту строку там, где используются данные:

> Data from [Best Skills](https://github.com/LinklyAI/best-skills) by [@BlueeonY](https://x.com/BlueeonY) — [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Сохраните ссылку на этот репозиторий и атрибуцию платформ, перечисленных выше. Это всё, что требуется; отдельное разрешение не нужно.

Создали что-то на основе этих данных? [@BlueeonY](https://x.com/BlueeonY) будет рад увидеть результат — это не требование лицензии, а просто пожелание.

---

Проект создан [@BlueeonY](https://x.com/BlueeonY) в [Linkly AI](https://linkly.ai) — локальной базе знаний с AI и поддержкой agent skills.

Проект оказался полезен? ⭐ поможет большему числу людей его найти.
