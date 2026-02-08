# Mapping Matrix: 49 PMI Processes

Матрица процессов PMI. Покрытие компонентами МАС — TBD после разработки концепции МАС. Распределение процессов по Performance Domains — по [reference/process-groups-to-domains.md](reference/process-groups-to-domains.md).

## Legend (покрытие)

| Маркер | Покрытие   | Описание |
|--------|------------|----------|
| 🟢     | 80–100%    | Функции процесса в основном покрыты компонентами МАС |
| 🟡     | 50–79%     | Основное покрытие, есть пробелы |
| 🟠     | 20–49%     | Частичное покрытие, нужно расширение |
| 🔴     | &lt;20%     | Минимальное/нет покрытия |
| TBD    | —          | Оценка будет уточнена после концепции МАС и этапов 12–60 |

## Режим выполнения (foreground / background)

Для проектирования МАС процессы могут быть помечены режимом выполнения:

| Режим | Описание | Критерии (примеры) |
|-------|----------|---------------------|
| **Foreground** | Выполняется последовательно, результат нужен для следующих шагов | Зависимость от выхода другого процесса (например, 5.1 после планов по доменам), критичность для принятия решений |
| **Background** | Допускается параллельный запуск | Независимые от других процессов подзадачи, длительные сборы данных, мониторинг |

Атрибут будет проставляться при заполнении матрицы и domain-*.md (этапы 12–60).

## Матрица (скелет)

Строки сгруппированы по доменам. Колонка «Покрытие МАС» заполняется после разработки концепции МАС.

### Governance

| Process | Покрытие МАС |
|---------|--------------|
| 4.1 Develop Project Charter | TBD |
| 5.1 Develop Project Management Plan | TBD |
| 6.1 Direct and Manage Project Work | TBD |
| 7.1 Monitor and Control Project Work | TBD |
| 7.2 Perform Integrated Change Control | TBD |
| 8.1 Close Project or Phase | TBD |

### Scope

| Process | Покрытие МАС |
|---------|--------------|
| 5.2 Plan Scope Management | TBD |
| 5.3 Collect Requirements | TBD |
| 5.4 Define Scope | TBD |
| 5.5 Create WBS | TBD |
| 7.3 Validate Scope | TBD |
| 7.4 Control Scope | TBD |

### Schedule

| Process | Покрытие МАС |
|---------|--------------|
| 5.6 Plan Schedule Management | TBD |
| 5.7 Define Activities | TBD |
| 5.8 Sequence Activities | TBD |
| 5.9 Estimate Activity Durations | TBD |
| 5.10 Develop Schedule | TBD |
| 7.5 Control Schedule | TBD |

### Finance

| Process | Покрытие МАС |
|---------|--------------|
| 5.11 Plan Cost Management | TBD |
| 5.12 Estimate Costs | TBD |
| 5.13 Determine Budget | TBD |
| 7.6 Control Costs | TBD |

### Stakeholders

| Process | Покрытие МАС |
|---------|--------------|
| 4.2 Identify Stakeholders | TBD |
| 5.17 Plan Communications Management | TBD |
| 5.24 Plan Stakeholder Engagement | TBD |
| 6.7 Manage Communications | TBD |
| 6.10 Manage Stakeholder Engagement | TBD |
| 7.9 Monitor Communications | TBD |
| 7.12 Monitor Stakeholder Engagement | TBD |

### Resources

| Process | Покрытие МАС |
|---------|--------------|
| 5.15 Plan Resource Management | TBD |
| 5.16 Estimate Activity Resources | TBD |
| 6.4 Acquire Resources | TBD |
| 6.5 Develop Team | TBD |
| 6.6 Manage Team | TBD |
| 7.8 Control Resources | TBD |

### Risk

| Process | Покрытие МАС |
|---------|--------------|
| 5.18 Plan Risk Management | TBD |
| 5.19 Identify Risks | TBD |
| 5.20 Perform Qualitative Risk Analysis | TBD |
| 5.21 Perform Quantitative Risk Analysis | TBD |
| 5.22 Plan Risk Responses | TBD |
| 6.8 Implement Risk Responses | TBD |
| 7.10 Monitor Risks | TBD |

### Cross-domain (Procurement, Quality, Knowledge)

| Process | Покрытие МАС |
|---------|--------------|
| 5.14 Plan Quality Management | TBD |
| 5.23 Plan Procurement Management | TBD |
| 6.2 Manage Project Knowledge | TBD |
| 6.3 Manage Quality | TBD |
| 6.9 Conduct Procurements | TBD |
| 7.7 Control Quality | TBD |
| 7.11 Control Procurements | TBD |

---

После разработки концепции МАС и этапов 12–60: подстановка оценок покрытия (🟢🟡🟠🔴) и сводная статистика по доменам.
