<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=F72585&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Khairunnisa+Maharani+%F0%9F%91%8B;Data+Engineer+%F0%9F%8F%97%EF%B8%8F;Pipeline+Builder+%F0%9F%94%A7;Local-First+Tool+Maker+%F0%9F%A6%86" alt="Typing SVG" />

### 🏗️ Data Engineer · Building Production-Ready Data Platforms
**Data Science Student @ ITERA · Indonesia**

*I design and build scalable, reliable data systems — from real-time streaming pipelines*
*to batch lakehouse architectures. My focus is on production engineering practices:*
*idempotent pipelines, data quality enforcement, fault tolerance, and reproducibility.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khairunnisa-maharani)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KMoex-HZ)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

![Visitor Count](https://komarev.com/ghpvc/?username=KMoex-HZ&color=F72585&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🔥 Currently

- 🚧 **Building:** Improving [MALLARD](https://github.com/KMoex-HZ/mallard) — adding smart column profiling & export pipelines
- 📚 **Learning:** Advanced Spark internals, Delta Lake, and data contract patterns
- 🎯 **Goal:** Land a Data Engineering role where I can own production pipelines end-to-end
- 🏆 **Recent Win:** ROC-AUC 0.9801 at IDSC 2026 Glaucoma Detection competition

---

## 🛠️ Core Engineering Stack

**Orchestration & Infrastructure**

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/-Apache_Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Dagster](https://img.shields.io/badge/-Dagster-232F3E?style=flat&logo=dagster&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**Data Processing**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Apache Spark](https://img.shields.io/badge/-Apache_Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)

**Streaming**

![Apache Kafka](https://img.shields.io/badge/-Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)

**Storage & Warehouse**

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MinIO](https://img.shields.io/badge/-MinIO-008D10?style=flat&logo=minio&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL_Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)

**Data Quality & Observability**

![Great Expectations](https://img.shields.io/badge/-Great_Expectations-FF6347?style=flat&logoColor=white)
![Soda Core](https://img.shields.io/badge/-Soda_Core-FF6347?style=flat&logoColor=white)

---

## 🚀 Featured Data Engineering Projects

### 🛒 [GlowCart — Production-Inspired E-commerce Data Platform](https://github.com/KMoex-HZ/glowcart)

![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

> Production-oriented data platform simulating real-world e-commerce analytics with streaming ingestion and robust failure handling.

| Component | Implementation |
| :--- | :--- |
| **Architecture** | Kafka + Medallion (Bronze → Silver → Gold) |
| **Reliability** | Dead Letter Queue + idempotent pipelines |
| **Data Quality** | Validation gates at Silver layer |
| **Orchestration** | Airflow DAGs with failure handling |
| **Serving** | FastAPI + DuckDB zero-ETL endpoints |
| **Docs** | Architecture Decision Records (ADR) |

---

### 🦆 [MALLARD — Local Data Warehouse & Refiner](https://github.com/KMoex-HZ/mallard)

![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)

> 100% local, zero-server data tool — drop CSV, Excel, Parquet, or JSON and let DuckDB handle the rest. No cloud, no API keys, no setup.

- 🧹 **Auto Deep Clean** — deduplication, type healing, wide-to-long pivot detection
- 📊 **Analytics Explorer** — Histogram, Bar, Scatter, Line, Box, Correlation Heatmap
- 🖥️ **Custom SQL** — run any DuckDB query directly against ingested tables
- 📦 **Standalone `.exe`** — distributable to Windows users with zero Python setup

---

### 🛍️ [Modern Data Platform — Automated ELT with CI/CD](https://github.com/KMoex-HZ/modern-data-platform-dagster)

![Dagster](https://img.shields.io/badge/-Dagster-232F3E?style=flat&logo=dagster&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Soda](https://img.shields.io/badge/-Soda_Core-FF6347?style=flat&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

![CI/CD](https://github.com/KMoex-HZ/modern-data-platform-dagster/actions/workflows/ci_cd.yml/badge.svg)

> Modern data stack (MDS) with strong data contracts and full pipeline automation.

- **SCD Type 2** for historical change tracking
- Fully automated **CI/CD** with testing & validation on every push
- **Data quality checks** as deployment gates via Soda Core

---

### 🚖 [NYC Taxi Data Pipeline](https://github.com/KMoex-HZ/nyc-taxi-pipeline-spark-airflow)

![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white)
![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![MinIO](https://img.shields.io/badge/-MinIO-008D10?style=flat&logo=minio&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)

> End-to-end distributed pipeline processing millions of records with automated data validation.

- Processed **2.9M+ records** using distributed Spark clusters
- Simulated **cloud data lake storage** using MinIO (S3-compatible)
- Automated **data validation** with Great Expectations

---

### 🇧🇷 [Olist Data Warehouse](https://github.com/KMoex-HZ/olist-analytics-pipeline)

![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)

- **Star schema** data warehouse for analytics-ready reporting
- Modular dbt transformations with tests and lineage tracking

---

### 🧱 [Market Data Ingestion Pipeline](https://github.com/KMoex-HZ/market-ingestion-pipeline)

![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)

- **Fault-tolerant ETL** for real-time market data ingestion
- Retry logic, scheduling, and containerized deployment

---

### 🏫 [LPMPP Institutional Data Warehouse](https://github.com/KMoex-HZ/LPMPP-Data-Warehouse-Project)

![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![SSIS](https://img.shields.io/badge/-SSIS-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)

- **Role:** Principal Data Engineer & Team Lead
- Dimensional modeling + cloud ETL pipelines on Azure

---

## 🧠 Additional Experience

### 👁️ [Glaucoma Detection — ML Pipeline (IDSC 2026)](https://github.com/KMoex-HZ/IDSC2026-Mathematics-for-Hope-Glaucoma)

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![DVC](https://img.shields.io/badge/-DVC-945DD6?style=flat&logo=dvc&logoColor=white)

- Fully reproducible ML pipeline with Docker + DVC + fixed seeds
- Achieved **ROC-AUC 0.9801** on blind test set

> Primary focus is **Data Engineering & platform reliability** — ML projects demonstrate systems thinking applied to the full model lifecycle.

---

## 📊 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=KMoex-HZ&show_icons=true&theme=radical&hide_border=true&count_private=true&hide_rank=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=KMoex-HZ&theme=radical&hide_border=true)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=KMoex-HZ&theme=redical&hide_border=true&area=true)

</div>

---

<div align="center">

### 🐍 Watch the snake eat my contributions!

![Snake animation](https://raw.githubusercontent.com/KMoex-HZ/KMoex-HZ/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 🤝 Let's Connect

<div align="center">

Got a pipeline to build, a platform to scale, or just want to talk data engineering?

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khairunnisa-maharani)
[![Email](https://img.shields.io/badge/Email-Say_Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KMoex-HZ)

*Open to internship & junior Data Engineering roles · Remote friendly*

</div>
