# Sportmaster × Ozon — выбор модели исполнения FBO / FBS

> Учебное тестовое задание на позицию Product Manager. Работа выполнена за 5 дней.

![Product case](https://img.shields.io/badge/type-product%20case-FFCC00) ![Marketplace](https://img.shields.io/badge/marketplace-Ozon-005BFF) ![Decision](https://img.shields.io/badge/decision-SKU--level-6C63FF) ![Delivery](https://img.shields.io/badge/delivery-5%20days-2E8B57)

## Кейс

[**Открыть полный разбор →**](docs/CASE_STUDY.md)

Исходная задача — оценить запуск FBS для продаж Sportmaster на Ozon. Я расширил выбор «FBO или FBS» до сценарной модели на уровне SKU: FBO, собственный FBS, гибрид и гибрид с внешним фулфилмент-партнёром.

При текущих вводных финансовой модели лучший результат показывает гибрид с Fulllog: **+912 999 ₽ операционной прибыли в месяц к FBO**. Это рекомендация для пилота, который должен подтвердить экономику, SLA и качество операций на реальном потоке.

## Материалы

| Раздел | Что внутри |
| --- | --- |
| [Исходное задание](docs/ASSIGNMENT.md) | Контекст, границы и ожидаемые результаты тестового задания |
| [Разбор кейса](docs/CASE_STUDY.md) | От постановки задачи до рекомендации и условий запуска |
| [Финансовая модель](assets/model/financial_model.xlsx) | Сценарный P&L и выбор схемы исполнения для SKU |
| [Метрики и пилот](docs/METRICS_AND_PILOT.md) | Целевая метрика, guardrails, этапы и decision gate |
| [Интеграционный контур](docs/INTEGRATION_CONTOUR.md) | Роли систем и логика обмена заказами, статусами и возвратами |
| [Риски](docs/RISKS.md) | Риски модели и действия до масштабирования |
| [FBO: текущий процесс](assets/bpmn/01_fbo.svg) | Поставка, исполнение заказа и возврат |
| [FBS: собственное исполнение](assets/bpmn/02_fbs.svg) | Обработка FBS-заказа и возврата |
| [Hybrid](assets/bpmn/03_hybrid.svg) | Распределение SKU между FBO и FBS |
| [Hybrid + Fulllog](assets/bpmn/04_hybrid_fulllog.svg) | FBS-поток через внешнего фулфилмент-партнёра |

## Ключевой вывод

Не переводить весь ассортимент в одну схему. Выбирать модель исполнения для каждого SKU по итоговой экономике, а позиции с отрицательным результатом в обеих схемах ставить на паузу до пересмотра цены, себестоимости или условий продаж.

## Навыки

`Product strategy` · `Scenario modelling` · `P&L` · `Unit economics` · `SKU analytics` · `BPMN` · `Marketplace operations` · `API integration` · `Product metrics` · `Pilot design` · `Risk management`
