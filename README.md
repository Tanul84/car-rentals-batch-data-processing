# 🚗 Car Rental Data Batch Processing Pipeline

### 📜 Overview
This project implements a **scalable ETL (Extract, Transform, Load) pipeline** for processing **car rental data**. Designed to handle large-scale data ingestion and transformation tasks, this pipeline supports advanced analytics and maintains historical data accuracy using modern **Big Data technologies**.

---

## ⚙️ Features
- **Batch Data Ingestion**: Processes daily car rental and customer data from Google Cloud Storage.  
- **Data Transformation**: Implements **Slowly Changing Dimensions Type 2 (SCD2)** for maintaining historical accuracy.  
- **Scalable Architecture**: Uses distributed computing with **PySpark** and **GCP Dataproc** to handle large datasets efficiently.  
- **Workflow Automation**: Orchestrated with **Apache Airflow** for scheduling and monitoring.  
- **Data Warehousing**: Stores transformed data in **Snowflake**, with well-structured dimension and fact tables for analytics.

---

## 🛠️ Tech Stack
- **Programming**: Python 🐍, PySpark  
- **Distributed Frameworks**: Apache Spark on GCP Dataproc  
- **Workflow Orchestration**: Apache Airflow  
- **Cloud**: Google Cloud Platform (GCP) - Dataproc, BigQuery, Cloud Storage  
- **Data Warehouse**: Snowflake  
- **Compression**: Snappy, Gzip  

---

## 📂 Project Structure
```plaintext
car-rental-batch-processing/
├── airflow_dags/                          # Airflow DAGs for workflow orchestration
├── spark_job/                       # PySpark jobs for data transformation
└── README.md                      # Project documentation (this file)
