# Khairunnisa Maharani

### Data Engineer | Building Production-Ready Data Platforms
**Data Science Student @ ITERA**

I design and build scalable, reliable data systems — from real-time streaming pipelines to batch lakehouse architectures. My focus is on production engineering practices: idempotent pipelines, data quality enforcement, fault tolerance, and reproducibility.

---

## 🛠️ Core Engineering Stack

| Domain | Technologies |
| :--- | :--- |
| **Orchestration & Infrastructure** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Airflow](https://img.shields.io/badge/-Apache_Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white) ![Dagster](https://img.shields.io/badge/-Dagster-232F3E?style=flat&logo=dagster&logoColor=white) |
| **Data Processing** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Spark](https://img.shields.io/badge/-Apache_Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black) |
| **Streaming** | ![Kafka](https://img.shields.io/badge/-Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white) |
| **Storage & Warehouse** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![MinIO](https://img.shields.io/badge/-MinIO-008D10?style=flat&logo=minio&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white) |
| **Data Quality & Observability** | ![Great Expectations](https://img.shields.io/badge/-Great_Expectations-FF6347?style=flat&logoColor=white) ![Soda](https://img.shields.io/badge/-Soda_Core-FF6347?style=flat&logoColor=white) |
| **Other** | ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |

---

## 🚀 Featured Data Engineering Projects

### 🛒 [GlowCart — Production-Inspired E-commerce Data Platform](https://github.com/KMoex-HZ/glowcart)
*Kafka · Spark · dbt · Airflow · FastAPI · DuckDB · Docker*

Designed and implemented a **production-oriented data platform** simulating real-world e-commerce analytics with streaming ingestion and robust failure handling.

- **Architecture:** Real-time pipeline using **Kafka + Medallion Architecture (Bronze → Silver → Gold)**
- **Reliability:** Implemented **Dead Letter Queue (DLQ)** and **idempotent pipelines** (safe retries, zero duplication)
- **Data Quality:** Enforced **validation gates at the Silver layer** before downstream processing
- **Orchestration:** Managed workflows using **Airflow DAGs with failure handling**
- **Serving Layer:** FastAPI + DuckDB for **zero-ETL analytics endpoints** (revenue, funnel, traffic, top products)
- **Engineering Practice:** Documented all major decisions using **Architecture Decision Records (ADR)**

---

### 🛍️ [Modern Data Platform — Automated ELT with CI/CD](https://github.com/KMoex-HZ/modern-data-platform-dagster)
*Dagster · dbt Core · DuckDB · Soda Core · GitHub Actions*

![CI/CD](https://github.com/KMoex-HZ/modern-data-platform-dagster/actions/workflows/ci_cd.yml/badge.svg)

Built a **modern data stack (MDS)** with strong data contracts and full automation.

- Implemented **SCD Type 2** for historical change tracking
- Fully automated **CI/CD pipeline** with testing & validation on every push
- Enforced **data quality checks** as deployment gates via Soda Core

---

### 🚖 [NYC Taxi Data Pipeline](https://github.com/KMoex-HZ/nyc-taxi-pipeline-spark-airflow)
*Apache Spark · Apache Airflow · MinIO · PostgreSQL · Great Expectations*

- Processed **2.9M+ records** using distributed Spark clusters
- Built an **end-to-end pipeline** with automated data validation
- Simulated **cloud data lake storage using MinIO (S3-compatible)**

---

### 🇧🇷 [Olist Data Warehouse](https://github.com/KMoex-HZ/olist-analytics-pipeline)
*dbt Core · PostgreSQL · Docker*

- Designed a **star schema data warehouse** for analytics-ready reporting
- Built modular transformations with **dbt**, including tests and lineage tracking

---

### 🧱 [Market Data Ingestion Pipeline](https://github.com/KMoex-HZ/market-ingestion-pipeline)
*Apache Airflow · Docker · PostgreSQL · Python*

- Developed a **fault-tolerant ETL pipeline** for real-time market data ingestion
- Implemented **retry logic, scheduling, and containerized deployment**

---

### 🏫 [LPMPP Institutional Data Warehouse](https://github.com/KMoex-HZ/LPMPP-Data-Warehouse-Project)
*Azure · SSIS · SQL Server*

- **Role:** Principal Data Engineer & Team Lead
- Delivered an institutional warehouse with **dimensional modeling** and cloud ETL pipelines on Azure

---

## 🧠 Additional Experience

### 👁️ [Glaucoma Detection — ML Pipeline (IDSC 2026)](https://github.com/KMoex-HZ/IDSC2026-Mathematics-for-Hope-Glaucoma)
*PyTorch · EfficientNet · Docker · DVC*

- Built a fully reproducible ML pipeline with **Docker + DVC + fixed seeds**
- Achieved **ROC-AUC 0.9801** on blind test set with quality-aware loss engineering

> Primary focus is **Data Engineering & platform reliability** — ML projects demonstrate systems thinking applied to the full model lifecycle.

---

## 📊 GitHub Analytics

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KMoex-HZ&theme=radical&hide_border=true" height="150" />
</p>
