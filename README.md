# Khairunnisa Maharani

### Data Science Student @ ITERA | Building Scalable Data & ML Pipelines

Passionate about building robust, containerized data infrastructure and exploring machine learning workflows. Currently focusing on applying clean architecture, reproducibility, and scalability across data ecosystems.

---

### 🛠️ Core Engineering Stack

| Domain | Technologies |
| :--- | :--- |
| **Orchestration & Containerization** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Airflow](https://img.shields.io/badge/-Apache_Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white) ![Dagster](https://img.shields.io/badge/-Dagster-232F3E?style=flat&logo=dagster&logoColor=white) |
| **Data Processing & ML** | ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Spark](https://img.shields.io/badge/-Apache_Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| **Storage, Warehouse & Cloud** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white) ![MinIO](https://img.shields.io/badge/-MinIO-008D10?style=flat&logo=minio&logoColor=white) |
| **Data Quality & Web** | ![Great Expectations](https://img.shields.io/badge/-Great_Expectations-FF6347?style=flat&logo=data&logoColor=white) ![Soda](https://img.shields.io/badge/-Soda_Core-FF6347?style=flat&logo=data&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.dot-js&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white) |

---

### 🚀 Featured Engineering Projects

#### 👁️ [Quality-Aware Glaucoma Detection (IDSC 2026)](https://github.com/KMoex-HZ/IDSC2026-Mathematics-for-Hope-Glaucoma)
> *PyTorch | EfficientNet | Medical Imaging | Docker | DVC*

* **Architecture:** Designed a **clinically-aligned deep learning pipeline** for glaucoma detection using EfficientNet with **quality-aware loss engineering** and strict **patient-level data partitioning (zero leakage)**.
* **Key Engineering:** Implemented **custom WeightedQualityBCE loss**, CLAHE-based preprocessing in LAB color space, and full **experiment reproducibility using Docker + DVC + fixed seeds**.
* **Impact:** Achieved **ROC-AUC 0.9801** on blind test set, exceeding benchmarks in fundus-based screening literature.
* **MLOps Mindset:** End-to-end reproducible ML pipeline with **Grad-CAM interpretability for clinical validation**.

---

#### 🛒 [GlowCart — Real-Time E-commerce Data Platform](https://github.com/KMoex-HZ/glowcart)
> *Kafka | Spark | dbt | Airflow | FastAPI | DuckDB | Docker*

* **Architecture:** Engineered a **real-time lakehouse data platform** using **Medallion Architecture (Bronze → Silver → Gold)** with Kafka-based streaming ingestion.
* **Data Flow:** Streaming events → Kafka → Parquet storage → PySpark transformations → dbt models → FastAPI analytics layer → BI dashboard.
* **Key Engineering:** Implemented **event-driven pipeline (10,000+ simulated events)**, distributed processing with Spark, and **modular SQL transformations with dbt including automated data quality tests**.
* **Orchestration:** Designed an **Airflow DAG (6-task pipeline)** for scheduled execution and monitoring.
* **Serving Layer:** Built analytics API with FastAPI + DuckDB powering real-time endpoints (revenue, funnel, traffic, top products).
* **Impact:** Simulates a **production-grade Indonesian e-commerce analytics system** with full-stack ownership from ingestion to dashboard.

---

#### 🛍️ [Modern Data Platform: Automated ELT with CI/CD](https://github.com/KMoex-HZ/modern-data-platform-dagster)
> *Dagster | dbt Core | DuckDB | Soda Core | GitHub Actions*
![CI/CD Pipeline](https://github.com/KMoex-HZ/modern-data-platform-dagster/actions/workflows/ci_cd.yml/badge.svg)

* **Architecture:** Built a production-grade **Modern Data Stack (MDS)** with SCD Type 2 history tracking and strict data contracts.
* **Key Engineering:** Fully automated CI/CD pipeline, modular transformations, and data quality enforcement.

---

#### 🚖 [NYC Taxi End-to-End Data Pipeline](https://github.com/KMoex-HZ/nyc-taxi-pipeline-spark-airflow)
> *Apache Spark | Apache Airflow | MinIO | PostgreSQL | Great Expectations*

* **Architecture:** Engineered a scalable pipeline processing **2.9M+ records** using distributed Spark clusters.
* **Key Engineering:** Integrated automated data validation and lakehouse ingestion flow.

---

#### 🇧🇷 [Olist E-Commerce Data Warehouse](https://github.com/KMoex-HZ/olist-analytics-pipeline)
> *dbt Core | PostgreSQL | Docker*

* **Architecture:** Developed a Star Schema warehouse for analytics-ready reporting.
* **Key Engineering:** Modular transformations with dbt, including testing and lineage.

---

#### 🧱 [Automated Market Data Ingestion Pipeline](https://github.com/KMoex-HZ/market-ingestion-pipeline)
> *Docker | Apache Airflow | PostgreSQL | Python*

* **Architecture:** Built a fault-tolerant ETL system for real-time ingestion.
* **Key Engineering:** Custom DAGs with retry logic and containerized deployment.

---

#### 🏫 [LPMPP Institutional Data Warehouse](https://github.com/KMoex-HZ/LPMPP-Data-Warehouse-Project)
> *Azure | SSIS | SQL Server*

* **Role:** Principal Data Engineer & Team Lead  
* **Impact:** Delivered institutional warehouse with dimensional modeling and cloud ETL pipelines.

---

### 📊 GitHub Analytics

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=KMoex-HZ&theme=radical&hide_border=true" height="150" />
</p>
