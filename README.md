# Hi, I'm Mihail 👋
### Backend Engineer → Data Engineer

> 🟢 **Open to Data Engineer / Analytics Engineer roles** · [CITY / Remote] · English: [LEVEL] · [email@example.com] · [Telegram @username]

Backend developer with production experience in asynchronous microservices, REST APIs and database-heavy systems, now building end-to-end analytical pipelines: **Airflow → Spark → S3 data lake → PostgreSQL DWH**, all containerized and idempotent.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

**Working knowledge:** Parquet, S3 API (boto3 / S3A), medallion architecture (Bronze/Silver/Gold), window functions, `EXPLAIN ANALYZE`, pytest
**Learning next:** dbt, ClickHouse, Kafka

---

## ⭐ Featured Project — Sneaker Data Lakehouse (Data Engineering)

**[sneaker-data-lakehouse](https://github.com/mihail-grigorev/sneaker-data-lakehouse)** · `Airflow` `PySpark` `S3 (object storage)` `PostgreSQL` `Docker Compose`

End-to-end batch ETL for a sneaker store: raw order events → cleaned analytics → a datamart ready for BI.

![Pipeline architecture](docs/diagram_1.png)

- **Medallion lakehouse:** raw JSON (Bronze) → validated Parquet partitioned by date (Silver) → aggregated metrics (Gold).
- **Orchestration:** Airflow DAG with retries, failure callback and a **data-quality gate** between Silver and Gold.
- **Idempotent by design:** re-running a date overwrites its Silver partition and replaces its datamart rows, with no duplicates (composite primary key in PostgreSQL).
- **Metrics:** revenue, refunds, return rate and average ticket per brand / channel / day.
- **One command to run:** `docker compose up -d --build`, with the whole stack reproducible locally.

**Result:** [ADD ONE LINE WITH NUMBERS, e.g. "300 events/day × N days → X metric rows; full run in ~Y min"]

---

## 💻 Other Projects

| Project | What it shows | Stack | Status |
|---|---|---|---|
| 🔹 **[Async High-Throughput Web Services](LINK)** | Production microservices, schema design, indexes, `EXPLAIN ANALYZE` tuning, multi-stage Docker | FastAPI · AsyncIO · Pydantic · PostgreSQL | ✅ Production |
| 🔹 **[Entity Resolution & Data Cleaning](LINK)** | Fuzzy matching and deduplication across relational DBs (Damerau-Levenshtein, Jaro-Winkler) | Python · SQL | ✅ Production |
| 🔹 **[Telegram Processing Platform](LINK)** | Event-driven bots, payment webhooks, async workers, Redis caching | aiogram · AsyncIO · Redis | ✅ Production |

> Replace every `LINK` with the real repository URL. At the moment all three links point to the same README anchor.

For each project add 1 line of impact if you can state it truthfully, e.g. "deduplicated N records, reduced duplicates by X%".

---

## 🎯 Data Engineering Roadmap

- [x] SQL & relational theory: window functions, indexes, query tuning
- [x] Orchestration: Apache Airflow DAGs
- [x] Distributed processing: PySpark batch jobs
- [x] Data lake & medallion architecture on S3-compatible storage
- [ ] DWH modeling: Kimball star schema, staging layer, Data Vault basics
- [ ] Transformations: dbt
- [ ] Analytical engines: ClickHouse / Greenplum
- [ ] Streaming: Apache Kafka

---

## 💡 What My Backend Background Brings to Data

- **Engineered code, not scripts:** modular, typed Python with tests.
- **Deep database awareness:** transactions, locking, connection pooling, schema design.
- **Reliability mindset:** idempotent retries, failure alerts, reproducible Docker environments.

---

## 📬 Contact

[email@example.com](mailto:mihailgrigorev223@yandex.ru) · [Telegram](https://t.me/grigoriev-mihail) ·
