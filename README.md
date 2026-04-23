# 🚀 Microsoft Fabric Labs

This repository contains my hands-on practice and tasks while learning **Microsoft Fabric (Analytics Engineer)**.

The goal of this repo is to document my learning journey, practice real-world scenarios, and build a strong portfolio for data engineering roles.

---

## 📌 Modules

In this repository, I covered the following modules from the **Microsoft Fabric Analytics Engineer (DP-600T00)** course:


### 🔹 Get started with Microsoft Fabric:

* Introduction to end-to-end analytics using Microsoft Fabric  ✅
* Get started with lakehouses in Microsoft Fabric  ✅
* Use Apache Spark in Microsoft Fabric  ✅
* Work with Delta Lake tables in Microsoft Fabric ✅
* Orchestrate processes and data movement with Microsoft Fabric  ✅
* Ingest Data with Dataflows Gen2 in Microsoft Fabric  ✅
* Get started with data warehouses in Microsoft Fabric  ✅
* Get started with Real-Time Intelligence in Microsoft Fabric ✅
* Get started with data science in Microsoft Fabric ✅
* Administer a Microsoft Fabric environment
  
### 🔹 Implement a data warehouse with Microsoft Fabric:

* Get started with data warehouses in Microsoft Fabric
* Load data into a Microsoft Fabric data warehouse
* Query a data warehouse in Microsoft Fabric
* Monitor a Microsoft Fabric data warehouse
* Secure a Microsoft Fabric data warehouse

### 🔹 Work with semantic models in Microsoft Fabric:

* Create DAX calculations in semantic models
* Design scalable semantic models
* Optimize a model for performance in Power BI
* Create and manage Power BI assets
* Enforce Power BI model security

### 🔹 Administer and govern Microsoft Fabric:

* Administer a Microsoft Fabric environment
* Secure data access in Microsoft Fabric
* Secure a Microsoft Fabric data warehouse
* Govern data in Microsoft Fabric with Purview

---

## 🧪 Tasks
These tasks are based on Microsoft Learn labs and extended with my own notes and experiments.

### 🔹 Task 1: Create a Microsoft Fabric lakehouse

Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/01-lakehouse.html)

In this task:

* Created a new workspace in Microsoft Fabric
* Created a Lakehouse for storing and managing data
* Explored the Lakehouse structure:
  - Files (raw data storage)
  - Tables (structured Delta tables)
* Uploaded a CSV file (sales.csv) into the Files section
* Created a new table from the uploaded file
* Explored the underlying storage (Parquet + Delta format)
* Queried data using SQL endpoint
* Created aggregations (total revenue per product)
* Built a visual query using Power Query interface
---

### 🔹 Task 2: Analyze Data with Spark

Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html)

In this task:

* Created a workspace and lakehouse
* Loaded sales data into Spark
* Defined schema manually
* Filtered and grouped data
* Created derived columns (Year, Month, FirstName, LastName)
* Saved transformed data as Parquet
* Applied partitioning (Year/Month)
* Queried data using Spark SQL
* Created visualizations using built-in charts and Matplotlib

---

### 🔹 Task 3: Use delta tables in Apache Spark

Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/03-delta-lake.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/03-delta-lake.html
)

In this task:

* Created Delta tables from DataFrames
* Differentiated between managed and external tables
* Performed data operations using Spark SQL (INSERT, UPDATE)
* Used Delta Lake API to update data directly from file paths
* Explored table history using DESCRIBE HISTORY
* Used Time Travel to read previous versions of data
* Optimized tables using Optimize Write and OPTIMIZE
* Applied V-Order to improve read performance
* Used VACUUM to clean up old data files
* Applied partitioning to improve query performance
* Worked with streaming data using Spark Structured Streaming
* Read streaming data from source files
* Transformed streaming data (filtering, derived columns)
* Wrote streaming data to Delta tables (sink)
* Used checkpointing for fault tolerance in streaming
* Stopped streaming jobs to avoid unnecessary resource usage

---

### 🔹 Task 5: Dataflows (Gen2) Lab

Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/05-dataflows-gen2.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/05-dataflows-gen2.html)

In this task:

* Create Dataflow (Gen2)
* Load & Transform Data
* Add Data Destination & run Dataflow
* Use Dataflow in Pipeline & Verify data

---

### 🔹 Task 6: Analyze data in a data warehouse
Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/06-data-warehouse.html
](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/06-data-warehouse.html
)

In this task:

* Create Data Warehouse
* Create Tables & Load Data (Use T-SQL & Visual Query)
* Create View
* Creating a Data Model (Semantic Model) & Define relationships

---

### 🔹 Task 7: Real-Time Intelligence
Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/07-real-time-Intelligence.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/07-real-time-Intelligence.html)

In this task:

* Create an eventstream & eventhouse
* Query the captured data
* Create a real-time dashboard
* Create an alert


---

### 🔹 Task 8: Data science
Based on the official lab:
👉 [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/08-data-science-get-started.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/08-data-science-get-started.html)

In this task:

* Learn end-to-end data science workflow in Microsoft Fabric (ingest → explore → prepare → train → track → save models)
* Create Notebook and Ingest & Explore Data
* Prepare Data and Train Machine Learning Models:
  1. Regression Model: Predict continuous value (Y)
  - Use: LinearRegression (scikit-learn)
    
  2. Classification Model: Predict binary label (Risk)
  - Use: LogisticRegression
* Track & Evaluate Models

---

## 🛠️ Technologies Used

* Microsoft Fabric
* Apache Spark (PySpark)
* Spark SQL
* Delta Lake
* Parquet
* Python (Matplotlib)

---

## 📷 Screenshots

Each task contains a `screenshots/` folder to show outputs and visualizations.

---

## 🔗 Resources

* Microsoft Learn:
  [https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html](https://microsoftlearning.github.io/mslearn-fabric/Instructions/Labs/02-analyze-spark.html)
