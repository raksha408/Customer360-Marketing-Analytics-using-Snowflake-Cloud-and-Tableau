#  Customer360 – Marketing Analytics using Snowflake Cloud & Tableau

This project performs a complete Customer 360 Marketing Analysis using **Snowflake Cloud** for cloud data warehousing and **Tableau** for visual analytics.  
All SQL logic, dataset, and dashboard outputs are included in this repository.

---

##  Introduction

The Customer360 Marketing Analytics project focuses on understanding customer behavior using modern cloud data warehousing and business intelligence tools.  
By leveraging **Snowflake** for scalable data processing and **Tableau** for dynamic visualizations, this project provides actionable insights into customer demographics, spending patterns, product preferences, engagement levels, and campaign performance.

The goal is to demonstrate a real-world, end-to-end data analytics workflow—from raw data ingestion to clean visual storytelling—using tools widely adopted in the industry.

---

##  Objectives

This project was designed with the following core objectives:

- **Integrate and prepare customer marketing data** using Snowflake Cloud.
- **Apply analytical SQL queries** to explore, segment, and summarize customer behavior.
- **Identify key customer attributes**, purchasing patterns, and marketing responsiveness.
- **Create rich, interactive Tableau dashboards** for decision-making insights.
- **Showcase end-to-end analytics skills** (ETL, SQL, Cloud, BI visualization) for portfolio and professional demonstrations.

---

##  Scope of the Project

The scope of this project includes the following:

### **1. Data Ingestion & Storage (Snowflake Cloud)**  
- Uploading the cleaned dataset (`marketing_campaign_fixed.csv`) into Snowflake  
- Creating tables and preparing the Customer360 data environment  

### **2. Data Transformation & Querying**  
- Performing data cleaning through SQL  
- Running analytical queries around demographics, spending, engagement, and campaign performance  
- Creating calculated fields such as **Age Group**, **Total Spend**, and **Engagement Score**

### **3. Customer Insight Generation**  
- Understanding income distribution  
- Identifying high-value customers  
- Analyzing product category preferences  
- Evaluating marketing campaign acceptance patterns  

### **4. Visualization & Reporting (Tableau)**  
- Connecting Tableau to Snowflake  
- Designing dashboards and worksheets  
- Exporting dashboards as PDF for review  

### **5. Documentation & Delivery**  
- Preparing SQL scripts (`MASTER_QUERIES.sql`)  
- Exporting Tableau dashboards (`Tableau_pdf.pdf`)  
- Organizing the GitHub repository with dataset and readable project documentation

---

##  Repository Contents 

This repository contains three main project files:

### **1. `MASTER_QUERIES.sql`**  
This file contains all Snowflake SQL queries used in the project.  
It includes segmentation, profiling, spend analysis, engagement scoring, campaign performance, and more.

### **2. `Tableau_pdf.pdf`**  
This is the exported Tableau Dashboard (PDF) containing all worksheets and visualizations created for this project.

### **3. `marketing_campaign_fixed.csv`**  
This is the cleaned dataset uploaded to Snowflake.  
It contains 2,240 customer records including demographics, purchasing behavior, spending, website activity, and campaign responses.

---

##  Project Overview

The project demonstrates:

- Loading data into **Snowflake Cloud**  
- Executing analytical SQL queries  
- Creating customer insights from raw marketing data  
- Building Tableau dashboards connected to Snowflake  
- Exporting dashboard results for portfolio/recruiter review  

This is a practical demonstration of **end-to-end data analytics workflow**.

---

##  Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Snowflake** | Cloud data warehouse & SQL execution |
| **SQL** | Transformations, aggregations, analytics |
| **Tableau Desktop** | Data visualization & dashboarding |
| **CSV Dataset** | Input dataset for analysis |

---

##  Dataset Summary (`marketing_campaign_fixed.csv`)

The dataset includes fields such as:

- **Demographics:** Year_Birth, Education, Marital_Status  
- **Household:** Kidhome, Teenhome  
- **Purchases:** Store, Web, Catalog  
- **Spending:** Wines, Meat, Fish, Sweets, Gold  
- **Campaign Response Flags**  
- **Recency and Enrollment Date**

Total Customers: **2,240**

---

##  SQL Analysis (Stored in `MASTER_QUERIES.sql`)

The SQL file contains all queries, including:

- Customer count  
- Income by marital status  
- Customers by education  
- Latest customer enrollment date  
- Age segmentation + income  
- Product category spending analysis  
- Campaign performance success rates  
- High-value customer (top 10%) detection  
- Engagement score creation

Each query was executed in Snowflake Cloud successfully.

---

##  Tableau Dashboard (Stored in `Tableau_pdf.pdf`)

The Tableau dashboard includes:

- Customer distribution  
- Education & marital segmentation visualizations  
- Average income charts  
- Enrollment trend  
- Age group vs income  
- Category-wise spend comparisons  
- Engagement score heatmap  
- Campaign success metrics  

All visuals were built using Snowflake as the live data source.

---

##  Data Pipeline Summary

1. Load CSV into Snowflake  
2. Execute SQL transformations  
3. Connect Snowflake warehouse to Tableau  
4. Build calculated fields (Age Group, Total Spend, Engagement Score)  
5. Create visual dashboards  
6. Export dashboard as PDF  

---

##  Key Insights

- Customers aged **36–50** spend the most on average  
- “Together” and “Married” customers show higher engagement  
- **Wines** and **Meat** are the top-selling spend categories  
- Campaign responses differ significantly across segments  
- Engagement score reveals hidden customer segments  

---

##  Future Improvements

- Publish dashboard on Tableau Public  
- Add Snowpark/Python for advanced models  
- Build prediction models (Churn/LTV/Response)  

---

##  Author

**Shriraksha Kulkarni**  
Data Analyst | SQL | Snowflake Cloud | Tableau

---

