# Chapter 4: Your SEO Toolbox

## Core Idea
Инструменты SEO должны поддерживать единую операционную систему: исследование, аудит, мониторинг, отчётность и эксперименты.

## Frameworks Introduced
- **Toolchain by Job-to-be-Done**: Выбирай инструменты по задаче: technical crawl, keyword intel, log analysis, analytics.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат
- **Single Source of Truth Reporting**: Строй единый слой метрик, чтобы избежать конфликтующих цифр.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат

## Key Concepts
- **Crawlers**: ключевой термин главы и практики SEO.
- **GSC**: ключевой термин главы и практики SEO.
- **Log Analysis**: ключевой термин главы и практики SEO.
- **Rank Tracking**: ключевой термин главы и практики SEO.
- **Dashboards**: ключевой термин главы и практики SEO.

## Mental Models
- Use minimum viable stack before buying more tools.
- Think workflow-first, tool-second.

## Anti-patterns
- **Риск**: Коллекционирование инструментов без процессов.
- **Риск**: Отчеты с несогласованными определениями KPI.

## Key Takeaways
1. Фиксируй владельца для каждого блока данных.
2. Стандартизируй naming и metric definitions.
3. Интегрируй алерты для критичных аномалий.

## Connects To
- **Ch 3**: формирует контекст для этой темы.
- **Ch 5**: логичное продолжение для внедрения.

## Implementation Playbook
1. Define tool ownership (GSC, crawler, analytics).
2. Standardize KPI definitions in one doc.
3. Automate weekly anomaly alerts.

## Metrics to Watch
- **Alert MTTR**: track weekly and compare vs baseline.
- **Report consistency**: track weekly and compare vs baseline.
- **Data freshness SLA**: track weekly and compare vs baseline.

## Failure Modes & Fixes
- **Симптом**: результат не растет при активности.
  - **Проверка**: есть ли проблема интента/индексации/приоритета?
  - **Фикс**: вернись к фреймворку главы и перезапусти цикл измерения.
- **Симптом**: метрики шумят и решения спорные.
  - **Проверка**: единые ли определения KPI и сегменты?
  - **Фикс**: стандартизируй отчеты и закрепи владельцев данных.
