# Data Engineer | Modern Data Stack

Welcome! I'm a **Data Engineer** specializing in designing and building **scalable, reliable, and production-grade data pipelines** using the **Modern Data Stack (MDS)**.

I focus on transforming raw data into **high-quality, analytics-ready datasets** through robust architecture, automation, and engineering best practices.

---

## 🧠 Core Expertise

- Designing end-to-end **ELT pipelines**
- Building **modular and reusable workflows**
- Ensuring **data quality, validation, and observability**
- Applying **software engineering principles** in data systems
- Working with **containerized and cloud-ready environments**

---

## 🛠 Tech Stack & Tools

### ⚙️ Data Orchestration & Infrastructure
- Astronomer (Astro)
- Apache Airflow
- Docker

### 🧱 Data Transformation & Modeling
- dbt (Data Build Tool)
- PostgreSQL
- SQL Server
- Snowflake

### 🔁 Version Control & DevOps
- Git & GitHub
- CI/CD Pipelines

---

## 🏗 Data Pipeline Architecture

```text
        ┌──────────────┐
        │  Data Source │  (SQL Server / APIs)
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │   Airflow    │  (Orchestration via Astro)
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │   Docker     │  (Containerized Tasks)
        └──────┬───────┘
               │
       ┌───────┴────────┐
       ▼                ▼
┌──────────────┐  ┌──────────────┐
│ PostgreSQL   │  │  Snowflake   │
│ (Staging)    │  │ (Warehouse)  │
└──────┬───────┘  └──────┬───────┘
       │                  │
       ▼                  ▼
        ┌──────────────┐
        │     dbt      │  (Transformations)
        └──────┬───────┘
               │
               ▼
        ┌──────────────┐
        │ Data Marts   │ (Star Schema)
        └──────────────┘
