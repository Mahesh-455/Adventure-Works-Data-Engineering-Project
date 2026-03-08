**Azure SparkSQL End-to-End Data Engineering Project**
📌 **Project Overview**
This project demonstrates an end-to-end data engineering pipeline built using Azure services and Apache Spark. The pipeline ingests raw data, processes it using PySpark/SparkSQL, and stores the transformed data for analytics.
The goal of this project is to simulate a real-world data engineering workflow, including data ingestion, transformation, and storage in a scalable cloud environment.

🎥 **Project Reference**

This project was built by following the tutorial:
https://www.youtube.com/watch?v=0GTZ-12hYtU
The tutorial demonstrates how to build a complete Azure SparkSQL pipeline using Databricks and cloud storage.

🏗️ **Architecture**

Typical workflow of the pipeline:

Data Source
     │
     ▼
Azure Data Lake Storage
     │
     ▼
Azure Databricks
(PySpark / SparkSQL)
     │
     ▼
Processed Data
(Silver / Gold Layer)
     │
     ▼
Analytics / Querying

**Architecture Layers:**

1. Raw Layer (Bronze)
Stores raw ingested data.
2. Processed Layer (Silver)
Data cleaning
Data transformation
3. Curated Layer (Gold)
Analytics-ready datasets
Aggregated tables

⚙️ **Tech Stack**

1. Azure Databricks
2. Apache Spark
3. PySpark
4. SQL
5. Azure Data Lake Storage
6. Python

<img width="561" height="245" alt="image" src="https://github.com/user-attachments/assets/5dbf6dde-5efb-46c4-88f7-5de3dcf6597a" />

