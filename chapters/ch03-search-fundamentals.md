# Chapter 3: Search Fundamentals

## Core Idea
Фундамент SEO — модель crawl-index-rank: сначала доступность, потом индексация, затем сигналы релевантности и авторитетности.

## Frameworks Introduced
- **Crawl → Index → Rank Pipeline**: Применяй для диагностики падений: где именно ломается поток.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат
- **Relevance + Authority model**: Используй баланс тематической релевантности и внешних сигналов доверия.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат

## Key Concepts
- **Crawler**: ключевой термин главы и практики SEO.
- **Index**: ключевой термин главы и практики SEO.
- **Canonical**: ключевой термин главы и практики SEO.
- **Robots**: ключевой термин главы и практики SEO.
- **Ranking Factors**: ключевой термин главы и практики SEO.

## Mental Models
- Use layered debugging: crawl first, index second, rank last.
- Think of technical constraints as throughput limits.

## Anti-patterns
- **Риск**: Лечить “позиции” без проверки индексируемости.
- **Риск**: Блокировать важные разделы robots/noindex по ошибке.

## Key Takeaways
1. Отладка SEO начинается с технической доступности.
2. Canonical/redirect должны быть консистентными.
3. Понимай, какие сигналы влияют на конкретный тип запросов.

## Connects To
- **Ch 2**: формирует контекст для этой темы.
- **Ch 4**: логичное продолжение для внедрения.

## Implementation Playbook
1. Run crawl diagnostics before rank investigations.
2. Audit robots/canonicals/sitemaps monthly.
3. Track index coverage deltas per template.

## Metrics to Watch
- **Valid indexed URLs**: track weekly and compare vs baseline.
- **Crawl errors**: track weekly and compare vs baseline.
- **Template-level impressions**: track weekly and compare vs baseline.

## Failure Modes & Fixes
- **Симптом**: результат не растет при активности.
  - **Проверка**: есть ли проблема интента/индексации/приоритета?
  - **Фикс**: вернись к фреймворку главы и перезапусти цикл измерения.
- **Симптом**: метрики шумят и решения спорные.
  - **Проверка**: единые ли определения KPI и сегменты?
  - **Фикс**: стандартизируй отчеты и закрепи владельцев данных.
