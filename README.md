# sql-data-analytics-project
A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. The repository covers database exploration, metrics analysis, time-based trends, cumulative analytics, segmentation, and more, showcasing best practices to help analysts and BI professionals analyze relational data efficiently.


**Analytics Project: Exploratory & Advanced Data Analysis**

**📌 Project Overview**
This project focuses on Exploratory Data Analysis (EDA) and Advanced Data Analytics using a dataset produced in a prior Data Warehouse project. The goal is to extract insights, identify patterns, and apply analytical techniques on a clean, well-modeled dataset.
This repository intentionally separates analytics work from data engineering to reflect real-world data workflows and best practices.

**🏗️ Upstream Data Source**
Dataset Origin: Data Warehouse Project
Repository Link: https://github.com/adisinha7007/DatawarehouseprojectAS
The dataset used in this project is generated through ETL pipelines, transformations, and schema design implemented in the Data Warehouse project. This analytics project does not recreate or modify the dataset, but consumes it for analysis purposes.

**📊 Dataset Description**
**Domain**: Business Analytics
**Key Tables**
gold.dim_customers
gold.dim_products
gold.fact_sales
**Key Metrics & KPIs**
**Customer-Level Metrics (Aggregated)**
Total orders
Total sales
Total quantity purchased
Total products purchased
Customer lifespan (in months)
**Calculated KPIs:**
Recency (months since last order)
Average Order Value (AOV)
Average Monthly Spend
**Product-Level Metrics (Aggregated)**
Total orders
Total sales
Total quantity sold
Total unique customers
Product lifespan (in months)
**Calculated KPIs:**
Recency (months since last sale)
Average Order Revenue (AOR)
Average Monthly Revenue
⚠️ Note: The dataset is not stored in this repository to avoid duplication. Please refer to the Data Warehouse project for schema and data generation details.

**🔍 Project Objectives**
Perform Exploratory Data Analysis (EDA)
Identify trends, anomalies, and patterns
Engineer analytical features
Apply advanced analytics techniques
Generate actionable insights

**🧠 Analytics Performed**
**1️⃣ Exploratory Data Analysis (EDA)**
The EDA phase focuses on understanding the structure, scope, and behavior of the data produced by the Data Warehouse.
Database Exploration
Overall structure, tables, schema relationships, and row counts
Dimension Exploration
Analysis of categorical dimensions, cardinality, and value distributions
Date and Measure Exploration
Time-related fields, measures, ranges, seasonality checks
Magnitude Exploration
Scale, volume, and spread of key metrics
Ranking Analysis
Top / bottom entities based on key measures
**2️⃣ Advanced Analytics**
This phase focuses on analytical patterns, comparisons, and business-style insights using SQL-based analysis only.
Change Over Time Analysis
Trend analysis, growth/decline patterns, period-over-period comparisons using date functions
Cumulative Analysis
Running totals and cumulative contribution using window functions
Performance Analysis
KPI evaluation, benchmarking, and comparative analysis
Part-to-Whole Analysis
Contribution analysis and percentage share calculations
Data Segmentation
Segmenting entities using SQL logic (CASE statements, grouping)
Reporting
Final analytical queries designed for reporting and dashboard consumption

**📂 Project Structure**
analytics-project/
│
├── sql/
│   ├── 01_database_exploration.sql
│   ├── 02_dimension_exploration.sql
│   ├── 03_date_measure_exploration.sql
│   ├── 04_magnitude_exploration.sql
│   ├── 05_ranking_analysis.sql
│   ├── 06_change_over_time.sql
│   ├── 07_cumulative_analysis.sql
│   ├── 08_performance_analysis.sql
│   ├── 09_part_to_whole.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_reporting.sql
│
├── README.md
└── .gitignore

---

## ⚙️ Tech Stack
- **Language:** SQL
- **Database:** (e.g., PostgreSQL / MySQL / SQL Server / Snowflake)
- **Concepts Used:** Joins, CTEs, Window Functions, Aggregations, Subqueries

---

Ensure access to the dataset as described in the Data Warehouse project
Run notebooks/scripts in sequence

**🔗 Related Projects**
Data Warehouse Project: https://github.com/adisinha7007/DatawarehouseprojectAS
This project is part of a broader data lifecycle demonstrating data engineering → analytics → insights.

**📬 Contact**
For questions or collaboration:
GitHub: https://github.com/adisinha7007
LinkedIn: https://www.linkedin.com/in/aditi-sinha-339479156

