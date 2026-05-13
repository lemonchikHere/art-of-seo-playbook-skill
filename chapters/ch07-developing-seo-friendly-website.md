# Chapter 7: Developing an SEO-Friendly Website

## Core Idea
SEO-friendly сайт сочетает корректную техническую архитектуру, ясную инфо-структуру и качественную on-page оптимизацию.

## Frameworks Introduced
- **Technical Baseline Checklist**: Применяй список: indexability, speed, mobile, structured data, internal links.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат
- **Information Architecture by Intent**: Проектируй разделы и URL-иерархию под сценарии поиска.
  - When to use: при планировании и решении задач главы
  - How: определи контекст, выбери метрики, примени метод, проверь результат

## Key Concepts
- **Core Web Vitals**: ключевой термин главы и практики SEO.
- **Internal Linking**: ключевой термин главы и практики SEO.
- **Schema**: ключевой термин главы и практики SEO.
- **URL Strategy**: ключевой термин главы и практики SEO.
- **Rendering**: ключевой термин главы и практики SEO.

## Mental Models
- Use crawl depth control for critical pages.
- Think of internal links as authority routing.

## Anti-patterns
- **Риск**: Сложные JS-рендеринг-цепочки без проверки индексации.
- **Риск**: Сиротские страницы без внутренних ссылок.

## Key Takeaways
1. Проверь mobile-first и CWV на шаблонах.
2. Используй schema там, где она улучшает понимание сущностей.
3. Укрепляй ключевые страницы перелинковкой.

## Connects To
- **Ch 6**: формирует контекст для этой темы.
- **Ch 8**: логичное продолжение для внедрения.

## Implementation Playbook
1. Validate CWV on key templates every release.
2. Enforce internal-link minimum for money pages.
3. Review schema completeness by entity type.

## Metrics to Watch
- **CWV pass rate**: track weekly and compare vs baseline.
- **Internal link depth**: track weekly and compare vs baseline.
- **Rich result eligibility**: track weekly and compare vs baseline.

## Failure Modes & Fixes
- **Симптом**: результат не растет при активности.
  - **Проверка**: есть ли проблема интента/индексации/приоритета?
  - **Фикс**: вернись к фреймворку главы и перезапусти цикл измерения.
- **Симптом**: метрики шумят и решения спорные.
  - **Проверка**: единые ли определения KPI и сегменты?
  - **Фикс**: стандартизируй отчеты и закрепи владельцев данных.
