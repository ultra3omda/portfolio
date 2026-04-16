<div align="center">

# Imed Eddine Safi

### Senior Data Analyst — GCP BigQuery, ML & Document AI

*Building production data platforms on financial & telecom data for 7+ years*

📍 Marseille, France &nbsp;•&nbsp; ✉️ [imededdine.safi@gmail.com](mailto:imededdine.safi@gmail.com) &nbsp;•&nbsp; 💼 [LinkedIn](https://linkedin.com/in/imededdine-safi-31549b88)

</div>

---

## 👋 About

Data Analyst and Data Engineer with 7+ years of experience designing, industrializing, and migrating data platforms to the cloud. Expert on **Google Cloud Platform** (BigQuery, Document AI, Looker Studio, Cloud Composer), modern **ETL/ELT** (dlt, Airflow, Celery), and production **Machine Learning** (LightGBM, XGBoost, Learn-to-Rank).

Specialized in unifying heterogeneous systems into clean, queryable data warehouses — especially for finance, banking, and telecom use cases. Comfortable owning a project end-to-end: requirements, architecture, delivery, team coordination, and stakeholder communication up to C-level.

---

## 🚀 Featured Projects

### 🏦 EasyBill ERP — Document AI for Bank Statement Extraction

> Tunisian accounting ERP with a custom **Google Document AI processor fine-tuned on local bank statements** (BIAT, Attijari).

**Measured impact of fine-tuning vs generic Google baseline:**

| Metric | Generic baseline | Fine-tuned model | Uplift |
|---|---|---|---|
| **F1 Score** | 0.495 | **0.835** | **+68%** |
| **Precision** | 38.5% | **83.1%** | **×2.16** |
| **Recall** | 69.4% | **84.0%** | **+21%** |

**Highlights**
- End-to-end bank statement AI extraction: PDF ingestion → OCR → table detection → line-level extraction (date, label, debit, credit, balance) → mathematical consistency validation
- Automatic bank reconciliation engine with fuzzy multi-criteria matching and posting suggestion
- ML transaction classifier with incremental pattern learning
- **NCT certification 100/100** across 7 compliance dimensions, validated by a 12-month rolling simulation

**Stack** &nbsp; Python (FastAPI) &nbsp;·&nbsp; MongoDB &nbsp;·&nbsp; Google Document AI &nbsp;·&nbsp; React &nbsp;·&nbsp; Docker

---

### 🔄 DataHive — Fivetran-style Multi-Destination Data Integration Platform

> Production ELT SaaS platform with **16 warehouse/BI destinations** and **30+ OAuth source connectors**, designed for agencies and mid-market teams that need a low-code Fivetran alternative.

**Destination catalog**
BigQuery (native) · Snowflake · Redshift · Databricks · ClickHouse · PostgreSQL · MySQL · MSSQL · DuckDB/MotherDuck · Athena · GCS · S3 · Azure Blob · Looker Studio · Power BI · Google Sheets

**Source catalog**
Meta Ads · Google Ads · Google Analytics · Instagram · TikTok · LinkedIn · Snapchat · Pinterest · Salesforce · HubSpot · QuickBooks · Shopify · Stripe · Apple App Store · Google Play Console · and more

**Technical highlights**
- Native **BigQuery destination** with Service Account authentication, `dlt[bigquery]` loader, multi-region (EU/US) dataset management
- **dlt-powered ELT** pipelines: auto-inferred schemas, incremental loading, merge/upsert, staging
- **Cross-dialect SQL transpilation** with `sqlglot` — migrate queries between MySQL / PostgreSQL / MSSQL / BigQuery Standard SQL
- Production-grade foundation: JWT auth with tenant isolation, rate-limiting, quota enforcement, audit logs, Sentry APM, Celery Beat orchestration
- Stripe-based subscriptions (Starter / Professional / Enterprise)

**Stack** &nbsp; Django 4.2 &nbsp;·&nbsp; FastAPI &nbsp;·&nbsp; Celery + Redis &nbsp;·&nbsp; PostgreSQL &nbsp;·&nbsp; dlt &nbsp;·&nbsp; sqlglot &nbsp;·&nbsp; Sentry

---

### 📊 Club Privilèges BI — Multi-System Unification & Payment ML

> Real-time BI platform unifying **6 heterogeneous partner systems** (Eklektik, Timwe, DGV, IZI, Ooredoo, SubStore) for a **500 000+ user** loyalty program.

**ML models in production**

*Payment Success Predictor* — LightGBM
- 64 000 training samples · 18 features · handled class imbalance with `scale_pos_weight`
- Features: per-channel success rate, churn probability, engagement score, lifetime value, subscription age, consecutive failure count, days since last payment
- AUC-ROC tracking, feature importance, persisted via joblib (production version `billing_predictor_v3`)

*Merchant Recommender* — Learn-to-Rank
- 111 660 training samples / 27 660 test samples / 15 399 groups
- 28 RFM features: visit patterns, loyalty score, recency, frequency, category diversity, promotions, subscription tier, demographics
- **NDCG@5 = 1.0 · NDCG@10 = 1.0**

**Business results**
- **+478.8%** subscription growth
- **94%** retention rate
- **500 000+** users tracked
- **15+** real-time KPI dashboards powering C-level decisions

**Additional work**
- Cross-system aggregation service layer (stats services, revenue-sharing engine, KPI optimizers)
- Historical data reprocessing scripts covering millions of rows after business rule changes
- Multi-level intelligent cache (adaptive TTL, hierarchical keys, automatic fallback)

**Stack** &nbsp; Laravel 10 &nbsp;·&nbsp; MySQL &nbsp;·&nbsp; Python (LightGBM, XGBoost, scikit-learn, SHAP, Optuna) &nbsp;·&nbsp; Chart.js

---

## 🛠 Technical Skills

**Google Cloud Platform**
BigQuery (Expert — partitioning, clustering, Service Account, `dlt[bigquery]`, Standard SQL, scripted procedures) · Cloud Storage · Pub/Sub · Dataflow · Cloud Composer (Airflow) · Cloud Functions · Cloud Run · Cloud SQL · Data Catalog · IAM · Cloud DLP · Looker Studio (Expert) · Document AI (custom processor fine-tuning)

**Data Engineering**
dlt (Data Load Tool) · Airflow · Celery + Redis · sqlglot (cross-dialect SQL transpilation) · pandas · NumPy · incremental pipelines · CDC · merge/upsert · batch & streaming orchestration

**SQL & Databases**
BigQuery SQL (Expert) · PostgreSQL · MySQL · MSSQL · MongoDB · ClickHouse · DuckDB · Snowflake · Redshift · Databricks · dimensional modeling (star/snowflake) · window functions · analytic queries over 500K+ rows

**Machine Learning**
LightGBM · XGBoost · scikit-learn · SHAP · Optuna · Learn-to-Rank (LambdaRank, NDCG) · scoring models (payment, churn, fraud) · recommendation systems · class imbalance handling · feature engineering

**AI & Document Intelligence**
Google Document AI (custom processor fine-tuning on domain-specific corpora) · OCR · post-processing ML · Azure OpenAI · LLM providers (OpenAI, Google GenAI, HuggingFace, litellm) · reconciliation engines · transaction classifiers

**BI & Visualization**
Power BI (Expert) · Looker Studio (Expert) · Chart.js · Recharts · KPI design · data storytelling · executive reporting

**Languages & Frameworks**
Python (Expert — pandas, NumPy, scikit-learn, FastAPI, Django, Celery) · SQL (Expert) · PHP (Laravel) · JavaScript/TypeScript (React, Node.js) · Bash

**Cloud & DevOps**
GCP (Expert) · AWS (S3, Athena, Redshift, Personalize) · Azure (ML, OpenAI, Blob Storage) · Terraform · Docker · Docker Compose · CI/CD (GitHub Actions) · Git · Sentry APM · Nginx

**Governance & Security**
GDPR · Data Quality · Data Lineage · JWT authentication · rate-limiting · multi-tenant isolation · audit logs · fine-grained IAM

---

## 💼 Experience

**Senior Data Architect & BI Lead** — BigDeal S.A. &nbsp;·&nbsp; *Jan 2018 – Present*
Leading data & BI strategy: 15+ production BI solutions and data pipelines, cross-database migrations to cloud warehouses, production ML introduction, GDPR-compliant governance, team management up to 8 people, monthly C-level reporting.

**Digital Strategy & Web Analytics Consultant** — MediaNet S.A. &nbsp;·&nbsp; *Jan 2015 – Dec 2017*
Advanced Google Analytics deployment, multi-touch attribution modeling, automated digital performance reporting — improved campaign ROI by +25%.

**SEO & Web Performance Specialist** — Prodexo S.A.R.L &nbsp;·&nbsp; *Jul 2013 – Dec 2014*
Technical SEO audits and optimization of high-traffic platforms — reduced load times by –60% via caching, compression, CDN, minification.

---

## 🎓 Education & Certifications

**Master's in AI & Robotics Engineering** — ENSIT, Tunis &nbsp;·&nbsp; 2020–2022
**Bachelor's in Information Systems Development** — ISET, Tunis &nbsp;·&nbsp; 2009–2013

**Certifications** &nbsp; Data Science Productivity Tools (HarvardX) &nbsp;·&nbsp; Data Science Tools (IBM) &nbsp;·&nbsp; Python Basics for Data Science (IBM) &nbsp;·&nbsp; Microsoft Office Specialist

**Languages** &nbsp; French (C2) &nbsp;·&nbsp; English (B1) &nbsp;·&nbsp; Arabic (Native)

---

## 📫 Get in touch

Available for senior **Data Analyst** and **Data Engineering** missions — preferably in **finance, banking, insurance, telecom or enterprise SaaS**. Open to remote or hybrid roles based in France.

- ✉️ **Email** &nbsp; [imededdine.safi@gmail.com](mailto:imededdine.safi@gmail.com)
- 💼 **LinkedIn** &nbsp; [imededdine-safi](https://linkedin.com/in/imededdine-safi-31549b88)
- 📍 **Location** &nbsp; Marseille, France

---

<div align="center">
<sub>Source code for the projects above is available on request, under NDA when required.</sub>
</div>
