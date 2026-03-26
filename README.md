# 📊 Product Demand Analytics

## 🚀 Overview
This project analyzes historical sales data to identify **seasonal demand patterns** across different locations.  
It helps optimize production planning and improve resource utilization.

---

## 🎯 Key Features
- Seasonal demand analysis  
- Location-based sales insights  
- Data cleaning & validation  
- Star schema (Fact & Dimension tables)  
- Power BI dashboards  

---

## 🏗️ Architecture (Medallion)

- **Bronze Layer**: Raw data ingestion from multiple sheets into Azure Data Lake (Blob Storage)  
- **Silver Layer**: Data cleaning, null handling, schema validation using Databricks (stored in Parquet)  
- **Gold Layer**: Business transformations, star schema, SCD implementation, data loaded into SQL DB  

---

## 🛠️ Tech Stack
- Azure Data Lake Gen2  
- Azure Data Factory (Copy Activity, Data Flow)  
- Databricks (PySpark)  
- SQL Database  
- Power BI  

---

## 📊 Visualization
- Interactive dashboards for demand trends and insights  

---

## 📈 Impact
- Improved demand forecasting  
- Better production planning  
- Efficient resource utilization  

---
