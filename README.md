# Sales-Data-Analytics-Azure-Data-Engineering-End-to-End-Project

# Project Overview:

This project simulates a real-world business scenario for a Retail company that wants to modernize its data architecture and gain actionable insights from its sales, customer, and inventory data stored in an on-premise SQL Server database.
I built a complete cloud-native Data Engineering solution using Microsoft Azure tools. The goal was to migrate raw operational data to the cloud, transform it using ETL best practices, store it in a centralized enterprise-grade warehouse, and present insights via an interactive Power BI dashboard  empowering business teams to make data-driven decisions.


## 🎯 Business Problem

A fictional **retail retail company** faces reporting delays, data silos, and inconsistent KPIs. This solution was developed to:

- Automate ingestion and transformation of daily sales and customer data.
- Enable centralized, cloud-based analytics.
- Deliver interactive dashboards to empower business teams with actionable insights.


# Architecture diagram Solution 

<img width="1280" height="556" alt="Architech diagram" src="https://github.com/user-attachments/assets/1614aa20-34b8-4afe-851f-1e0635de20c1" />

🗂️ Project Repository Structure


azure-retail-data-pipeline/
├── README.md
├── architecture-diagram.png
├── powerbi/
│   └── Sales Dashboard.pbix
├── notebooks/
│   ├── bronze_ingestion.py
│   ├── silver_transformation.py
│   └── gold_modeling.py
├── ADF Files/
│   └── retail_pipeline.json
├── synapse_queries/
│   └── analytics_queries.sql






# Tools/Technology used


| Component        | Technology                 |
| ---------------- | -------------------------- |
| Source System    | SQL Server (On-premise)    |
| Data Ingestion   | Azure Data Factory         |
| Storage Layer    | Azure Data Lake Gen2       |
| ETL & Processing | Azure Databricks (PySpark) |
| Query Layer      | Azure Synapse Analytics    |
| BI & Reporting   | Power BI Desktop    
| Azure Key Vault  | Manages secrets, credentials, keys, tokens |
| Azure Active Directory (AAD) | Manages user access/authentication |



## 📊 Power BI Dashboard


<img width="630" height="354" alt="image" src="https://github.com/user-attachments/assets/d90d439a-4997-4c0f-ac23-45c826faa920" />


## The final dashboard provides rich, real-time insights, including:

- 🧍 Customer Distribution by Location  
- 📈 Monthly Sales Trends by Region  
- 📦 Best Perfoming Products
- 🌍 Geo Mapping of Product Performance

> 🖼️ Dashboard preview available in the `/powerBi files/` folder.



 # Key Business Features Delivered:

🔄 Automated ETL: Scheduled ingestion and transformation of sales data across regions

📦 Data Warehousing: Centralized, query-optimized data for reporting and advanced analytics


🧠 Insight-Driven Decision Making: Enabled marketing and supply chain teams to act on timely insights

🧹 Data Quality Checks: Implemented validation layers using Databricks and ADF



## 🧪 Data Quality & Governance

- 🔐 **Secure connections** using Azure Key Vault for credentials
- ✅ **Validation rules** in Databricks notebooks for schema & null checks
- 🗂️ **Role-based access** applied to Synapse & Power BI


## 📈 Business Impact

This cloud-based data engineering pipeline improves the organization's ability to:

- Make faster, data-driven decisions
- Eliminate manual report generation
- Monitor product, region, and customer behavior dynamically
- Scale infrastructure with business growth







