# PMI Processes Mapping Framework

Фреймворк маппинга 49 процессов PMI Process Groups Practice Guide по Performance Domains. Соответствие процессов и компонентов МАС будет определено после разработки концепции МАС.

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

- [mapping-matrix.md](mapping-matrix.md) — матрица процессов (покрытие компонентами МАС — TBD после концепции МАС)
- [domain-governance.md](domain-governance.md) … [domain-risk.md](domain-risk.md) — домены
- [reference/](reference/) — маппинг Focus Areas ↔ Domains, список процессов
- [diagrams/](diagrams/) — обзор доменов, потоки данных

## Связь с Cursor

- **Фреймворк** (framework/pmi-processes-mapping/) — источник истины по доменам и процессам PMI.
- **Требования к МАС:** при необходимости подключать `mas/requirements/business_requirements.md` и файлы из framework/pmi-processes-mapping/ (domain-*.md, reference/).
- **.cursor/agents/** — опционально после появления концепции МАС: заготовки субагентов по доменам на основе domain-*.md.

Подробнее: [reference/cursor-integration.md](reference/cursor-integration.md).

## Навигация

- План: см. приложенный план (60 этапов, цепочка результат → вход).
- Источник процессов: `knowledge/project-management/pmi/processgroupspracticeguide_eng.pdf`.
- Требования к МАС: [mas/requirements/business_requirements.md](../../mas/requirements/business_requirements.md).
