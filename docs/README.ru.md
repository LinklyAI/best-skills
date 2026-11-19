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

> Последнее обновление: **2026-11-19** (UTC) · Предпросмотр Top 10 для каждого рейтинга — полный Top 100 доступен в CSV.

<details open>
<summary><b>🏆 Лучшие 100 (рейтинг целесообразности установки)</b></summary>

| # | Skill | Издатель | WIS | Охват |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 81.9 | C |
| 2 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76 | C |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 75 | C |
| 4 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 67.3 | C |
| 5 | [microsoft-foundry](https://www.skills.sh/microsoft/azure-skills/microsoft-foundry) | [microsoft](https://www.skills.sh/microsoft) | 66.9 | C |
| 6 | [azure-ai](https://www.skills.sh/microsoft/azure-skills/azure-ai) | [microsoft](https://www.skills.sh/microsoft) | 66.8 | C |
| 7 | [azure-diagnostics](https://www.skills.sh/microsoft/azure-skills/azure-diagnostics) | [microsoft](https://www.skills.sh/microsoft) | 66.7 | C |
| 8 | [azure-prepare](https://www.skills.sh/microsoft/azure-skills/azure-prepare) | [microsoft](https://www.skills.sh/microsoft) | 66.7 | C |
| 9 | [azure-deploy](https://www.skills.sh/microsoft/azure-skills/azure-deploy) | [microsoft](https://www.skills.sh/microsoft) | 66.7 | C |
| 10 | [azure-validate](https://www.skills.sh/microsoft/azure-skills/azure-validate) | [microsoft](https://www.skills.sh/microsoft) | 66.7 | C |

➡️ Полный список: [best-100.csv](../data/2026-11-19/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Лидеры по установкам (все экосистемы)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub Китай |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,430,966 | — | — |
| 2 | dev-god | — | — | 12,100,566 |
| 3 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,624,378 | — | — |
| 4 | multi-search-engine | — | — | 11,140,436 |
| 5 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,593,043 | — | — |
| 6 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,588,356 | — | — |
| 7 | aigccerts | — | — | 6,780,272 |
| 8 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,574,152 | — | — |
| 9 | dev-expert-pro | — | — | 6,328,699 |
| 10 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,502,384 | — | — |

➡️ Полный список: [top-installs.csv](../data/2026-11-19/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 В тренде (7 дней)</b></summary>

| # | Skill | Установки | Недельный Δ% |
| --- | --- | --- | --- |
| 1 | [ai-video-generation](https://www.skills.sh/beltsh/superpowers/ai-video-generation) | 28,854 | — |
| 2 | [ai-image-generation](https://www.skills.sh/beltsh/superpowers/ai-image-generation) | 28,847 | — |
| 3 | [twitter-automation](https://www.skills.sh/beltsh/superpowers/twitter-automation) | 28,846 | — |
| 4 | [ai-avatar-video](https://www.skills.sh/beltsh/superpowers/ai-avatar-video) | 28,845 | — |
| 5 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 1,502,384 | -1.8 |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,593,043 | -0.3 |
| 7 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 4,430,966 | -0.3 |
| 8 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,588,356 | 1.7 |
| 9 | [website-builder](https://www.skills.sh/flowkit-labs/skills/website-builder) | 110,579 | — |
| 10 | [media-use](https://www.skills.sh/heygen-com/hyperframes/media-use) | 1,497,077 | -0.2 |

➡️ Полный список: [trending-7d.csv](../data/2026-11-19/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Обсуждаемость (X · HN · Bluesky · GitHub, 7 дней)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 71+ | 8 | 20 | 41 |
| 2 | self-improving | 44+ | 5 | 24 | 4 |
| 3 | [ai-video-generation](https://www.skills.sh/101-skills/superpowers/ai-video-generation) | 31 | 1 | 8 | 2 |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 70+ | 0 | 8 | 37 |
| 5 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 69+ | 0 | 1 | 107 |
| 6 | proactive-agent | 88+ | 0 | 8 | 2 |
| 7 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 7 | 36 | 15 |
| 8 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 31 | 0 | 15 | 33 |
| 9 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 15 | 0 | 2 | 243 |
| 10 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 37 | 0 | 3 | 2 |

➡️ Полный список: [social-buzz.csv](../data/2026-11-19/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Самые активные (популярные и регулярно обновляемые)</b></summary>

| # | Skill | Обновлено | Версии |
| --- | --- | --- | --- |
| 1 | ai-insurance-advisor | 2026-11-18 | 297 |
| 2 | insurance-advisor-china | 2026-11-18 | 286 |
| 3 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-11-18 | 175 |
| 4 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-11-17 | 53 |
| 5 | [free-ride](https://clawhub.ai/shaivpidadi/skills/free-ride) | 2026-11-18 | 10 |
| 6 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-11-10 | 30 |
| 7 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-11-07 | 191 |
| 8 | opentwitter-mcp | 2026-11-16 | 4 |
| 9 | scrapling-official | 2026-11-05 | 17 |
| 10 | cellcog | 2026-11-01 | 54 |

➡️ Полный список: [most-active.csv](../data/2026-11-19/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Официальные 100 (проверенные издатели)</b></summary>

| # | Skill | Издатель | Проверено |
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

➡️ Полный список: [official-100.csv](../data/2026-11-19/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1322 | 444,510 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Полный список: [official-vendors.csv](../data/2026-11-19/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Лучшие репозитории</b></summary>

| # | Репозиторий | Stars | Последний push |
| --- | --- | --- | --- |
| 1 | [morluto/rea](https://github.com/morluto/rea) | 468,288 | 2026-11-19 |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 327,463 | 2026-11-18 |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | 321,311 | 2026-11-03 |
| 4 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 306,508 | 2026-11-17 |
| 5 | [anthropics/skills](https://github.com/anthropics/skills) | 197,206 | 2026-11-16 |
| 6 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 194,027 | 2026-10-29 |
| 7 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 156,174 | 2026-11-18 |
| 8 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 151,348 | 2026-11-18 |
| 9 | [vercel/next.js](https://github.com/vercel/next.js) | 143,584 | 2026-11-19 |
| 10 | [garrytan/gstack](https://github.com/garrytan/gstack) | 142,024 | 2026-11-19 |

➡️ Полный список: [top-repos.csv](../data/2026-11-19/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Восходящие звёзды (младше 30 дней)</b></summary>

| # | Skill | Возраст (дни) | Популярность |
| --- | --- | --- | --- |
| 1 | patent-search-i | 25 | 0.879 |
| 2 | proactive-agent | 23 | 0.859 |
| 3 | design-image-search | 25 | 0.851 |
| 4 | maxhub-xhs | 3 | 0.814 |
| 5 | patent-novelty-i | 24 | 0.807 |
| 6 | dy-search | 21 | 0.802 |
| 7 | xiaohs-search | 21 | 0.801 |
| 8 | xiaohs-profile | 21 | 0.795 |
| 9 | dy-comments | 21 | 0.794 |
| 10 | xiaohs-comments | 21 | 0.792 |

➡️ Полный список: [rising-stars.csv](../data/2026-11-19/rankings/rising-stars.csv)

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
