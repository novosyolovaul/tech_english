# Tech English Course

A self-built technical English course for developers: daily communication, workflows,
code reviews, incidents, docs, and interviews — built from real articles, not textbook
dialogues.

## О курсе

Свой курс по мотивам *Vocab for Devs*, но под конкретную цель: свободное владение
техническим девелоперским английским для работы и собеседований — не для
стандартизированных тестов (IELTS/TOEFL и т.п.).

Принцип — от общего к частному по двум осям сразу:

- **Частотность**: сначала лексика, нужная каждый день всем (standup, Slack), потом всё
  более узкие домены (architecture, incidents).
- **Формальность**: от живой устной речи к письменной точности (specs) и абстрактной
  аргументации (architecture discussions).

Интервью — не отдельный модуль в середине, а капстоун в конце: туда стекается лексика из
всех модулей + добавляется специфика интервью.

## Структура репозитория

```
tech-english-course/
├── README.md            ← этот файл
├── course-plan.md        ← роадмap: 8 модулей, статус, ссылки на уроки
├── lesson-plan.md         ← шаблон структуры урока (9 шагов)
└── lessons/
    └── 01-daily-dev-communication/
        └── 01-standups-and-async.md
```

Актуальный статус модулей и список уроков — в [course-plan.md](course-plan.md).

## Формат урока

Каждый урок — один самодостаточный файл: слова, статья, все упражнения и ответы в одном
месте, без внешних зависимостей. Полный шаблон — в [lesson-plan.md](lesson-plan.md).

9 шагов:

1. **Intro** — модуль, слова, источник
2. **Word preview** — слово → перевод
3. **Article** — отрывок из настоящей статьи/доков/PR-треда с выделенными словами
4. **Matching** — слово → определение на английском
5. **Collocations** — 2 самых частотных сочетания на слово, с переводом
6. **Discrimination task** — выбор между двумя близкими по смыслу словами
7. **Combine & rewrite** — переписать нейтральное предложение естественно, со словами
8. **Translation (RU→EN)** — перевод с живого русского, без калек
9. **Personalization** — вопросы о реальном опыте + Answer Key

Целевых слов на урок — 10–13, реальные, взятые из аутентичного источника под тему урока
(статья не генерируется с нуля).

## Модули

1. Daily Dev Communication (standups, Slack, async, small talk)
2. Projects & Workflows (agile, planning, estimates, deadlines)
3. Coding in Practice (code review, PR, git, testing, refactoring)
4. Debugging & Incidents (bug reports, root cause, postmortems, on-call)
5. Documentation & Specs (tech writing, RFC, API docs)
6. DevOps & Deployment (releases, infra, monitoring, scaling)
7. Architecture & System Design (trade-offs, whiteboarding, design debates)
8. Interviews & Career (behavioral, technical, self-presentation, perf review)

Число уроков на модуль не фиксировано — зависит от того, сколько смысловых кластеров
лексики реально есть в теме.
