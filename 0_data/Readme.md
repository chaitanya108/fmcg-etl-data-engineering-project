# 🚀 Data Engineering Project – Databricks (Bronze → Silver → Gold Pipeline)

This project showcases an end-to-end **data engineering pipeline** built on **Databricks**, using **AWS S3**, **Unity Catalog**, **Delta Lake**, and **Lakeflow Jobs**.  
It demonstrates how a **Child Company** processes data and shares curated **Gold** datasets with a **Parent Company** for enterprise-level analytics.

---

## 🏗️ Architecture Overview

The workflow follows the Medallion Architecture pattern:

### 1️⃣ RAW Data (S3)
- 📥 Raw data lands in an S3 bucket (JSON/CSV).  
- 🗄️ Historical data archived for auditing.

### 2️⃣ Bronze Layer
- ⚙️ Data ingestion using **Lakeflow Jobs**.  
- 🧹 Basic parsing and minimal transformation.

### 3️⃣ Silver Layer
- 🔧 Data cleaning, validation, and schema standardization.  
- 🔄 Business rules applied.

### 4️⃣ Gold Layer
- ⭐ Child Company produces analytics-ready Gold tables.  
- 🔗 Shared with Parent Company via **Unity Catalog**.  
- 🏢 Parent Company merges child Gold into enterprise analytics layers.

### 5️⃣ Serving Layer
- 📊 Dashboards  
- 🧞 Genie  
- 🤖 BI & Analytics Applications  

---

## 🧰 Tech Stack
- 🔥 Databricks  
- 🐱 Unity Catalog  
- 💾 Delta Lake  
- 🔄 Lakeflow Jobs  
- ☁️ AWS S3  
- 🐍 Python / PySpark  
- 🛢️ SQL  

