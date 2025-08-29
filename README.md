# SQL-Data-Warehouse-and-Analytics-Project
This project shows how to build a complete data warehouse and analytics solution—from collecting raw data to creating insights that help in decision-making. It follows industry best practices in data engineering and analytics and is designed as a strong portfolio project.

---

## Data Architecture

The solution is designed using the Medallion Architecture with three layers:

- **Bronze Layer (Raw Data):**  
  - Stores data as-is from ERP and CRM source systems.  
  - Data is ingested from CSV files into SQL Server.  

- **Silver Layer (Clean Data):**  
  - Cleans and standardizes raw data.  
  - Ensures accuracy, consistency, and usability.  

- **Gold Layer (Business-Ready Data):**  
  - Transforms clean data into a star schema (fact and dimension tables).  
  - Optimized for reporting and analytics.  

---

## Project Overview

This project covers the end-to-end flow of a modern data warehouse:

1. **Data Architecture** – Build Bronze, Silver, and Gold layers.  
2. **ETL Pipelines** – Extract, Transform, Load (ETL) using SQL scripts.  
3. **Data Modeling** – Create fact and dimension tables for analytics.  
4. **Analytics & Reporting** – Run SQL queries and dashboards for insights.  

---

## Project Requirements

### 1. Data Engineering – Build the Warehouse
**Objective:** Create a SQL Server-based data warehouse to consolidate sales data.  

**Specifications:**  
- **Data Sources:** ERP and CRM datasets provided as CSV files.  
- **Data Quality:** Fix errors, duplicates, and formatting issues.  
- **Integration:** Merge ERP & CRM into a unified, analysis-friendly model.  
- **Scope:** Use only the most recent dataset (no history needed).  
- **Documentation:** Provide clear guidance for business and analytics teams.  

---

### 2. Data Analysis – Analytics & Reporting
**Objective:** Deliver SQL-based insights for business decisions.  

**Analytics focus areas:**  
- Customer Behavior → Best customers, segmentation, and loyalty.  
- Product Performance → Top/bottom products by sales.  
- Sales Trends → Growth, seasonality, and KPIs.  

These insights help managers make data-driven decisions.  

---



