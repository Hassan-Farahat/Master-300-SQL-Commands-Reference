# Master 300 SQL Commands & Queries Reference (T-SQL / SSMS)

## 🚀 Executive Overview
This repository contains an exhaustive, production-grade master catalog of **300 distinct SQL queries, commands, and script blocks** optimized for Microsoft SQL Server Management Studio (SSMS / T-SQL). 

Designed for data professionals, analytics engineers, and technical interview candidates, this project bridges the gap between academic SQL learning and elite enterprise execution. It features a complete automated mock data environment followed by line-by-line executable queries spanning junior problem-solving, mid-level window functions, senior optimization, advanced data cleaning, and business KPI tracking.

---

## 🛠️ Repository Architecture & Script Structure

The master execution script (`The Script.sql`) is structured into two comprehensive tracks:

### **Setup & Mock Data Framework**
- Automatically builds the reference database (`MasterSQLReference300`) and provisions fully populated relational mock tables (e.g., `employees`, `departments`, `customers`, `orders`, `products`, `sales`, `metrics`, `staging`, `subscriptions`).
- Seeds diverse multi-datatype data including JSON strings, date ranges, and edge-case values for rigorous testing.

### **Track 1: Technical Interview Mastery (Queries 1–150)**
* **Level 1: Junior Queries (1–50):** Fundamental CRUD operations, filtering (`WHERE`, `LIKE`, `BETWEEN`, `IS NULL`), multi-table joins (`INNER`, `LEFT`, `RIGHT`, `FULL OUTER`, `CROSS`, `Self-Join`), aggregations (`GROUP BY`, `HAVING`), set operators (`UNION`, `INTERSECT`, `EXCEPT`), and basic DDL/DML.
* **Level 2: Mid-Level Queries (51–100):** Advanced window functions (`ROW_NUMBER`, `RANK`, `DENSE_RANK`, `LAG`, `LEAD`, `FIRST_VALUE`, `NTILE`), Common Table Expressions (CTEs), multi-CTE architectures, recursive sequence generators, correlated subqueries, conditional aggregation pivoting, and precise date/string manipulations.
* **Level 3: Senior & Lead Queries (101–150):** Recursive organizational graph traversal, Bill-of-Materials (BOM) explosions, dynamic pivoting, execution plan analysis, index tuning strategies (B-Tree, composite, filtered), transaction isolation levels, security management, stored procedures, scalar functions, triggers, and performance diagnostics.

### **Track 2: Daily Production Job Tasks (Queries 151–300)**
* **Category 4: Data Cleansing & Hygiene (151–200):** Enterprise ETL operations, string sanitization (`LTRIM`, `RTRIM`, whitespace stripping), regex pattern cleaning, null imputation (`COALESCE`, `NULLIF`), type casting (`TRY_CAST`, `CAST`), date formatting, outlier detection via Z-score logic, and checksum validations.
* **Category 5: Business Analytics & KPI Tracking (201–250):** Time-series financial metrics, Month-over-Month (MoM) & Year-over-Year (YoY) growth calculations, cohort analysis, Recency-Frequency-Monetary (RFM) modeling, cumulative Pareto distributions, moving averages, rolling sums, and executive scorecard metrics.
* **Category 6: Database Engineering & Optimization (251–300):** Upserts (`MERGE`), Slowly Changing Dimensions Type 2 (SCD2) lifecycle logic, batch processing controls to prevent table lockouts, statistics updates, index rebuilding, and concurrency monitoring.

---

## 💡 Key Technical Highlights & Highlights for Interviews

- **T-SQL Compliance:** Written natively for SQL Server Management Studio (SSMS), addressing differences like `TOP` vs. `LIMIT`, `STRING_AGG`, and `IDENTITY` management.
- **Robust ETL Pipeline Simulation:** Demonstrates how raw ingestion staging fields transition cleanly into enterprise reporting star schemas.
- **Advanced Problem Solving:** Includes solutions for classic data engineering challenges such as *Gaps and Islands*, *Hierarchical Paths*, and *Dynamic SQL Generation*.

---

## ⚙️ How to Run the Script

1. Open **SQL Server Management Studio (SSMS)** and connect to your SQL Server instance.
2. Open a new query window, copy the contents of `The Script.sql`, and paste them into the editor.
3. Execute the script (`F5`). It will automatically create the database, build all mock tables, seed sample data, and process all 300 statements error-free.

---

## 👤 Author
**Hassan Mohamed Hassan Farahat**  
*Data Analyst | MBA & MIS Professional*  
[GitHub Profile](https://github.com/Hassan-Farahat)