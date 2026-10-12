## 🚀 Featured Projects

### [👟 Sneaker Data Lakehouse | End-to-End Analytics Platform](https://github.com/mihail-grigorev/sneaker-data-lakehouse)
> **Data Engineering • Medallion Architecture • Batch Processing**

Масштабируемый Data Lakehouse для e-commerce ритейла кроссовок с полным циклом обработки данных: от сырых событий до витрин метрик в хранилище.

* **Архитектура (Medallion Architecture):**
  * **Bronze:** Ingestion потока транзакций (JSON) в распределенное S3-совместимое объектное хранилище.
  * **Silver:** Дедупликация, валидация строгих контрактов данных, очистка аномалий и партиционирование в колоночный формат **Parquet** через **Apache Spark**.
  * **Gold & Datamart:** Агрегация бизнес-метрик (GMV, net revenue, retention/return rate, средний чек по брендам и каналам сбыта) с репликацией в аналитический витринный слой **PostgreSQL**.
* **Оркестрация & Data Quality:** Пайплайн автоматизирован в **Apache Airflow** с внедрением Quality Gates — автоматической валидацией целостности и наличия партиций перед пересчетом витрин.
* **Стек:** `Python`, `Apache Airflow`, `Apache Spark (PySpark)`, `PostgreSQL`, `S3 API (Garage Rust S3)`, `Docker & Compose`.

---

### [💳 Enterprise Financial Transactions & Fraud Platform](https://github.com/mihail-grigorev)
> **Data Infrastructure • Real-time Streaming • Analytical Warehousing**

Симуляция отказоустойчивой банковской платформы для потоковой обработки транзакций, начисления кэшбэка и агрегации аналитики.

* **Потоковая и пакетная обработка:** Прием транзакционных сообщений через распределенную шину **Apache Kafka** с последующей batch-обработкой и валидацией в **PySpark**.
* **DWH & Витрины:** Моделирование многослойного корпоративного хранилища данных с разделением на аналитические движки (**ClickHouse** для OLAP real-time аналитики и **Greenplum** для сложных распределенных срезов).
* **Трансформация:** Версионирование, тестирование и документирование пайплайнов трансформации данных с помощью **dbt**.
* **Стек:** `Apache Kafka`, `PySpark`, `ClickHouse`, `Greenplum`, `dbt`, `PostgreSQL`, `Docker`.

---

### [🔍 Entity Resolution & Customer Identity Matching](https://github.com/mihail-grigorev)
> **Data Quality • NLP Matching • Business Process Automation**

ETL-конвейер дедупликации и слияния разнородных клиентских профилей из разрозненных источников с высоким уровнем шума.

* **Алгоритмы слияния:** Реализация гибридного матчинга строк на базе расстояния Дамерау-Левенштейна и Джаро-Винклера с предварительной нормализацией через Unicode NFKC и фонетические эвристики.
* **Интеграция процессов:** Моделирование логики маршрутизации, ручной валидации пограничных совпадений и обогащения данных через диаграммы **Camunda BPMN**.
* **Стек:** `Python`, `MySQL`, `String Metrics`, `Camunda BPMN`, `ETL Pipelines`.
