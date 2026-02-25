# 🎵 music_store_data_analysis | PostgreSQL


## 📌 Project Summary
This project performs an in-depth analysis of a digital music store's database using **PostgreSQL**. By querying the **Chinook Database**, I extracted key business metrics to help the store understand its customer behavior, sales performance, and inventory demand. The project covers everything from basic data exploration to complex multi-level joins and window functions.

## 🎯 Business Objectives
* **Revenue Analysis:** Identify the cities and countries with the highest revenue to plan promotional events.
* **Customer Insights:** Find the most loyal and highest-spending customers.
* **Content Performance:** Determine the most popular genres and artists to guide library expansion.
* **Operational Reporting:** Analyze employee seniority and reporting structures.

## 🗂 Dataset Information
The project uses the **Chinook Dataset**, which mimics a real-world digital media store.
* **Format:** PostgreSQL Custom Format Archive (`PGDMP`).
* **Schema:** 11 interrelated tables including `Invoice`, `Customer`, `Track`, `Artist`, and `Employee`.
* **Complexity:** Features many-to-many relationships and self-referencing tables.

## 🛠 Tools & Technologies
* **Database:** PostgreSQL
* **Query Tool:** pgAdmin 4 or DBeaver
* **SQL Techniques Used:**
    * **Advanced Joins:** Connecting up to 6 tables to link sales back to artists.
    * **Window Functions:** Using `RANK()` and `ROW_NUMBER()` with `PARTITION BY` for category-wise ranking.
    * **CTEs (Common Table Expressions):** For modular and readable code.
    * **Subqueries:** For filtering data based on aggregate benchmarks (e.g., songs longer than average).

## 📊 Key Questions Answered
The project is divided into three levels of difficulty:
1. **Easy:** Senior employees, invoice totals, and top-performing countries.
2. **Moderate:** Rock music listeners, top 10 rock bands, and song length analysis.
3. **Hard:** Spending habits per customer on artists, most popular genres by country, and the top customer per country.

## 📁 Repository Structure
```text
├── Music_Store_database.sql        # The database backup file
├── Customer_anaysis.sql            # Organized SQL scripts for all analysis
└── README.md                       # Project documentation
