# constructor-data-pipeline-demo
End-to-end Data Platform Demo for E-commerce — Ingesting, transforming, and serving product interaction data using Spark, Delta Lake, Parquet, AWS Lambda, and ClickHouse, following a bronze → silver → gold layered architecture. Inspired by Constructor.io's real-world data stack.


# 🧠 E-Commerce Data Platform Pipeline (Constructor-Inspired)

This project showcases an end-to-end **Data Platform** for a mock e-commerce business, inspired by the architecture and tooling used at [Constructor.io](https://www.constructor.io/).  
It demonstrates how to process, optimize, and serve large-scale product discovery data across **Bronze → Silver → Gold layers**, while focusing on modularity, performance, and observability.

---

## 🚀 Features

- ✅ Raw data ingestion into **S3** (Bronze layer)
- 🧹 Data transformation & cleaning using **PySpark** (Silver layer)
- 📊 Aggregation & modeling for downstream consumption (Gold layer)
- 📦 Query-ready datasets loaded into **ClickHouse**
- ⚙️ Event-based pipeline with simulated **AWS Lambda**
- 🧪 Unit test coverage for pipeline stages
- 📈 Monitoring hooks via mock **Prometheus** exporters
- 📄 Modular, testable code structure in **Python**

---

## 🏗️ Tech Stack

| Layer            | Tools/Tech                              |
|------------------|------------------------------------------|
| Data Ingestion   | Python, JSON, S3 (LocalStack or simulated) |
| Transformation   | PySpark, Delta Lake, Parquet              |
| Storage          | S3, Delta Lake, Parquet                   |
| Serving          | ClickHouse, FastAPI (optional API layer) |
| Orchestration    | Python script / cron / event trigger      |
| Monitoring       | Prometheus (simulated), logs              |
| Testing          | Pytest, assertions, schema checks         |

---
