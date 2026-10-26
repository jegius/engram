# 19. Референсы: аннотированная библиография

> **Статус:** Draft v0.1 · **Владелец:** Creative Director + Tech Lead · **Зависит от:** [00 Видение](00-vision.md), [01 Канон](01-canon.md) · **Обновлено:** 2026-10-26

## 1. Как читать документ

Ссылки проверялись 2026-10-26. Маркировка: **✅** — открывалась при подготовке (HTTP 200/202); **◐** — обнаружена поиском или редиректом, открывается в браузере, но автопроверка не прошла (Cloudflare, cross-origin); **⚠** — не проверялась (домен недоступен из рабочей среды или известен по опыту). Для книг вместо URL иногда даётся DOI/издатель, потому что страница книги нестабильна. Правило: **непроверенную ссылку нельзя ставить в документ без маркера**; при следующей ревизии ⚠ либо подтверждается, либо удаляется.

## 2. Астрофизика и физика

| Источник | Ссылка | Зачем проекту |
|---|---|---|
| Murray & Dermott, *Solar System Dynamics*, Cambridge, 1999 | [doi.org/10.1017/CBO9781139174817](https://doi.org/10.1017/CBO9781139174817) ◐ | орбитальная динамика, резонансы, секулярные возмущения — база для L1 и генератора систем (01 §6.2, §8.2) |
| Carroll & Ostlie, *An Introduction to Modern Astrophysics*, 2nd ed., Cambridge | [cambridge.org — Modern Astrophysics](https://www.cambridge.org/ae/universitypress/subjects/physics/astrophysics/introduction-modern-astrophysics-2nd-edition) ◐ | звёздные классы, светимость, зоны обитаемости — палитра и генерация звёзд |
| Shapiro & Teukolsky, *Black Holes, White Dwarfs, and Neutron Stars*, Wiley, 1983 | [Google Books](https://books.google.com/books?id=R0MzEQAAQBAJ) ◐ | радиус Шварцшильда, аккреция, приливное разрушение (01 §8.5) |
| Frank, King & Raine, *Accretion Power in Astrophysics*, Cambridge | [doi.org/10.1017/CBO9781139164245](https://doi.org/10.1017/CBO9781139164245) ◐ | аккреционные диски, эффективность 5,7–42 %, джеты (01 §8.5) |
| Janka, *Neutron Star Formation and Supernova* (обзор) | [arXiv: поиск «core-collapse supernovae»](https://arxiv.org/search/?query=core-collapse+supernovae&searchtype=all) ✅ | физика сверхновых: энергия ~10⁴⁴ Дж, нейтринный фон, предвестники (01 §8.4) |
| NIST CODATA, фундаментальные постоянные | [physics.nist.gov/cuu/Constants](https://physics.nist.gov/cuu/Constants/) ✅ | эталон G, c, M☉, а.е. — сверка констант канона (01 §8.1) |
| NASA ADS — астрофизическая библиотека | [ui.adsabs.harvard.edu](https://ui.adsabs.harvard.edu/) ✅ | быстрый поиск первоисточников для спорных формул и чисел |
| arXiv, astro-ph | [arxiv.org](https://arxiv.org/) ✅ | открытые препринты: кинетика, планетология, релятивистские удары |
| HDRP-референсы по освещению и линзированию (технические статьи Unity) | [docs.unity3d.com — HDRP](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@17.0/manual/index.html) ◐ | физические единицы света, экспозиция, шейдеры ЧД (11 §3.5–3.6) |
| Bate, Mueller & White, *Fundamentals of Astrodynamics*, Dover, 1971 | [store.doverpublications.com](https://store.doverpublications.com/) ⚠ | задачи двух тел, Hohmann-переходы, гравитационные манёвры — для подсказок и прогноза курса |

## 3. Источники данных

| Источник | Ссылка | Зачем проекту |
|---|---|---|
| NASA Exoplanet Archive | [exoplanetarchive.ipac.caltech.edu](https://exoplanetarchive.ipac.caltech.edu/) ✅ | распределения масс/радиусов/периодов для генерации планет (01 §6.2–6.4) |
| JPL Horizons | [ssd.jpl.nasa.gov/horizons](https://ssd.jpl.nasa.gov/horizons/) ⚠ | эфемериды и состояния тел — сверка интеграторов WHFast/IAS15 (01 §8.2) |
| JPL Small-Body Database | [ssd.jpl.nasa.gov/tools/sbdb_lookup.html](https://ssd.jpl.nasa.gov/tools/sbdb_lookup.html) ⚠ | распределения астероидов и комет для поясов (01 §6.2) |
| IAU — Международный астрономический союз | [iau.org](https://www.iau.org/) ✅ | авторитетные определения, названия, системы координат |
| IAU Minor Planet Center | [minorplanetcenter.net](https://www.minorplanetcenter.net/) ⚠ | каталог малых тел; ссылка взята с сайта IAU |
| NASA/GSFC Planetary Fact Sheets | [nssdc.gsfc.nasa.gov/planetary/factsheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/) ⚠ | эталонные параметры планет для «бытовой» шкалы интерфейса |
| NASA ADS/arXiv (повторно) | см. §2 ✅ | данные для балансных таблиц и проверки распределений |

## 4. Гейм-дизайн и нарратив

| Источник | Ссылка | Зачем проекту |
|---|---|---|
| GDC (конференция и доклады) | [gdconf.com](https://gdconf.com/) ✅ | системный дизайн, постмортемы, продакшн-практики |
| GDC Vault — архив докладов | [gdcvault.com](https://gdcvault.com/) ◐ | материалы по симуляциям, экономике и нарративу; редиректит на gdconf.com |
| Game Developer — статьи и постмортемы | [gamedeveloper.com](https://www.gamedeveloper.com/) ✅ | разборы провалов и успехов, в т. ч. симуляторов |
| Jesse Schell, *The Art of Game Design* | [schellgames.com](https://www.schellgames.com/) ⚠ | линзы дизайна, опыт игрока — проверка решений по UX |
| Tynan Sylvester, *Designing Games* | [tynansylvester.com](https://tynansylvester.com/) ⚠ | «игра как генератор историй» — философия живой галактики (00 §3) |
| Steve Swink, *Game Feel* | [routledge.com](https://www.routledge.com/) ⚠ | ощущение управления, обратная связь — полёт и наземный режим |
| Salen & Zimmerman, *Rules of Play* | [MIT Press](https://mitpress.mit.edu/9780262240451/rules-of-play/) ⚠ | формальные рамки правил и «магический круг» — для системного дизайна |
| Miguel Sicart, *The Ethics of Computer Games* | [MIT Press](https://mitpress.mit.edu/) ⚠ | цена насилия и последствий — тон мира (00 §6) |
| Tarn Adams, интервью и доклады о Dwarf Fortress | [bay12games.com/dwarves](https://www.bay12games.com/dwarves/) ✅ | эмерджентность, «симуляция важнее графики», цена потери |
| Brenda Romero, доклады о дизайне и нарративе | [brendaromero.com](https://brendaromero.com/) ⚠ | нарратив через системы и последствия, а не через кат-сцены |

## 5. Референсные игры

| Игра | Ссылка | Что берём |
|---|---|---|
| «Космические рейнджеры» (Space Rangers HD: A War Apart) | [Steam: 214730](https://store.steampowered.com/app/214730/) ✅ | дух и тон, быт, бюрократия, «маленький человек в большой галактике», смесь жанров и текстовых квестов |
| Elite Dangerous | [elitedangerous.com](https://www.elitedangerous.com/) ⚠ | ощущение масштаба, карта галактики, полёт и станции (00 §5) |
| EVE Online | [eveonline.com](https://www.eveonline.com/) ⚠ | рынок, ордербуки, производственные цепочки, экономика как политика |
| Starsector | [fractalsoftworks.com](https://fractalsoftworks.com/) ◐ | кампания с живым сектором, флоты, снабжение, читаемость боя |
| Stellaris | [paradoxinteractive.com](https://www.paradoxinteractive.com/games/stellaris) ⚠ | автономные империи, дипломатия, «мир живёт сам» |
| Dwarf Fortress | [bay12games.com/dwarves](https://www.bay12games.com/dwarves/) ✅ | эмерджентные истории, глубина симуляции, цена потери |
| Aurora 4X | [aurora4x.com](https://aurora4x.com/) ✅ | глубокая симуляция флотов, технологий и логистики; урок о цене сложности |
| Children of a Dead Earth | [childrenofadeadearth.com](https://www.childrenofadeadearth.com/) ✅ | физика как геймплей: орбиты, кинетика, реалистичный урон (00 §5) |
| Terra Invicta | [pavonisinteractive.com](https://www.pavonisinteractive.com/) ◐ | геополитика и «медленная» стратегия поверх симуляции; фракционные арки |
| FTL: Faster Than Light | [subsetgames.com](https://subsetgames.com/) ⚠ | корабль как набор систем, управление экипажем, напряжение |
| RimWorld | [rimworldgame.com](https://rimworldgame.com/) ✅ | сторителлинг через события; AI-рассказчик как референс темпа |
| Hardspace: Shipbreaker | [hardspaceshipbreaker.com](https://www.hardspaceshipbreaker.com/) ⚠ | разбор кораблей, тактильность ремонта и салважа |
| X4: Foundations | [egosoft.com](https://www.egosoft.com/) ⚠ | живой сектор, флоты и торговля; уроки о производительности и UI |
| Sunless Skies | [failbettergames.com](https://www.failbettergames.com/) ⚠ | тон, текстовый нарратив, страх и одиночество в космосе |
| Offworld Trading Company | [mohawkgames.com](https://www.mohawkgames.com/) ⚠ | экономика как соревнование, читаемость рынка и ценовых шоков |

## 6. Документация инструментов

| Инструмент | Ссылка | Зачем проекту |
|---|---|---|
| Unity DOTS / Entities 1.3 | [docs.unity3d.com — Entities](https://docs.unity3d.com/Packages/com.unity.entities@1.3/manual/index.html) ✅ | ECS, Burst, Jobs — основа L1–L2 (01 §4, [03](03-architecture.md)) |
| Unity HDRP 17 | [docs.unity3d.com — HDRP](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@17.0/manual/index.html) ◐ | физический свет, экспозиция, шейдеры (11 §3.5) |
| Houdini (Indie) — документация | [sidefx.com/docs/houdini](https://www.sidefx.com/docs/houdini/) ✅ | процедурные планеты, поля, разрушение; батч-пайплайн (11 §3.7) |
| FMOD Studio — документация | [fmod.com/docs/2.03/studio](https://www.fmod.com/docs/2.03/studio/) ✅ | адаптивная музыка, снапшоты, диегетика (11 §5) |
| Blender 4.2 LTS Manual | [docs.blender.org/manual/en/4.2](https://docs.blender.org/manual/en/4.2/) ✅ | моделирование и экспорт ассетов (01 §4) |
| GameCI — CI/CD для Unity | [game.ci](https://game.ci/) ✅ | ночные сборки и тесты в GitHub Actions ([13](13-content-pipeline-devops.md)) |
| Crowdin — локализация | [crowdin.com](https://crowdin.com/) ⚠ | строки RU/EN и будущие языки (01 §4, 11 §4.8) |
| NUnit | [nunit.org](https://nunit.org/) ⚠ | unit-тесты логики симуляции (12 §3) |
| FsCheck | [fscheck.github.io](https://fscheck.github.io/FsCheck/) ⚠ | property-based инварианты баланса (12 §4) |
| Sentry | [sentry.io](https://sentry.io/) ⚠ | краш-репорты без PII (12 §8, §15) |

## 7. Что мы сознательно не берём

- **Космические симуляторы-песочницы без цели** (Elite в части гринда, No Man's Sky) — противоречит anti-goal «не бесконечная процедурная пустота» (00 §8).
- **MMO-экономику и PvP-баланс** — на релизе нет мультиплеера (00 §8).
- **Реализм ради реализма** (Children of a Dead Earth целиком) — берём физику как язык, но оставляем space opera допущения (01 §4, 00 §12.3).
- **Гримдарк и «древнее зло»** — Эхо это загадка, а не антагонист (00 §6).

## 8. Открытые вопросы

1. Нужен ли внутренний «научный консультант» (0,2 FTE) для сверки формул, или достаточно ревью Sim-программиста?
2. Поддерживать ли публичную страницу «источники и допущения» для сообщества и моддеров?
3. Какие референсы обязательны для онбординга новых сотрудников (список из 5–7 позиций)?
4. Обновлять ли библиографию при каждой смене канона чисел или раз в полгода?

## 9. Предложения к канону

1. **Маркировка ссылок** (✅/◐/⚠) — сделать обязательной для всех документов, где есть внешние источники.
2. **Эталонные источники констант:** NIST CODATA и JPL — зафиксировать как «источник по умолчанию» для §8.1 канона.
3. **Список обязательных референсов** (5–7 игр/книг) — включить в [14](14-roadmap.md) как часть онбординга.
4. **Ревизия библиографии** — раз в 6 месяцев, с датой проверки в шапке.

## 10. Связанные документы

- [00. Видение](00-vision.md) — референсы по слоям, anti-goals.
- [01. Канон](01-canon.md) — числа и стек, которые подтверждают источники.
- [11. Арт/UX/аудио/нарратив](11-art-ux-audio-narrative.md), [12. Баланс и тесты](12-balance-testing-telemetry.md).
- [02. Тулчейн](02-toolchain.md), [03. Архитектура](03-architecture.md), [04. Симуляция и физика](04-simulation-physics.md), [18. Глоссарий и формулы](18-glossary-formulas.md).
- [06. Экономика](06-economy.md), [07. Цивилизации](07-civilizations-tech-politics.md), [08. Бой](08-combat.md), [10. Планеты](10-planets-landing.md).
