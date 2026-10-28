<div align="center">





![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00FF9D&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Debya.;Data+%2F+ML+Engineer;Based+in+France.)

---


[![LinkedIn](https://img.shields.io/badge/LinkedIn-debya--ahmed--salem-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debya-ahmed-salem-3255122a2/)
[![Email](https://img.shields.io/badge/Email-debyaahmedsalem%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:debyaahmedsalem@gmail.com)


📍 Montpellier, France (open to relocating across all of Metropolitan France) &nbsp;|&nbsp; Looking for a PFE internship in Data / AI

</div>

---

```python
class Debya(DataEngineer, MLEngineer):
    """
    Data Engineer turning messy data into AI systems that actually run.
    """
    def __init__(self):
        self.role         = "Data / ML Engineer"
        self.education    = "M2 Data Science & AI, Univ. of Montpellier"
        self.base         = "France"
        self.looking_for  = "PFE in Data / AI, 2026 – 2027"

    def mission(self) -> str:
        return "From raw data to reliable predictions, at scale."
```

---

## 🔧 Technical Skills

**`languages`**&nbsp;&nbsp;
![Python](https://img.shields.io/badge/Python-79c0ff?style=flat-square&logo=python&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-79c0ff?style=flat-square&logo=postgresql&logoColor=black)
![R](https://img.shields.io/badge/R-79c0ff?style=flat-square&logo=r&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-79c0ff?style=flat-square&logo=gnubash&logoColor=black)

**`cloud_infra`**&nbsp;
![GCP](https://img.shields.io/badge/GCP-d2a8ff?style=flat-square&logo=googlecloud&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-d2a8ff?style=flat-square&logo=amazonaws&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-d2a8ff?style=flat-square&logo=docker&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-d2a8ff?style=flat-square&logo=openai&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-d2a8ff?style=flat-square&logo=githubactions&logoColor=black)

**`data_eng`**&nbsp;&nbsp;
![Airflow](https://img.shields.io/badge/Airflow-ffa657?style=flat-square&logo=apacheairflow&logoColor=black)
![Spark](https://img.shields.io/badge/Spark-ffa657?style=flat-square&logo=apachespark&logoColor=black)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-ffa657?style=flat-square&logo=elasticsearch&logoColor=black)
![Neo4j](https://img.shields.io/badge/Neo4j-ffa657?style=flat-square&logo=neo4j&logoColor=black)
![CI/CD](https://img.shields.io/badge/CI%2FCD-ffa657?style=flat-square&logo=githubactions&logoColor=black)

**`ml_stack`**&nbsp;&nbsp;
![TensorFlow](https://img.shields.io/badge/TensorFlow-3fb950?style=flat-square&logo=tensorflow&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-3fb950?style=flat-square&logo=pytorch&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-3fb950?style=flat-square&logo=scikitlearn&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-3fb950?style=flat-square&logo=langchain&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-3fb950?style=flat-square&logo=huggingface&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-3fb950?style=flat-square&logo=mlflow&logoColor=black)
![XGBoost](https://img.shields.io/badge/XGBoost-3fb950?style=flat-square&logo=xgboost&logoColor=black)


**`monitoring`**&nbsp;
![Grafana](https://img.shields.io/badge/Grafana-8b949e?style=flat-square&logo=grafana&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-8b949e?style=flat-square&logo=tableau&logoColor=black)
![PowerBI](https://img.shields.io/badge/PowerBI-8b949e?style=flat-square&logo=powerbi&logoColor=black)

**`project_mgmt`**&nbsp;
![Agile](https://img.shields.io/badge/Agile-f778ba?style=flat-square&logo=agile&logoColor=black)
![Scrum](https://img.shields.io/badge/Scrum-f778ba?style=flat-square&logo=scrumalliance&logoColor=black)
![Kanban](https://img.shields.io/badge/Kanban-f778ba?style=flat-square&logo=kanban&logoColor=black)

---

## 💼 Experience

**Data & AI Intern** — Levon Studio | Casablanca, Morocco | **Feb 2025 – Jul 2025**
- Designed and deployed a **content-based recommendation engine** for a language-learning flashcard app, fully serverless on **GCP**: a nightly Cloud Function finds active users in **BigQuery**, encodes profiles and content with **SBERT embeddings**, ranks content by cosine similarity and writes personalized recommendations to **Firestore**, with a fallback for new users (cold start).
- Built a modular **Text-to-Speech pipeline** (Coqui XTTS v2) generating pronunciation audio in **7 languages**, in batch mode for existing cards and in real time via **Pub/Sub** for new ones.
- Solved production issues such as memory timeouts (model packaging, lazy loading, batched inference).
- Worked in **Scrum** with daily stand-ups.

**Data Engineering Intern** — Banque Nationale de Mauritanie (BNM) | Nouakchott, Mauritania | **Jul 2024 – Sep 2024**
- Designed a self-hosted **banking data warehouse**: incremental replication with **Airbyte** from the core banking system (**SQL Server**) and the mobile app (**MySQL**) into **PostgreSQL**, using read-only accounts.
- Modeled the data with **dbt** in layers (staging, SCD2 snapshot, **star schema** with 6 dimensions and 4 fact tables), cleaning messy front-office data and deduplicating customers.
- Built business marts for **credit risk** (days past due, NPL, PAR30/90, provisions), **branch performance** against targets and **digital adoption**.
- Added **49 data quality tests**, including reconciliation against source systems on 2.1M transactions; role-based access with personal data isolated in a restricted schema.
- Orchestrated the nightly pipeline with **Airflow** and built **3 Metabase dashboards** (Risk, Finance, Digital), all created as code.

**Data Science Intern** — ANSADE (Agence Nationale de la Statistique et de l'Analyse Démographique et Économique) | Nouakchott, Mauritania | **Jun 2022 – Jul 2022**
- Analyzed Mauritania's **trade balance (2006–2021)** from quarterly export/import data in **Stata, R and Excel**.
- Applied **PCA** on exported products, time-series decomposition and **hypothesis tests** (paired t-test, F-test on variances) to compare periods.

---

## 🚀 Selected Projects

| Project | Description | Stack |
|---|---|---|
| [**Food Delivery Pipeline**](https://github.com/De-bya/food-delivery-pipeline) | End-to-end daily data pipeline on **35M rows** of food delivery orders: S3 → Snowflake → dbt (medallion architecture, star schema, incremental models, SCD2, 17 tests), orchestrated by Airflow. An AI layer adds review analysis, a RAG chatbot over customer reviews and text-to-SQL with a SELECT-only guardrail. | `Python` `AWS S3` `Snowflake` `dbt` `Airflow` `Docker` `OpenAI` |
| [**JobFit Agent**](https://github.com/De-bya/jobfit-agent) | Multi-step **RAG agent** that compares a resume to a job posting requirement by requirement, classifies each gap and suggests improvements without inventing skills. Benchmarked 4 retrieval strategies (hybrid search chosen, Hit Rate 0.72) and monitored with Grafana. | `Python` `OpenAI API` `Elasticsearch` `dlt` `PostgreSQL` `Grafana` `Streamlit` |
| [**SightSense**](https://drive.google.com/file/d/1-sQQ7uDNP34f3CI1joapCOv-itMAEVZ4/view) | Android app helping visually impaired people with **computer vision**: object and banknote recognition, real-time obstacle alerts and text reading with voice guidance. Fine-tuned **YOLOv11** on a team-built dataset (800 photos augmented to 4,000) and ran it on-device with TensorFlow Lite. | `Kotlin` `Python` `YOLO` `TensorFlow Lite` `Flask` `GPT-4o` |
---

## 🎓 Education

- **Master 2, Data Science & Artificial Intelligence** — Université de Montpellier, France (2026 – 2027)
- **Engineering Degree, Data Engineering** — ENSIAS, Rabat, Morocco (2023 – 2025)
- **Engineering Degree, Statistics & Data Engineering** — ESP, Nouakchott, Mauritania (2021 – 2023)
- **Preparatory Classes for Engineering Schools (MPSI/MP)** — IPEGI, Nouakchott, Mauritania (2019 – 2021)

---



<div align="center">

If you're hiring in France for a **PFE in Data or AI/ML** , I'd love to connect.

[![Let's Connect](https://img.shields.io/badge/Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debya-ahmed-salem-3255122a2/)

</div>
