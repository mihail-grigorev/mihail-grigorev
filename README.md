# Hi there, I'm Mikhail 👋

### **Data Engineer** *(with a solid Backend Engineering background)*

I build resilient, distributed data pipelines and analytical storage systems. Having transitioned from backend development, I treat data pipelines as production-grade software: emphasizing clean architecture, rigorous data modeling, ACID guarantees, idempotency, and automated testing.

---

### 💼 Technical Expertise

- **Data Processing & Orchestration:** Apache Airflow, Apache Spark (PySpark), dbt, Streaming ETL / ELT
- **Databases & DWH:** PostgreSQL, ClickHouse, Greenplum, MySQL, Redis
- **Streaming & Messaging:** Apache Kafka
- **Backend & Core:** Python (FastAPI, Asyncio), REST APIs, Docker, Docker Compose, Linux
- **Storage & Cloud:** S3 / MinIO, Object Storage patterns
- **Data Engineering Practices:** Kimball Dimensional Modeling, Star/Snowflake schemas, CDC (Change Data Capture), Data Deduplication, Data Quality Checks

---

### 🚀 Featured Projects

#### 🔹 [Fraud Analytics & Financial Transactions Platform](#) *(DWH / Streaming & Batch)*
*Enterprise-grade platform for payment acquiring analytics, cashback distribution, and fraud detection patterns.*
- **Tech Stack:** Apache Kafka, PySpark, Greenplum, ClickHouse, dbt, Apache Airflow, PostgreSQL, Docker
- **Architecture:** 
  - Real-time ingestion via Kafka topic partitions.
  - Streaming aggregation and anomaly detection with PySpark.
  - Multi-layer DWH (Raw / ODS / DDS / Data Marts) in Greenplum & ClickHouse modeled with dbt.
  - End-to-end Airflow DAGs with idempotent staging loads and SLA alerts.

#### 🔹 [Deduplication & Entity Resolution ETL Pipeline](#) *(Data Cleaning & Deduplication)*
*High-throughput pipeline for matching, fuzzy deduplication, and consolidation of unstructured customer data.*
- **Tech Stack:** Python, PostgreSQL, MySQL, S3/MinIO
- **Highlights:** 
  - Implemented phonetic and edit-distance algorithms (Damerau-Levenshtein, Jaro-Winkler) for identity resolution.
  - Batch normalization pipelines handling messy naming and transaction records.

#### 🔹 [Production Backend Services & Event-Driven APIs](#) *(Backend Foundation)*
*Microservices and asynchronous pipelines handling high request volumes.*
- **Tech Stack:** Python, FastAPI, PostgreSQL, Redis, Docker
- **Highlights:** Clean architecture, connection pooling, optimized indexing, MVCC tuning, and robust integration testing.

---

### 📈 What My Backend Background Brings to Data Teams:
1. **Production Code Quality:** I don't write "throwaway notebook scripts" — my ETL code uses strict type hints, modular structure, CI/CD, and unit tests.
2. **Deep Database Internals:** Clear understanding of transaction isolation levels, indexing mechanics (B-tree, GIN/GiST), WAL, and query execution plans (`EXPLAIN ANALYZE`).
3. **Resilience & Idempotency:** Systems designed for failure handling, retry backoff, backpressure management, and exactly-once / at-least-once semantic realities.

---

### 📬 Connect with Me
- **LinkedIn:** [linkedin.com/in/...](#)
- **Telegram:** [@...](#)
- **Email:** `...`
