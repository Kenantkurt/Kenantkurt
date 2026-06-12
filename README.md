# 👋 Hi, I'm Kenan Kurt

**Data Engineer** | Building end-to-end ELT pipelines | Python • SQL • BigQuery • dbt • Apache Airflow • Docker

🎯 I build end-to-end **ELT pipelines**, design **analytics data warehouses**, and optimize **data transformations** using **Apache Airflow, dbt, and BigQuery**. I bring a strong analytics background (Power BI, SQL) and keep deepening my data engineering skills through hands-on projects and the **DataTalks.Club Data Engineering Zoomcamp**.

---

## 🎯 About Me

I'm a **Data Engineer** with a strong analytics background, building real-world data infrastructure projects. My focus is on **end-to-end ELT pipelines**, **dbt transformations**, and **cloud data warehouses** (BigQuery, PostgreSQL). I believe in writing clean, tested, and documented code—and I practice this in every project.

**Current Location:** Utrecht, Netherlands  
**Learning:** DataTalks.Club Data Engineering Zoomcamp (in progress)

---

## 🛠️ Tech Stack

### **Core Data Engineering**
- **Languages:** Python 3.11, SQL (BigQuery, PostgreSQL)
- **Transformation:** dbt (dbt-BigQuery), SQL for analytics
- **Orchestration:** Apache Airflow 2.9+
- **Cloud Warehousing:** Google BigQuery, PostgreSQL
- **Storage:** Parquet, Google Cloud Storage (GCS)
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

### **3. Data Engineering Practice Solutions**
**Technologies:** Python | SQL | dbt | Docker | Pandas

Step-by-step solutions to the **data-engineering-practice** exercises (Daniel Beach's course).

**Coverage:**
- ✅ File I/O & data ingestion (Python)
- ✅ Web scraping & API integration
- ✅ AWS S3 & cloud storage basics
- ✅ JSON/CSV transformations
- ✅ SQL joins & aggregations
- ✅ Data modeling for Postgres
- ✅ PySpark fundamentals
- ✅ DuckDB for analytics
- ✅ Polars lazy computation
- ✅ Data quality with Great Expectations

👉 [View Repository](https://github.com/Kenantkurt/data-engineering-practice-solutions)

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

Currently working through **DataTalks.Club Data Engineering Zoomcamp** modules:

- ✅ Module 1: Docker & GCP setup
- ✅ Module 2: dbt fundamentals
- ✅ Module 3: BigQuery & data warehousing
- 🔄 Module 4: Orchestration with Airflow (in progress)
- 🔄 Currently going deeper into **PySpark, Databricks (Delta Lake), and CI/CD** for data pipelines

---

## 🎓 Skills Summary

| Skill | Proficiency | Evidence |
|-------|-------------|----------|
| **Python** | Intermediate+ | Ingestion scripts, API integration, data transformation |
| **SQL** | Advanced | Complex joins, window functions, query optimization |
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
2. `bigquery-taxi-data-warehouse` — Data warehouse design & optimization
3. `gz-dbt-repository` — dbt project examples
4. `sql-financial-analytics-pipeline` — Advanced SQL transformations

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

**Last Updated:** May 2, 2026  
**Status:** Actively learning & building 🚀
