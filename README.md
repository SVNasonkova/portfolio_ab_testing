# Портфолио по анализу данных с примерами дизайна A/B-экспериментов для продуктовых и маркетинговых задач в цифровых продуктах.
Репозиторий содержит проекты, выполненные в ходе курса по анализу данных

# A/B Testing & Experiment Design Portfolio

**Keywords:** A/B Testing, Experiment Design, Product Analytics, CRM Analytics

Репозиторий с примерами дизайна A/B-экспериментов для продуктовых  
и маркетинговых задач в цифровых продуктах.

Фокус — на формулировке гипотез, выборе метрик, дизайне экспериментов  
и учёте продакшн-ограничений.

---

## Проекты

№ | Ссылка на проект | Отрасль бизнеса | Описание | Навыки и подходы, представленные в проектах | Презентация проекта
---|---|---|---|---|---
1 | [Supperapp: Marketplace Removal](https://github.com/SVNasonkova/portfolio_ab_testing/tree/4d18901977a6c1d7a9eaa45062527997153b985d/case_1_superapp_marketplace) | Digital / Superapp / Mobility | Дизайн A/B/n-эксперимента для оценки влияния удаления маркетплейса из супераппа на вовлечённость пользователей в заказ такси. Проработка гипотез, primary и guardrail-метрик, рандомизации, утечки и вызревания метрик. | Product analytics, A/B/n testing, Experiment design, ITT, Guardrail metrics, Metric maturation, Stratification, CUPED |[Презентация "Supperapp — влияние удаления маркетплейса"](https://github.com/SVNasonkova/portfolio_ab_testing/blob/4d18901977a6c1d7a9eaa45062527997153b985d/case_1_superapp_marketplace/presentation.pdf)
2 | [Email vs Push Marketing Test](https://github.com/SVNasonkova/portfolio_ab_testing/tree/4d18901977a6c1d7a9eaa45062527997153b985d/case_2_marketing_channels) | Marketing / CRM / Growth | Дизайн A/B/n (4-arm) эксперимента для сравнения эффективности email- и push-коммуникаций в привлечении новых клиентов. Выбор success- и guardrail-метрик, контроль побочных эффектов, обоснование серии тестов. | Growth analytics, A/B/n testing, CRM experimentation, Uplift measurement, Guardrail metrics, Sequential testing |[Презентация "Marketing — Email vs Push-коммуникации"](https://github.com/SVNasonkova/portfolio_ab_testing/blob/4d18901977a6c1d7a9eaa45062527997153b985d/case_2_marketing_channels/presentation.pdf)
3 | [EdTech: Персонализация карусели курсов](https://github.com/SVNasonkova/portfolio_ab_testing/tree/main/case_3_edtech-ab-test) | EdTech / Online Education | Аналитический кейс по проектированию A/B-теста персонализированной карусели курсов «Вам понравится». Проведён полный EDA логов пользовательских событий, анализ воронки, выявлены ограничения данных и обоснована невозможность проведения корректного A/B-теста. На основе данных разработан дизайн эксперимента: выбор метрик, расчёт MDE, ограничения по трафику и длительности, допущения. | Product analytics, Funnel analysis, Event logs, Ratio-metrics, Delta method, MDE calculation, Experiment design under data constraints | [Презентация "EdTech — Почему не каждый A/B-тест стоит запускать"](https://github.com/SVNasonkova/portfolio_ab_testing/blob/b74cddee5805ed3d8e88e6ef3ae289e71fe61f3c/case_3_edtech-ab-test/EdTech.pdf)
