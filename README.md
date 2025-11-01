# Databricks AI Segmentation → Salesforce Data Cloud

This repository contains a lightweight **Databricks / PySpark** notebook that demonstrates how customer segmentation models can be operationalized within **Salesforce Data Cloud** and **Agentforce**.

---

### 🎯 Scenario: Customer Segmentation for AI-Driven Engagement
A marketing team wants to identify **high-value** and **at-risk** customers using transaction data processed in Databricks.  
The enriched dataset is exported to Salesforce Data Cloud for downstream activation in CRM Analytics and Agentforce.

---

### 🧱 Architecture
Databricks (PySpark DataFrames) → Feature Engineering → Segment CSV → Salesforce Data Cloud (DMO) → CRM Analytics → Agentforce Actions

---

### 🧩 Repository Contents
| Path | Description |
|------|--------------|
| `notebooks/segmentation_notebook.ipynb` | Jupyter/Databricks notebook that computes customer RFM-style segments |
| `data/sample_transactions.csv` | Synthetic dataset for demo |
| `images/architecture_diagram.png` | Visualization of architecture |
| `docs/demo_story.md` | Full enablement context and storytelling guide |

---

### 🧪 Key Demo Steps
1. Load sample transactions in Databricks or local PySpark.  
2. Aggregate by customer and compute metrics (total spend, recency, frequency).  
3. Label segments (High/Medium/Low value).  
4. Export results as `segments.csv`.  
5. Ingest into Salesforce Data Cloud and visualize in CRM Analytics.

---

### 💬 Demo Talking Points
- Shows integration of external AI/ML pipelines with Data Cloud.  
- Demonstrates how DataFrames (PySpark/pandas) fit into Salesforce architecture.  
- Storytelling bridge for SEs: external data → unified Data Cloud profile → AI-driven actions.  

---

### 🧠 Intended Audience
Salesforce Solution Engineers, Data Cloud & AI practitioners, and community learners building Data Cloud–AI demo flows.

---

### 📚 Related Reading
- [Dynamic Dashboard Filters in CRM Analytics + Data Cloud (LinkedIn Article)](https://www.linkedin.com/in/lakshmi-achary)

---

### 📄 License
MIT © Lakshmi Achary  
*(Sample enablement demo — not affiliated with Salesforce.)*
