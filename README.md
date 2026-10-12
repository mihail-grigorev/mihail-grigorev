<h1 align="center">Hi there, I'm Mihail 👋</h1>
<h3 align="center">Data Engineer · Analytics Engineer · Data Analyst</h3>

<p align="center">
  Building reliable data pipelines, warehouses and analytics on top of a strong backend foundation.<br>
  <b>Python · SQL · Airflow · Spark · S3 · PostgreSQL · Docker</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Data%20Engineer%20roles-2ea44f?style=for-the-badge" alt="Open to work">
  <a href="https://github.com/mihail-grigorev"><img src="https://img.shields.io/badge/GitHub-mihail--grigorev-181717?style=for-the-badge&logo=github" alt="GitHub"></a>
</p>

---

## 👤 About

Data Engineer with hands-on experience designing ETL/ELT pipelines, data lakes and analytical datamarts, coming from a production backend background (asynchronous microservices, REST APIs, database-intensive systems).

I apply clean-code architecture, ACID guarantees, query optimization and containerized deployments to analytical pipelines: **idempotent, retry-safe and reproducible**, with data-quality checks built in.

**What I do:** data pipelines & orchestration · data lake / DWH modeling · SQL analytics & metrics · data cleaning & entity resolution · batch processing with Spark

---

## 🛠️ Tech Stack

### 🧱 Data Engineering Core
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Amazon S3](https://img.shields.io/badge/S3%20API-569A31?style=flat-square&logo=amazons3&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white)

### 🗄️ Databases & Warehouses
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Greenplum](https://img.shields.io/badge/Greenplum-00A94F?style=flat-square&logo=greenplum&logoColor=white)

### 🔁 Orchestration & Transformation
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

### 🌊 Big Data & Streaming
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat-square&logo=apachehadoop&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### ⚙️ Infrastructure & Tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### 🧩 Backend Foundation
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?style=flat-square&logo=python&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-26A5E4?style=flat-square&logo=telegram&logoColor=white)

---

## 💻 Projects & Experience

### ⭐ FEATURED · [Sneaker Data Lakehouse](https://github.com/mihail-grigorev/sneaker-data-lakehouse)
`Airflow` `PySpark` `S3` `Parquet` `PostgreSQL` `Docker Compose`

* End-to-end batch ETL with medallion architecture: raw JSON (**Bronze**) → validated Parquet partitioned by date (**Silver**) → aggregated metrics (**Gold**).
* Airflow DAG with retries, failure callbacks and a **data-quality gate** between layers.
* PySpark on S3-compatible object storage; daily brand/channel metrics (revenue, refunds, return rate, average ticket) loaded into a PostgreSQL datamart.
* **Idempotent by design:** partition overwrite, delete-and-insert by date, composite primary key; the whole stack runs with `docker compose up`.

### 🔹 Entity Resolution & Data Cleaning Pipelines · ✅ Production
`Python` `SQL` `Algorithms`

* Built high-performance batch pipelines for fuzzy identity resolution and record deduplication.
* Applied phonetic and edit-distance algorithms (Damerau-Levenshtein, Jaro-Winkler) to consolidate customer and transactional records across relational databases.
* Automated validation rules to keep data consistent between operational stores.

### 🔹 Asynchronous High-Throughput Web Services · ✅ Production
`Python` `FastAPI` `PostgreSQL` `Docker`

* Designed and deployed production microservices (FastAPI, AsyncIO, Pydantic).
* Designed schemas, indexes and transactional boundaries; query optimization with `EXPLAIN ANALYZE`.
* Multi-stage Docker builds and reproducible dev environments.

### 🔹 Automated Bot & Processing Platforms · ✅ Production
`Python` `AsyncIO` `Redis` `aiogram`

* Event-driven Telegram platforms with state management and webhook integrations.
* Payment gateways and media-processing workflows with asynchronous workers and Redis caching.

---

## 🗺️ Roadmap: Data Engineering

> After each block I build a mini-project or task to lock the knowledge in.

| # | Block | Focus | Status |
|:-:|---|---|:-:|
| 1 | **SQL** | Window functions, joins, CTEs · mini-project: SQL cheat sheet | ✅ |
| 2 | **Database theory** | ACID, indexes (B-tree, GIN/GiST), locking · mini-project | ✅ |
| 3 | **Warehouse theory** | Kimball, Star/Snowflake, staging, Data Vault | ✅ |
| 4 | **Greenplum** | MPP, distribution keys, distributed queries | ✅ |
| 5 | **ClickHouse** | Columnar storage, MergeTree, sharding | ✅ |
| 6 | **Python** | Typed, modular, tested code for pipelines | ✅ |
| 7 | **Airflow** | DAGs, retries, quality gates, idempotency | 🔥 In progress |
| 8 | **dbt** | Models, tests, documentation | ⏳ Next |
| 9 | **Spark + Jupyter** | PySpark batch jobs, Parquet | 🔨 Practicing in pet-project |
| 10 | **S3** | Object storage, S3 API, data lake layout | 🔨 Practicing in pet-project |
| 11 | **MinIO** | S3-compatible storage for local lakehouse | 🔨 Practicing in pet-project |
| 12 | **Kafka** | Event streaming, topics, consumers | ⏳ Planned |
| 13 | **GitHub** | Profile, repos, documentation | 🔨 Ongoing |
| 14 | **Hadoop** | HDFS, YARN fundamentals | ⏸ In parallel with pet-project |
| 15 | **Linux** | Shell, processes, networking | ⏸ In parallel with pet-project |

**Legend:** ✅ done · 🔥 current focus · 🔨 hands-on in a project · ⏳ upcoming · ⏸ learned alongside projects

**Next steps:** reach full Airflow proficiency this month; keep Hadoop and Linux for the pet-project instead of studying them in isolation.

---

## 💡 What My Backend Background Brings to Data

* **Engineered code, not scripts:** production-grade modular Python with type annotations, clean OOP/functional patterns and tests.
* **Deep database awareness:** transactions, locking, connection pooling, relational schemas.
* **Reliability mindset:** failure recovery, idempotent retries, reproducible Docker environments.

---

<p align="center">
  📬 <a href="https://github.com/mihail-grigorev">github.com/mihail-grigorev</a>
</p>
