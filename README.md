# Azure-ETL-Sales-Pipeline

This project showcases a production-ready end-to-end data pipeline built on Azure and Databricks to automate the ingestion, transformation, and modeling of car sales data for analytical use.

🔧 Tech Stack
Azure Data Factory – Orchestration and parameterized workflows

Databricks – Distributed data processing with PySpark

Azure SQL Database – Initial storage and relational modeling

Delta Lake – Medallion architecture (Bronze, Silver, Gold layers)

Unity Catalog – Data access control and governance

GitHub API – Source of raw car sales data

📌 Features
🔁 Incremental Loading using parameterized ADF pipelines

⚙️ Reusable Workflow with managed identities and linked services

🧱 Medallion Architecture for layered data processing

🌟 Star Schema modeling and SCD logic with PySpark

🔐 Secure Access Control via Unity Catalog

🚀 Performance Gains: Reduced analyst refresh lag by 60%

📁 Architecture Overview
Data Ingestion: ADF connects to GitHub API → Azure SQL DB

Bronze Layer: Raw ingestion via Databricks

Silver Layer: Data cleansing + transformations

Gold Layer: Star schema (facts/dimensions) + SCD

Access: Unity Catalog ensures secure, governed access

📊 Outcome
Enabled scalable, automated data preparation for analytics

Reduced data refresh time significantly

Improved traceability, reusability, and securityThis project showcases a production-ready end-to-end data pipeline built on Azure and Databricks to automate the ingestion, transformation, and modeling of car sales data for analytical use.

🔧 Tech Stack
Azure Data Factory – Orchestration and parameterized workflows

Databricks – Distributed data processing with PySpark

Azure SQL Database – Initial storage and relational modeling

Delta Lake – Medallion architecture (Bronze, Silver, Gold layers)

Unity Catalog – Data access control and governance

GitHub API – Source of raw car sales data

📌 Features
🔁 Incremental Loading using parameterized ADF pipelines

⚙️ Reusable Workflow with managed identities and linked services

🧱 Medallion Architecture for layered data processing

🌟 Star Schema modeling and SCD logic with PySpark

🔐 Secure Access Control via Unity Catalog

🚀 Performance Gains: Reduced analyst refresh lag by 60%

📁 Architecture Overview
Data Ingestion: ADF connects to GitHub API → Azure SQL DB

<img width="1337" alt="Screenshot 2025-04-12 at 11 15 10" src="https://github.com/user-attachments/assets/969b1096-84f9-4270-b458-127f8eca4bac" />

Bronze Layer: Raw ingestion via Databricks

Silver Layer: Data cleansing + transformations

Gold Layer: Star schema (facts/dimensions) + SCD

Access: Unity Catalog ensures secure, governed access

<img width="1718" alt="Workflow" src="https://github.com/user-attachments/assets/99fe11d3-3b3c-4233-8914-ddfc8f401354" />

📊 Outcome
Enabled scalable, automated data preparation for analytics

Reduced data refresh time significantly

Improved traceability, reusability, and security
