# Data Flow Diagrams

Потоки данных по доменам и между доменами.

## Внутридоменные потоки (концептуально)

- **Governance:** Charter → PM Plan → Work performance data/Info → Change requests → Closed deliverables.
- **Scope:** Requirements → Scope baseline (WBS) → Verified deliverables → Scope updates.
- **Schedule:** Activities → Schedule baseline → Work performance → Schedule updates.
- **Finance:** Cost baseline → Actuals → Cost forecasts → Updates.
- **Stakeholders:** Register → Engagement/Comm plans → Communications → Engagement metrics.
- **Resources:** Resource plan → Team/Resources acquired → Performance → Resource updates.
- **Risk:** Risk management plan → Register → Responses → Risk metrics.

## Междоменные точки интеграции

- **5.1 (PM Plan)** собирает выходы планирования из Scope, Schedule, Finance, Resources, Risk, Stakeholders.
- **7.1 (Monitor and Control)** использует данные из всех доменов (performance data).
- **7.2 (Integrated Change Control)** влияет на базовые планы Scope, Schedule, Cost и др.

## Участие компонентов МАС в потоках

TBD (после разработки концепции МАС). Для каждого процесса будет указано, какие компоненты МАС участвуют в сборе/обработке входов и формировании выходов (см. [mapping-matrix](../mapping-matrix.md) и domain-*.md).
