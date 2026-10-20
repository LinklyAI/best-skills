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

> Последнее обновление: **2026-10-20** (UTC) · Предпросмотр Top 10 для каждого рейтинга — полный Top 100 доступен в CSV.

<details open>
<summary><b>🏆 Лучшие 100 (рейтинг целесообразности установки)</b></summary>

| # | Skill | Издатель | WIS | Охват |
| --- | --- | --- | --- | --- |
| 1 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | 77.6 | C |
| 2 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | 76 | C |
| 3 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | 73.7 | C |
| 4 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | [mattpocock](https://www.skills.sh/mattpocock) | 70.3 | C |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | [mattpocock](https://www.skills.sh/mattpocock) | 67.8 | C |
| 6 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | [steipete](https://clawhub.ai/steipete) | 67.1 | B |
| 7 | [remotion-best-practices](https://www.skills.sh/remotion-dev/skills/remotion-best-practices) | [remotion-dev](https://www.skills.sh/remotion-dev) | 66.3 | C |
| 8 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 66 | B |
| 9 | [web-design-guidelines](https://www.skills.sh/vercel-labs/agent-skills/web-design-guidelines) | [vercel-labs](https://www.skills.sh/vercel-labs) | 64.9 | C |
| 10 | [setup-matt-pocock-skills](https://www.skills.sh/mattpocock/skills/setup-matt-pocock-skills) | [mattpocock](https://www.skills.sh/mattpocock) | 63 | C |

➡️ Полный список: [best-100.csv](../data/2026-10-20/rankings/best-100.csv)

</details>

<details>
<summary><b>📈 Лидеры по установкам (все экосистемы)</b></summary>

| # | Skill | skills.sh | ClawHub | SkillHub Китай |
| --- | --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 3,939,387 | — | — |
| 2 | dev-expert-pro | — | — | 5,188,304 |
| 3 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 1,392,524 | — | — |
| 4 | dev-god | — | — | 5,058,420 |
| 5 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 1,192,769 | — | — |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 1,178,796 | — | — |
| 7 | dev-expert | — | — | 4,867,726 |
| 8 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | — | 486,581 | 1,447,293 |
| 9 | [improve-codebase-architecture](https://www.skills.sh/mattpocock/skills/improve-codebase-architecture) | 1,138,023 | — | — |
| 10 | multi-search-engine | — | — | 3,896,449 |

➡️ Полный список: [top-installs.csv](../data/2026-10-20/rankings/top-installs.csv)

</details>

<details>
<summary><b>🚀 В тренде (7 дней)</b></summary>

| # | Skill | Установки | Недельный Δ% |
| --- | --- | --- | --- |
| 1 | [media-use](https://www.skills.sh/heygen-com/hyperframes/media-use) | 992,888 | 0.7 |
| 2 | [hyperframes-cli](https://www.skills.sh/heygen-com/hyperframes/hyperframes-cli) | 1,126,145 | 8.1 |
| 3 | [hyperframes-animation](https://www.skills.sh/heygen-com/hyperframes/hyperframes-animation) | 965,434 | 2.7 |
| 4 | [hyperframes](https://www.skills.sh/heygen-com/hyperframes/hyperframes) | 1,080,639 | 13.3 |
| 5 | [ai-image-generation](https://www.skills.sh/magentosh/superpowers/ai-image-generation) | 667,917 | 14.2 |
| 6 | [ai-video-generation](https://www.skills.sh/magentosh/superpowers/ai-video-generation) | 667,590 | 14.2 |
| 7 | [ai-avatar-video](https://www.skills.sh/magentosh/superpowers/ai-avatar-video) | 667,518 | 14.2 |
| 8 | [twitter-automation](https://www.skills.sh/magentosh/superpowers/twitter-automation) | 667,400 | 14.2 |
| 9 | [hyperframes-core](https://www.skills.sh/heygen-com/hyperframes/hyperframes-core) | 894,827 | 5.1 |
| 10 | [design-mobile-apps](https://www.skills.sh/designed-by-ai/skills/design-mobile-apps) | 914,309 | 0.2 |

➡️ Полный список: [trending-7d.csv](../data/2026-10-20/rankings/trending-7d.csv)

</details>

<details>
<summary><b>💬 Обсуждаемость (X · HN · Bluesky · GitHub, 7 дней)</b></summary>

| # | Skill | X | HN | Bluesky | GitHub |
| --- | --- | --- | --- | --- | --- |
| 1 | [grill-me](https://www.skills.sh/mattpocock/skills/grill-me) | 72+ | 3 | 6 | 39 |
| 2 | [self-improving](https://clawhub.ai/ivangdavila/skills/self-improving) | 73+ | 6 | 76 | 3 |
| 3 | [nano-banana-pro](https://clawhub.ai/steipete/skills/nano-banana-pro) | 23 | 2 | 14 | 12 |
| 4 | [grill-with-docs](https://www.skills.sh/mattpocock/skills/grill-with-docs) | 14 | 1 | 4 | 9 |
| 5 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 28 | 2 | 9 | 1 |
| 6 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | 82+ | 0 | 2 | 44 |
| 7 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | 33 | 0 | 3 | 89 |
| 8 | [browser-use](https://www.skills.sh/browser-use/browser-use/browser-use) | — | 3 | 10 | 12 |
| 9 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | 8 | 0 | 1 | 181 |
| 10 | [proactive-agent](https://clawhub.ai/halthelobster/skills/proactive-agent) | 36 | 0 | 1 | 1 |

➡️ Полный список: [social-buzz.csv](../data/2026-10-20/rankings/social-buzz.csv)

</details>

<details>
<summary><b>🔧 Самые активные (популярные и регулярно обновляемые)</b></summary>

| # | Skill | Обновлено | Версии |
| --- | --- | --- | --- |
| 1 | cloudbase | 2026-10-19 | 238 |
| 2 | [chinese-official-writing](https://clawhub.ai/gongyu0918-debug/skills/chinese-official-writing) | 2026-10-19 | 153 |
| 3 | [cellcog](https://clawhub.ai/nitishgargiitd/skills/cellcog) | 2026-10-19 | 52 |
| 4 | [getnote](https://clawhub.ai/iswalle/skills/getnote) | 2026-10-19 | 50 |
| 5 | scrapling-official | 2026-10-17 | 16 |
| 6 | web-search-plus | 2026-10-10 | 63 |
| 7 | [planning-with-files](https://clawhub.ai/othmanadi/skills/planning-with-files) | 2026-10-10 | 28 |
| 8 | [self-improving-agent](https://clawhub.ai/pskoett/skills/self-improving-agent) | 2026-10-04 | 40 |
| 9 | [api-gateway](https://clawhub.ai/byungkyu/skills/api-gateway) | 2026-10-02 | 182 |
| 10 | homeassistant-skill | 2026-10-12 | 6 |

➡️ Полный список: [most-active.csv](../data/2026-10-20/rankings/most-active.csv)

</details>

<details>
<summary><b>✅ Официальные 100 (проверенные издатели)</b></summary>

| # | Skill | Издатель | Проверено |
| --- | --- | --- | --- |
| 1 | [find-skills](https://www.skills.sh/vercel-labs/skills/find-skills) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 2 | dev-god | 阿客（北京）科技有限公司 | skillhub |
| 3 | [agent-browser](https://www.skills.sh/vercel-labs/agent-browser/agent-browser) | [vercel-labs](https://www.skills.sh/vercel-labs) | skills.sh |
| 4 | multi-search-engine | 成都智创未来教育管理合伙企业（有限合伙） | skillhub |
| 5 | tencent-docs | 腾讯科技（深圳）有限公司 | skillhub |
| 6 | [frontend-design](https://www.skills.sh/anthropics/skills/frontend-design) | [anthropics](https://www.skills.sh/anthropics) | skills.sh |
| 7 | beatra | 乐萱同行科技（深圳）有限公司 | skillhub |
| 8 | cic | 成都国信公链科技有限公司 | skillhub |
| 9 | [github](https://clawhub.ai/steipete/skills/github) | [steipete](https://clawhub.ai/steipete) | clawhub |
| 10 | [obsidian](https://clawhub.ai/steipete/skills/obsidian) | [steipete](https://clawhub.ai/steipete) | clawhub |

➡️ Полный список: [official-100.csv](../data/2026-10-20/rankings/official-100.csv)

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
| 7 | [skills.sh](https://www.skills.sh) | [nvidia](https://www.skills.sh/nvidia) | 1190 | 431,451 |
| 8 | [skills.sh](https://www.skills.sh) | [remotion-dev](https://www.skills.sh/remotion-dev) | 19 | 305,359 |
| 9 | [skills.sh](https://www.skills.sh) | [flutter](https://www.skills.sh/flutter) | 88 | 286,211 |
| 10 | [skills.sh](https://www.skills.sh) | [expo](https://www.skills.sh/expo) | 18 | 283,306 |

➡️ Полный список: [official-vendors.csv](../data/2026-10-20/rankings/official-vendors.csv)

</details>

<details>
<summary><b>⭐ Лучшие репозитории</b></summary>

| # | Репозиторий | Stars | Последний push |
| --- | --- | --- | --- |
| 1 | [morluto/rea](https://github.com/morluto/rea) | 336,760 | 2026-10-19 |
| 2 | [obra/superpowers](https://github.com/obra/superpowers) | 302,131 | 2026-10-10 |
| 3 | [mattpocock/skills](https://github.com/mattpocock/skills) | 297,495 | 2026-10-19 |
| 4 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | 284,142 | 2026-10-19 |
| 5 | [anthropics/skills](https://github.com/anthropics/skills) | 182,236 | 2026-10-09 |
| 6 | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) | 168,102 | 2026-10-18 |
| 7 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 152,646 | 2026-10-19 |
| 8 | [vercel/next.js](https://github.com/vercel/next.js) | 143,096 | 2026-10-20 |
| 9 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 137,615 | 2026-10-15 |
| 10 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 125,974 | 2026-10-19 |

➡️ Полный список: [top-repos.csv](../data/2026-10-20/rankings/top-repos.csv)

</details>

<details>
<summary><b>🌱 Восходящие звёзды (младше 30 дней)</b></summary>

| # | Skill | Возраст (дни) | Популярность |
| --- | --- | --- | --- |
| 1 | dev-expert-pro | 4 | 0.999 |
| 2 | dev-god | 12 | 0.998 |
| 3 | cic | 22 | 0.988 |
| 4 | gongwen-writting-2 | 29 | 0.968 |
| 5 | aigccerts | 3 | 0.964 |
| 6 | [ui-taste](https://www.skills.sh/uizze.sh/ui-taste) | 29 | 0.95 |
| 7 | xique-tender-pay | 12 | 0.913 |
| 8 | course-video-studio | 8 | 0.911 |
| 9 | totorosir-workbuddy-score | 29 | 0.903 |
| 10 | humanize-ai-text | 27 | 0.883 |

➡️ Полный список: [rising-stars.csv](../data/2026-10-20/rankings/rising-stars.csv)

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
