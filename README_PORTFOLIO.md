<div align="center">

# Imed Eddine Safi

### Senior Data Analyst — GCP BigQuery, ML & Document AI

*Building production data platforms on financial & telecom data for 7+ years*

📍 Marseille, France  •  ✉️ [imededdine.safi@gmail.com](mailto:imededdine.safi@gmail.com)  •  💼 [LinkedIn](https://linkedin.com/in/imededdine-safi-31549b88)

</div>

-----

## 👋 About

Data Analyst and Data Engineer with 7+ years of experience designing, industrializing, and migrating data platforms to the cloud. Expert on **Google Cloud Platform** (BigQuery, Document AI, Looker Studio, Cloud Composer), modern **ETL/ELT** (dlt, Airflow, Celery), and production **Machine Learning** (LightGBM, XGBoost, Learn-to-Rank).

Specialized in unifying heterogeneous systems into clean, queryable data warehouses — especially for finance, banking, and telecom use cases. Comfortable owning a project end-to-end: requirements, architecture, delivery, team coordination, and stakeholder communication up to C-level.

-----

## 🚀 Featured Projects

### 🏦 EasyBill ERP — Document AI for Bank Statement Extraction

> Tunisian accounting ERP with a custom **Google Document AI processor fine-tuned on local bank statements** (BIAT, Attijari).

**Measured impact of fine-tuning vs generic Google baseline:**

|Metric       |Generic baseline|Fine-tuned model|Uplift   |
|-------------|----------------|----------------|---------|
|**F1 Score** |0.495           |**0.835**       |**+68%** |
|**Precision**|38.5%           |**83.1%**       |**x2.16**|
|**Recall**   |69.4%           |**84.0%**       |**+21%** |

**Highlights**

- End-to-end bank statement AI extraction: PDF ingestion, OCR, table detection, line-level extraction (date, label, debit, credit, balance), mathematical consistency validation
- Automatic bank reconciliation engine with fuzzy multi-criteria matching and posting suggestion
- ML transaction classifier with incremental pattern learning
- **NCT certification 100/100** across 7 compliance dimensions, validated by a 12-month rolling simulation

**Stack**   Python (FastAPI) · MongoDB · Google Document AI · React · Docker

-----

### 🔄 DataHive — Multi-Destination Data Integration Platform

> Production ELT SaaS platform with **16 warehouse/BI destinations** and **30+ OAuth source connectors**, designed for teams that need centralized data integration.

**Destination catalog**
BigQuery (native) · Snowflake · Redshift · Databricks · ClickHouse · PostgreSQL · MySQL · MSSQL · DuckDB/MotherDuck · Athena · GCS · S3 · Azure Blob · Looker Studio · Power BI · Google Sheets

**Source catalog**
Meta Ads · Google Ads · Google Analytics · Instagram · TikTok · LinkedIn · Snapchat · Pinterest · Salesforce · HubSpot · QuickBooks · Shopify · Stripe · Apple App Store · Google Play Console · and more

**Technical highlights**

- Native **BigQuery destination** with Service Account authentication, dlt[bigquery] loader, multi-region (EU/US) dataset management
- **dlt-powered ELT** pipelines: auto-inferred schemas, incremental loading, merge/upsert, staging
- **Cross-dialect SQL transpilation** with sqlglot — migrate queries between MySQL / PostgreSQL / MSSQL / BigQuery Standard SQL
- Production-grade: JWT auth with tenant isolation, rate-limiting, quota enforcement, audit logs, Sentry APM, Celery Beat orchestration

**Stack**   Django 4.2 · FastAPI · Celery + Redis · PostgreSQL · dlt · sqlglot · Sentry

-----

### 📊 Club Privileges BI — Multi-System Unification & Payment ML

> Real-time BI platform unifying **6 heterogeneous partner systems** (Eklektik, Timwe, DGV, IZI, Ooredoo, SubStore) for a **500,000+ user** loyalty program.

**ML models in production**

*Payment Success Predictor* — LightGBM

- 64,000 training samples, 18 features, handled class imbalance with scale_pos_weight
- Features: per-channel success rate, churn probability, engagement score, lifetime value, subscription age
- AUC-ROC tracking, feature importance, persisted via joblib (production version billing_predictor_v3)

*Merchant Recommender* — Learn-to-Rank

- 111,660 training samples / 27,660 test / 15,399 groups / 28 RFM features
- **NDCG@5 = 1.0 / NDCG@10 = 1.0**

**Business results**

- **+478.8%** subscription growth
- **94%** retention rate
- **500,000+** users tracked
- **15+** real-time KPI dashboards powering C-level decisions

**Stack**   Laravel 10 · MySQL · Python (LightGBM, XGBoost, scikit-learn, SHAP, Optuna) · Chart.js

-----

## 🛠 Technical Skills

|Domain                   |Technologies                                                                                                                                                                                      |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**GCP**                  |BigQuery (Expert), Cloud Storage, Pub/Sub, Dataflow, Cloud Composer, Cloud Functions, Cloud Run, Cloud SQL, Data Catalog, IAM, Cloud DLP, Looker Studio (Expert), Document AI (custom fine-tuning)|
|**Data Engineering**     |dlt, Airflow, Celery + Redis, sqlglot, pandas, NumPy, incremental pipelines, CDC, merge/upsert                                                                                                    |
|**SQL & Databases**      |BigQuery SQL (Expert), PostgreSQL, MySQL, MSSQL, MongoDB, ClickHouse, DuckDB, Snowflake, Redshift, Databricks                                                                                     |
|**Machine Learning**     |LightGBM, XGBoost, scikit-learn, SHAP, Optuna, Learn-to-Rank, scoring models, recommendation systems                                                                                              |
|**AI & Doc Intelligence**|Google Document AI, OCR, Azure OpenAI, LLM providers (OpenAI, Google GenAI, HuggingFace, litellm)                                                                                                 |
|**BI & Dataviz**         |Power BI (Expert), Looker Studio (Expert), Chart.js, Recharts, KPI design, executive reporting                                                                                                    |
|**Languages**            |Python (Expert), SQL (Expert), PHP (Laravel), JavaScript/TypeScript (React, Node.js), Bash                                                                                                        |
|**Cloud & DevOps**       |GCP (Expert), AWS (S3, Athena, Redshift), Azure (ML, OpenAI, Blob), Terraform, Docker, CI/CD, Git, Sentry                                                                                         |

-----

## 💼 Experience

**Senior Data Architect & BI Lead** — BigDeal S.A. · *Jan 2018 – Present*
Leading data & BI strategy: 15+ production BI solutions and data pipelines, cross-database migrations to cloud warehouses, production ML introduction, GDPR-compliant governance, team management up to 8 people, monthly C-level reporting. Reduced Time-to-Insight by -75%.

**Digital Strategy & Web Analytics Consultant** — MediaNet S.A. · *Jan 2015 – Dec 2017*
Advanced Google Analytics deployment, multi-touch attribution modeling, automated digital performance reporting. Improved campaign ROI by +25%.

**SEO & Web Performance Specialist** — Prodexo S.A.R.L · *Jul 2013 – Dec 2014*
Technical SEO audits and optimization of high-traffic platforms. Reduced load times by -60%.

-----

## 🎓 Education & Certifications

**Master’s in AI & Robotics Engineering** — ENSIT, Tunis (2020–2022)
**Bachelor’s in Information Systems Development** — ISET, Tunis (2009–2013)

**Certifications:** HarvardX Data Science · IBM Data Science Tools · IBM Python for Data Science · Microsoft Office Specialist

**Languages:** French (C2) · English (B1) · Arabic (Native)

-----

## 📫 Get in touch

Available for senior **Data Analyst** and **Data Engineering** missions in finance, banking, telecom, or enterprise SaaS. Open to remote/hybrid based in France.

✉️ [imededdine.safi@gmail.com](mailto:imededdine.safi@gmail.com)  ·  💼 [LinkedIn](https://linkedin.com/in/imededdine-safi-31549b88)

-----

<div align="center">
<sub>Source code for the projects above is available on request, under NDA when required.</sub>
</div>
