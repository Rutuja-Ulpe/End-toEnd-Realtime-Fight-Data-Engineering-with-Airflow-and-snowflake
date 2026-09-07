# ✈️ End-to-End Real-Time Flight Data Engineering with Apache Airflow & Snowflake

An end-to-end real-time flight data engineering project that demonstrates automated data ingestion, ETL processing, workflow orchestration, data transformation, cloud data warehousing, and interactive analytics.

The pipeline uses **Apache Airflow** to orchestrate flight data processing and **Snowflake** as the cloud data warehouse for storing and analyzing processed flight data.

---

## 🚀 Project Overview

This project implements a production-style data engineering pipeline for processing real-time flight data.

### Pipeline

```text
Flight Data API
      ↓
Apache Airflow
      ↓
Bronze Layer
      ↓
Silver Layer
      ↓
Gold Layer
      ↓
Snowflake
      ↓
Analytics Dashboard
