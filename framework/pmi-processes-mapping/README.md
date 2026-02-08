# PMI Processes to Agents Mapping Framework

Фреймворк маппинга 49 процессов PMI Process Groups Practice Guide на агентов ProjectAI по Performance Domains.

## Содержание

- [Обзор](#обзор)
- [Performance Domains](#performance-domains)
- [Структура документации](#структура-документации)
- [Трекинг этапов](#трекинг-этапов)
- [Навигация](#навигация)

## Обзор

Структура фреймворка — по **Performance Domains** (Governance, Scope, Schedule, Finance, Stakeholders, Resources, Risk). Один домен — один раздел документации. Связь с группами процессов (Focus Areas) — в [reference/process-groups-to-domains.md](reference/process-groups-to-domains.md).

## Performance Domains

| Домен | Описание |
|-------|----------|
| Governance | Инициация, интеграция планов, исполнение, контроль, закрытие |
| Scope | Содержание, требования, WBS; контроль и валидация |
| Schedule | Расписание: планирование, разработка, контроль |
| Finance | Стоимость: план, оценки, бюджет, контроль |
| Stakeholders | Идентификация, вовлечение, коммуникации |
| Resources | Ресурсы: план, оценка, приобретение, команда, контроль |
| Risk | Риски: план, идентификация, анализ, ответы, мониторинг |

## Структура документации

- [mapping-matrix.md](mapping-matrix.md) — матрица процессов × агенты
- [domain-governance.md](domain-governance.md) … [domain-risk.md](domain-risk.md) — домены
- [reference/](reference/) — маппинг Focus Areas ↔ Domains, список процессов, справочник агентов
- [diagrams/](diagrams/) — обзор доменов, потоки данных, соответствие агентов и доменов

## Трекинг этапов

Таблица этапов 1–60: [STAGES.md](STAGES.md). После выполнения этапа помечать Status = done.

## Связь с Cursor

- **Фреймворк** (framework/pmi-processes-mapping/) — источник истины по доменам, процессам и маппингу на агентов.
- **Контекст агентов и требований:** при необходимости подключать `mas/requirements/business_requirements.md` и файлы из framework/pmi-processes-mapping/ (domain-*.md, reference/).
- **.cursor/agents/** — опционально: субагенты по доменам или по ключевым агентам; заготовки промптов можно формировать на основе domain-*.md и раздела «Контекст для агента» в них.

Подробнее: [reference/cursor-integration.md](reference/cursor-integration.md).

## Рекомендации по агентам

Рекомендации по новым агентам и расширениям существующих для непокрытых процессов приводятся в сводке по каждому домену (файлы domain-*.md, раздел 4). После заполнения матрицы покрытия (оценка по каждому процессу в [mapping-matrix.md](mapping-matrix.md)) сводки и приоритеты пробелов будут уточнены.

## Навигация

- План: см. приложенный план (60 этапов, цепочка результат → вход).
- Источник процессов: `knowledge/project-management/pmi/processgroupspracticeguide_eng.pdf`.
- Агенты: [reference/agents-reference.md](reference/agents-reference.md), `mas/requirements/business_requirements.md`.
