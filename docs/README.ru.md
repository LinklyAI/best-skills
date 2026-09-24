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

> Последнее обновление: **2026-09-24** (UTC) · Предпросмотр Top 10 для каждого рейтинга — полный Top 100 доступен в CSV.

<details open>
<summary><b>🏆 Лучшие 100 (рейтинг целесообразности установки)</b></summary>

| # | Skill | Издатель | WIS | Охват |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 81.3 | C |
| 2 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 78.5 | C |
| 3 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 75.9 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 71.1 | C |
| 5 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 67 | B |
| 6 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 66.3 | C |
| 7 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | [anthropics](https://www.skills.sh/anthropics) | 66.3 | C |
| 8 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | 65.2 | B |
| 9 | [gog](https://clawhub.ai/steipete/skills/gog) | [steipete](https://clawhub.ai/steipete) | 64.9 | B |
| 10 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | [mattpocock](https://www.skills.sh/mattpocock) | 64.1 | C |

➡️ Полный список: [best-100.csv](../data/2026-09-24/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Лидеры по установкам (все экосистемы)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub Китай |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,539,141 | — | — |
| 2 | dev-expert | — | — | 1,318,818 |
| 3 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 480,936 | 1,236,358 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,210,780 | — | — |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,034,479 | — | — |
| 6 | tencent-docs | — | — | 1,171,901 |
| 7 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 983,389 | — | — |
| 8 | [tdd](https://www.skills.sh/mattpocock/skills/tdd) | 955,467 | — | — |
| 9 | find-skills | — | — | 1,025,641 |
| 10 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 919,805 | — | — |

➡️ Полный список: [top-installs.csv](../data/2026-09-24/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 В тренде (7 дней)</b></summary>

| # | Skill | Установки | Недельный Δ% |
| --- | --- | --- | --- |
| 1 | [ai-image-generation](https://www.skills.sh/101-skills/superpowers/ai-image-generation) | 405,232 | 233.8 |
| 2 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 405,595 | 231.4 |
| 3 | [ai-avatar-video](https://www.skills.sh/101-skills/superpowers/ai-avatar-video) | 404,986 | 236.4 |
| 4 | [twitter-automation](https://www.skills.sh/101-skills/superpowers/twitter-automation) | 405,290 | 235.1 |
| 5 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 51,074 | — |
| 6 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 397,609 | -1.2 |
| 7 | [ai-video-generation](https://www.skills.sh/qu-skills/superpowers/ai-video-generation) | 196,984 | 234.3 |
| 8 | [ai-avatar-video](https://www.skills.sh/qu-skills/superpowers/ai-avatar-video) | 197,521 | 228.9 |
| 9 | [ai-image-generation](https://www.skills.sh/qu-skills/superpowers/ai-image-generation) | 196,960 | 234.8 |
| 10 | [twitter-automation](https://www.skills.sh/qu-skills/superpowers/twitter-automation) | 197,151 | 231.5 |

➡️ Полный список: [trending-7d.csv](../data/2026-09-24/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Обсуждаемость (X · HN · Bluesky · GitHub, 7 дней)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 76 | 5 | 5 | 29 |
| 2 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 71+ | 4 | 13 | 24 |
| 3 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 66+ | 1 | 28 | 10 |
| 4 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 39 | 3 | 3 | 49 |
| 5 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 14 | 1 | 5 | 1 |
| 6 | [skill-creator](https://www.skills.sh/anthropics/skills/skill-creator) | 56 | 0 | 1 | 105 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 8 | 0 | 1 | 141 |
| 8 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 42 | 0 | 1 | 3 |
| 9 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 2 | 27 | 4 |
| 10 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 12 | 0 | 2 | 3 |

➡️ Полный список: [social-buzz.csv](../data/2026-09-24/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Самые активные (популярные и регулярно обновляемые)</b></summary>

| # | Skill | Обновлено | Версии |
| --- | --- | --- | --- |
| 1 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-09-23 | 175 |
| 2 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-09-23 | 129 |
| 3 | [google-drive](https://clawhub.ai/byungkyu/skills/google-drive) | 2026-09-24 | 21 |
| 4 | [linear-api](https://clawhub.ai/byungkyu/skills/linear-api) | 2026-09-24 | 19 |
| 5 | google-workspace-admin | 2026-09-24 | 18 |
| 6 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-09-23 | 25 |
| 7 | [linkedin-api](https://clawhub.ai/byungkyu/skills/linkedin-api) | 2026-09-24 | 17 |
| 8 | [google-sheets](https://clawhub.ai/byungkyu/skills/google-sheets) | 2026-09-24 | 15 |
| 9 | [klaviyo](https://clawhub.ai/byungkyu/skills/klaviyo) | 2026-09-24 | 14 |
| 10 | [gmail](https://clawhub.ai/byungkyu/skills/gmail) | 2026-09-23 | 15 |

➡️ Полный список: [most-active.csv](../data/2026-09-24/rankings/most-active.csv)

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
| 9 | ima-skills | 腾讯科技（深圳）有限公司 | skillhub |
| 10 | [weather](https://clawhub.ai/steipete/skills/weather) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ Полный список: [official-100.csv](../data/2026-09-24/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1055 | 427,452 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Полный список: [official-vendors.csv](../data/2026-09-24/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Лучшие репозитории</b></summary>

| # | Репозиторий | Stars | Последний push |
| --- | --- | --- | --- |
| 1 | [obra/superpowers](https://github.com/obra/superpowers) | 290,678 | 2026-09-22 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 268,489 | 2026-09-18 |
| 3 | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 248,404 | 2026-09-24 |
| 4 | [anthropics/skills](https://github.com/anthropics/skills) | 177,828 | 2026-09-22 |
| 5 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 147,808 | 2026-09-23 |
| 6 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 145,016 | 2026-09-14 |
| 7 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 130,144 | 2026-09-21 |
| 8 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 124,488 | 2026-09-21 |
| 9 | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | 120,921 | 2026-09-23 |
| 10 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 116,087 | 2026-09-24 |

➡️ Полный список: [top-repos.csv](../data/2026-09-24/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Восходящие звёзды (младше 30 дней)</b></summary>

| # | Skill | Возраст (дни) | Популярность |
| --- | --- | --- | --- |
| 1 | parenting-expert | 8 | 0.994 |
| 2 | mysteel-datasearch | 23 | 0.984 |
| 3 | luhe-paper-free-pro | 8 | 0.981 |
| 4 | tencent-meeting-mcp | 20 | 0.966 |
| 5 | talking-avatar-video | 22 | 0.965 |
| 6 | gongwen-writting-2 | 3 | 0.943 |
| 7 | poster-design-studio | 14 | 0.942 |
| 8 | ai-podcast-voiceover | 22 | 0.936 |
| 9 | gh-cli-readonly-agent | 11 | 0.932 |
| 10 | suno-lyrics-to-song | 13 | 0.928 |

➡️ Полный список: [rising-stars.csv](../data/2026-09-24/rankings/rising-stars.csv)

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
