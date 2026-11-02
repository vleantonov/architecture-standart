> [!NOTE]
> **Использование ИИ в работе**
>
> 1. ИИ использовался для формирования структуры и оформления диаграмм. Компоненты и связи задавались автором в промптах.
> 2. ИИ использовался для корректировки таблиц с требованиями.
> 3. ИИ использовался для формирования структуры Roadmap. Сами задачи полностью сформированы автором самостоятельно.

# Архитектура банка «Стандарт»

Материалы четырёх заданий: от текущего IT-ландшафта и требований до архитектуры депозитного MVP и плана внедрения на 6 месяцев.

## Task1 — текущий IT-ландшафт

Карты показывают системы банка, участников процессов и существующие интеграции между приложениями.

- Карта IT-ландшафта: [просмотр](Task1/it-landscape.svg) · [draw.io](Task1/it-landscape.drawio).
- Интеграции приложений и участники: [просмотр](Task1/application-integration.svg) · [draw.io](Task1/application-integration.drawio).

## Task2 — требования FURPS+

[Таблица FURPS+](Task2/FURPS+.md) содержит функциональные требования, требования к качеству и ограничения решения. Комментарии поясняют их влияние на архитектуру.

## Task3 — архитектура открытия депозитов

[ADR депозитного MVP](Task3/ADR-deposit-opening-mvp.md) описывает сценарии, архитектурное решение, интеграции, альтернативы и риски. Контейнерная схема объединяет текущее состояние и изменения для MVP.

- Контекст C4: [просмотр](Task3/deposit-mvp-context.png) · [PlantUML](Task3/deposit-mvp-context.puml).
- Контейнеры C4: [просмотр](Task3/deposit-containers.png) · [PlantUML](Task3/deposit-containers.puml).

## Task4 — ставки для кол-центров и Roadmap

[ADR публикации ставок](Task4/ADR-call-center-deposit-rates.md) описывает передачу ставок кол-центру банка через Kafka и партнёру через SFTP. Roadmap охватывает шесть систем, интеграции, запуск MVP и сбор метрик в пределах двух кварталов.

- Roadmap: [просмотр](Task4/deposit-roadmap-timeline.png) · [draw.io](Task4/deposit-roadmap.drawio).
- Контекст C4: [просмотр](Task4/call-center-rates-context.png) · [PlantUML](Task4/call-center-rates-context.puml).
- Компоненты адаптера АБС: [просмотр](Task4/rate-publication-components.png) · [PlantUML](Task4/rate-publication-components.puml).
- Компоненты каталога кол-центра банка: [просмотр](Task4/call-center-catalog-components.png) · [PlantUML](Task4/call-center-catalog-components.puml).

Файлы `.drawio` редактируются в diagrams.net, `.puml` — в PlantUML с библиотекой C4. PNG и SVG предназначены для просмотра. Файл Roadmap содержит две страницы: «Roadmap» и «Roadmap_change».
