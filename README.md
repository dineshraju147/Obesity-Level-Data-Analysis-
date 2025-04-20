# ETL Pipeline for Obesity Level Data Analysis Using GCP and Power BI

## 📌 Project Overview
This project aims to build a scalable ETL (Extract, Transform, Load) pipeline using **Google Cloud Platform (GCP)** services for analyzing obesity level data based on eating habits and physical condition. The pipeline processes raw data from Google Cloud Storage, transforms it using **Cloud Data Fusion**, stores it in **BigQuery**, and visualizes the results in **Power BI**.

---

## 🛠️ Tools & Technologies

- **Google Cloud Storage (GCS)** – Raw data storage
- **Cloud Data Fusion** – Visual ETL pipeline (Wrangler + Python Transform)
- **BigQuery** – Scalable cloud data warehouse
- **Power BI** – Business Intelligence and visualization
- **Cloud Dataproc & Log Explorer** – Pipeline orchestration and job monitoring

---

## 📈 Project Architecture

```text
Step 1: GCS 
   ↓
Step 2: Wrangler (Cloud Data Fusion)
   ↓
Step 3: Python Transform (INFO & ERROR Logging)
   ↓
Step 4: BigQuery
   ↓
Step 5: Power BI Dashboard
