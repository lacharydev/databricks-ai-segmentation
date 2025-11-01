# Databricks AI Segmentation (POC)

This repository contains a lightweight **Databricks / PySpark** notebook that segments customers for **AI-powered experiences** in Salesforce **Data Cloud** and **Agentforce**.

## 🔗 Flow
Raw transactions (CSV) → PySpark/pandas feature engineering → segment export → Data Cloud ingest → CRM Analytics dashboard → Agentforce action.

## 📦 Contents
- `notebooks/segmentation_notebook.ipynb` – minimal notebook with PySpark + pandas steps.
- `data/sample_transactions.csv` – small synthetic dataset.
- `images/architecture_diagram.png` – diagram for README/LinkedIn.

## ▶️ How to Run (Databricks or Local)
- Upload the notebook to Databricks (or run locally with PySpark).
- Replace the CSV path as needed.
- Export the resulting `segments.csv` and ingest into Data Cloud (CSV data stream).

## 🧪 Demo Talking Points
- DataFrames for wrangling, engineered features (RFM, recency, amount buckets).
- Export segments to Data Cloud; build a CRM Analytics view filtered per user/region.
- Connect to Agentforce for “target high-value churn-risk customers” action.

## 📄 License
MIT © Lakshmi Achary
