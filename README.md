# 👋 Hi, I'm Kenan Kurt

**Data Engineer** | Building end-to-end ELT pipelines | Python • SQL • PySpark • Databricks • dbt • Airflow • Docker

🎯 I build end-to-end **ELT pipelines**, design **analytics data warehouses**, and clean and transform data at scale with **PySpark on Databricks**. I bring a strong analytics background (SQL, Power BI) and keep deepening my data engineering skills through hands-on projects — currently focused on **PySpark, Delta Lake, and CI/CD**.

---

## 🎯 About Me

I'm a **Data Engineer** with a strong analytics background, building real-world data infrastructure projects. My focus is on **end-to-end ELT pipelines**, **dbt transformations**, and **cloud data warehouses** (BigQuery, PostgreSQL). I believe in writing clean, tested, and documented code—and I practice this in every project.

**Current Location:** Utrecht, Netherlands  
**Learning now:** PySpark & Databricks (hands-on Bronze→Silver cleaning projects) → CI/CD → next big build: an end-to-end lakehouse pipeline (Databricks + Delta Lake + dbt + Airflow + AWS)

---

## 🛠️ Tech Stack

### **Core Data Engineering**
- **Languages:** Python 3.11, SQL (Spark SQL, BigQuery, PostgreSQL)
- **Processing:** PySpark (DataFrame API), Databricks, Delta Lake (medallion architecture)
- **Transformation:** dbt (dbt-BigQuery), SQL for analytics
- **Orchestration:** Apache Airflow 2.9+
- **Cloud Warehousing:** Google BigQuery, PostgreSQL
- **Storage:** Parquet, Delta, Google Cloud Storage (GCS)
- **Containerization:** Docker, Docker Compose

### **Data Formats & APIs**
- Parquet, CSV, JSON
- REST APIs (Python Requests)
- Open-Meteo API (weather data enrichment)

### **Other Tools**
- Git & GitHub (version control, CI/CD)
- Linux / Bash scripting
- Jupyter Notebooks (EDA & prototyping)

---

## 🚀 Highlighted Projects

### **1. End-to-End Flight Delay Pipeline** ⭐
**Technologies:** Airflow 2.9 | dbt | BigQuery | PostgreSQL | Python | Docker

A complete **ELT analytics pipeline** for U.S. domestic flight delays using real data from BTS (Bureau of Transportation Statistics).

**What I Built:**
- ✅ Python ingestion scripts (Parquet generation, API enrichment, data cleaning)
- ✅ PostgreSQL staging (local data landing zone)
- ✅ BigQuery transformation (dbt: 5 staging + 5 mart models)
- ✅ Apache Airflow orchestration (daily @ 9 AM UTC)
- ✅ Data quality layer (15+ dbt tests: unique, not_null, accepted_range, composite keys)
- ✅ BI dashboard with 4 analytical views

**Key Metrics:**
- **Dataset size:** 2-3 GB/month, 20M+ flight records analyzed
- **Pipeline runtime:** ~15 minutes
- **Query optimization:** Leveraged BigQuery partitioning & clustering

**Key Findings:**
- Identified airport-level inefficiencies as primary delay driver (stronger than weather/holidays)
- Applied BigQuery partitioning & clustering to reduce query scan costs
- Weather moderately affects delays; holiday periods show stable scheduling

👉 [View Repository](https://github.com/Kenantkurt/end-to-end-flight-delay-pipeline)

---

### **2. BigQuery Taxi Data Warehouse**
**Technologies:** BigQuery | GCS | SQL

Hands-on project comparing **3 table strategies** for NYC Yellow Taxi data (20M+ trips, Jan–Jun 2024).

**What I Learned:**
- External tables vs. regular tables (storage vs. query trade-offs)
- Columnar storage impact on query costs
- Partitioning effectiveness: 12x cost reduction on filtered queries
- When to use clustering with partitions

**Results:**
- Same query on non-partitioned table: **310 MB** scanned
- Same query on partitioned table: **26 MB** scanned
- Practical demonstration of BigQuery optimization

👉 [View Repository](https://github.com/Kenantkurt/bigquery-taxi-data-warehouse)

---

### **3. Databricks PySpark Data Cleaning** 🔥
**Technologies:** PySpark | Databricks | Delta Lake | Spark SQL

Six hands-on **Bronze → Silver cleaning pipelines** on Databricks, following the medallion architecture. Practice projects — each one a full raw-to-clean pass on a different messy dataset (e-commerce orders, cafe sales, Netflix titles, gym sessions, raw event logs, IoT device events).

**Techniques covered:**
- ✅ Schema-on-read (StructType / DDL), clean-then-cast, `try_*` + `coalesce` for mixed formats
- ✅ Parsing raw unstructured logs with `regexp_extract` (chose regex over an LLM for determinism)
- ✅ Timezone normalization (CET → UTC), complex types (`struct` / `array` / `map`, `withField`)
- ✅ Grain-aware deduplication, null vs. invalid-value policies, idempotent Delta writes

👉 [View Repository](https://github.com/Kenantkurt/databricks-pyspark-data-cleaning)

---

## 📊 What I Focus On

- **ELT/ETL Pipelines:** From raw data to production-ready analytics
- **dbt Best Practices:** Staging layers, mart models, comprehensive testing
- **SQL Performance:** Query optimization, BigQuery partitioning/clustering
- **Data Quality:** dbt tests, schema validation, anomaly detection
- **Orchestration:** Airflow DAG design, error handling, monitoring
- **Docker:** Local reproducibility, image optimization
- **Code Quality:** Clean SQL/Python, documentation, version control

---

## 📚 Learning Path

- ✅ **DataTalks.Club Data Engineering Zoomcamp** — Docker, dbt, BigQuery, Airflow fundamentals
- 🔄 **PySpark & Databricks** — Spark programming course + 6 published hands-on cleaning projects
- ⏭️ **CI/CD for data pipelines** — GitHub Actions, pre-commit, detect-secrets
- ⏭️ **Flagship project:** end-to-end lakehouse pipeline (Databricks + Delta Lake + dbt + Airflow + AWS S3)
- 🎯 **Target certification:** Databricks Certified Data Engineer Associate

---

## 🎓 Skills Summary

| Skill | Proficiency | Evidence |
|-------|-------------|----------|
| **Python** | Intermediate+ | Ingestion scripts, API integration, data transformation |
| **SQL** | Advanced | Complex joins, window functions, query optimization |
| **PySpark** | Intermediate | 6 Bronze→Silver cleaning projects on Databricks (DataFrame API + Spark SQL) |
| **Databricks / Delta Lake** | Intermediate | Medallion architecture, Delta tables, idempotent writes, notebooks |
| **dbt** | Intermediate+ | 10+ production models, comprehensive tests, staging/mart patterns |
| **BigQuery** | Intermediate+ | External/regular/partitioned tables, cost optimization, real data at scale |
| **Apache Airflow** | Intermediate | DAG design, error handling, email alerts, daily orchestration |
| **Docker** | Intermediate | Docker Compose, multi-container setups, local dev environments |
| **PostgreSQL** | Intermediate | Schema design, indexing, data loading pipelines |
| **Git** | Intermediate | Version control, branching, commit hygiene |

---

## 🔗 Featured Work

**Best for:** Data engineering interviews, portfolio reviews, hiring managers

📌 **Pinned Repositories:**
1. `end-to-end-flight-delay-pipeline` — End-to-end ELT pipeline (Airflow + dbt + BigQuery)
2. `databricks-pyspark-data-cleaning` — PySpark Bronze→Silver cleaning on Databricks (6 projects)
3. `bigquery-taxi-data-warehouse` — Data warehouse design & optimization
4. `gz-dbt-repository` — dbt analytics pipeline (staging + marts + tests)
5. `sql-financial-analytics-pipeline` — Advanced SQL transformations
6. `sql-order-analytics` — Window functions & analytical SQL

---

## 💡 What Makes My Work Stand Out

✅ **Real-world projects** — Not toy datasets. Real data, real pipelines, real trade-offs.  
✅ **Data quality-first** — Every pipeline includes comprehensive testing.  
✅ **Clear documentation** — READMEs that explain the "why," not just the "what."  
✅ **Optimization mindset** — BigQuery cost reduction, SQL efficiency, Airflow reliability.  
✅ **Learning in public** — Active in DataTalks.Club community, documenting learnings.

---

## 📧 Get In Touch

💼 **LinkedIn:** [kenan-tufan-k-263000308](https://www.linkedin.com/in/kenan-tufan-k-263000308/)  
📬 **Email:** [kenantkurt@gmail.com](mailto:kenantkurt@gmail.com)  
🐙 **GitHub:** [@Kenantkurt](https://github.com/Kenantkurt)  
📍 **Location:** Utrecht, Netherlands

---

## 🎯 Open To

- 💼 **Data Engineering roles:** Junior to mid-level
- 🤝 **Collaborations:** Open-source data projects, learning groups
- 💬 **Discussions:** Data pipelines, dbt best practices, SQL optimization

**Let's talk data!** Feel free to reach out on LinkedIn or email. I'm always eager to discuss data infrastructure, ask questions, and collaborate on interesting problems.

---

**Last Updated:** July 6, 2026  
**Status:** Actively learning & building 🚀
