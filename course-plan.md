# Tech English Course — план курса

Свой курс по мотивам Vocab for Devs, но под конкретную цель: свободное владение
техническим девелоперским английским для работы и собеседований.

## Принцип

От общего к частному — по двум осям сразу:

- **Частотность**: сначала лексика, нужная каждый день всем (standup, Slack), потом всё более
  узкие домены (architecture, incidents).
- **Формальность**: от живой устной речи к письменной точности (specs) и абстрактной
  аргументации (architecture discussions).

Интервью — не отдельный модуль в середине, а капстоун в конце: туда стекается лексика
из всех модулей + добавляется специфика интервью.

## Модули

Число уроков на модуль не фиксировано — зависит от того, сколько смысловых кластеров
лексики реально есть в теме (узкая тема вроде small talk может закрыться одним уроком,
широкая вроде Architecture — потребует несколько). Решаем по ходу.

| # | Модуль | Статус | Уроки |
|---|---|---|---|
| 1 | Daily Dev Communication (standups, Slack, async, small talk) | в работе | [01-standups-and-async](lessons/01-daily-dev-communication/01-standups-and-async.md) |
| 2 | Projects & Workflows (agile, planning, estimates, deadlines) | не начат | — |
| 3 | Coding in Practice (code review, PR, git, testing, refactoring) | не начат | — |
| 4 | Debugging & Incidents (bug reports, root cause, postmortems, on-call) | не начат | — |
| 5 | Documentation & Specs (tech writing, RFC, API docs) | не начат | — |
| 6 | DevOps & Deployment (releases, infra, monitoring, scaling) | не начат | — |
| 7 | Architecture & System Design (trade-offs, whiteboarding, design debates) | не начат | — |
| 8 | Interviews & Career (behavioral, technical, self-presentation, perf review) | не начат | — |

Статусы модуля: не начат / в работе (есть уроки, но тема не закрыта) / пройден (лексика
темы покрыта, решаем по факту, не по счётчику).

Когда добавляется урок — в колонку «Уроки» добавляется ссылка вида
`[NN-slug](lessons/MM-module-slug/NN-slug.md)`, статус модуля обновляется.

### Модуль 1 — план уроков (Daily Dev Communication)

- **01-standups-and-async** ✅ — статус, блокеры, договорённости не в реальном времени.
  Источник: блог-пост про async dailys (ferderer.de). Целевые слова: blocker, sync, async,
  escalate/escalation, huddle, follow-through, context switch, scale, onboarding,
  disengagement, box-ticking, interdependence
  (список отличается от изначально предполагаемого — подобран под реально найденную статью,
  а не придуман заранее)
- **02-slack-and-small-talk** — этикет переписки (треды, реакции, срочность) + лёгкий
  социальный small talk в рабочем контексте.
  Целевые слова: thread, DM, tag, escalate, nudge, bump, reach out, chime in, small talk,
  water cooler

Третий урок (например, про тайм-зоны/remote-культуру) добавляется по факту, если после
двух первых останется непокрытый кластер лексики.

## Формат урока

См. [lesson-plan.md](lesson-plan.md).

## Источник текстов

Аутентичные статьи/треды/доки ищутся под каждый урок отдельно (не генерируются с нуля) —
актуальная лексика 2026 года, реальный контекст, как в Vocab for Devs Bonus Unit.

## Структура папки

```
tech-english-course/
├── course-plan.md                          ← этот файл, роадмап и статус
├── lesson-plan.md                          ← шаблон структуры урока
└── lessons/
    ├── 01-daily-dev-communication/
    │   ├── 01-standups-and-async.md
    │   └── 02-slack-and-small-talk.md
    ├── 02-projects-and-workflows/
    │   └── 01-agile-ceremonies.md
    └── ...
```
