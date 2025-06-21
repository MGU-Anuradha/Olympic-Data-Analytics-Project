# Tokyo Olympics Data Analytics Pipeline — Azure End-to-End Project

An end-to-end data analytics project built using the **Microsoft Azure** ecosystem, focused on transforming raw Olympic data into powerful insights through cloud-native tools and technologies.

📌 Blog : [Entering the World of Data Engineering: A Hands-On Azure Project](https://medium.com/@mguanuradha/entering-the-world-of-data-engineering-a-hands-on-azure-project-f39461cc9c8d)

## 🚀 Project Overview

This project explores the power of cloud-based data engineering by developing a **scalable and modular pipeline** to analyze the **Tokyo Olympics** dataset. The goal is to build a pipeline that moves data from ingestion to visualization, applying data cleaning, transformation, and basic ML analysis along the way.

![Project Overview](https://github.com/user-attachments/assets/5b35d894-4072-4e69-997a-c1be49714a76)


---

## 🛠️ Tech Stack

- **Azure Data Factory** – Data ingestion from local CSVs to Azure Data Lake Storage Gen2
- **Azure Data Lake Storage Gen2** – Centralized storage for raw and curated datasets
- **Azure Databricks (PySpark)** – Data transformation, exploration, and feature engineering
- **Azure Synapse Analytics** – Scalable SQL querying on curated data (Lake Database)
- **Power BI** – Interactive dashboard for visualizing athlete performance and medal trends

---

### 📊 Pipeline Workflow

CSV Files → Azure Data Factory → Data Lake Storage Gen2 → Databricks Notebooks → Synapse Analytics → Power BI Dashboard


### ✅ Steps

1. **Data Ingestion**: Raw CSV files uploaded via **Azure Data Factory** to **ADLS Gen2**  
2. **Data Cleaning & Transformation**: PySpark scripts in **Databricks** for preparing the dataset  
3. **Data Storage**: Processed data written to **Azure Synapse Lake Database**  
4. **Data Visualization**: Final reporting and insights shown through **Power BI Dashboard**

---

## 📚 Learnings

- Hands-on experience with Azure's **ETL pipeline architecture**
- Working with **PySpark** in a real-world analytics use case
- Integrating **machine learning** into a cloud data pipeline
- Leveraging **Power BI** for data storytelling and insight communication

If you're interested in cloud-based data analytics or working on similar projects, feel free to connect or collaborate!





