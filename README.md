
SQL Music Store Analysis Project
📌 Project Overview

This project is based on the Chinook (Music Store) Database.
The goal of this project is to analyze customer behavior, sales performance, and music trends using SQL queries.


The objective is to analyze:

* Customer purchasing behavior
* Revenue trends
* Popular music genres
* Top-performing artists
* Country-wise and city-wise sales insights

The project is structured into **Easy, Moderate, and Advanced SQL problems**, progressing from basic aggregation queries to advanced analytical SQL using CTEs and window functions.



## 🗂️ Database Description

The Chinook database simulates a digital music store containing the following core entities:

* **Artist** – Music creators
* **Album** – Collection of tracks
* **Track** – Individual songs
* **Genre** – Music category
* **Customer** – Buyers
* **Invoice** – Purchase transactions
* **InvoiceLine** – Detailed transaction records
* **Employee** – Store representatives
* **Playlist / PlaylistTrack** – Music collections

The schema represents relationships between customers, invoices, artists, and music tracks.

---

## 🧠 Business Problems Solved

### 🟢 Easy Level

* Identify the senior-most employee
* Find countries with the most invoices
* Determine top 3 invoice totals
* Identify highest revenue-generating city
* Find the best customer (highest spender)

### 🟡 Moderate Level

* Retrieve all Rock music listeners
* Find top 10 Rock artists by track count
* Identify tracks longer than average length

### 🔴 Advanced Level

* Calculate amount spent by each customer on artists
* Determine most popular genre per country
* Identify top-spending customer per country (handling ties)

---

## 🛠️ SQL Concepts Used

This project demonstrates strong command over:

* `SELECT`, `WHERE`, `ORDER BY`
* `GROUP BY`, `HAVING`
* `SUM()`, `COUNT()`, `AVG()`
* `INNER JOIN`
* Subqueries
* `DISTINCT`
* CTE (`WITH`)
* Window Functions (`ROW_NUMBER()`)
* Partitioning (`PARTITION BY`)
* Recursive CTE
* Ranking logic
* Business aggregation analysis

---

## 📊 Key Insights Extracted

* Identified highest revenue-generating cities for marketing decisions
* Determined top customers for loyalty targeting
* Found most popular music genres country-wise
* Ranked artists based on performance
* Compared spending behavior across regions

---

## 🚀 How to Run the Project

1. Download the Chinook database
2. Import it into:

   * SQLite / PostgreSQL / MySQL
3. Open SQL editor
4. Execute queries from:

   * `easy.sql`
   * `moderate.sql`
   * `advanced.sql`

---

## 📁 Project Structure

```
📦 Chinook-SQL-Analysis
 ┣ 📜 easy.sql
 ┣ 📜 moderate.sql
 ┣ 📜 advanced.sql
 ┗ 📜 README.md
```

---

## 🎯 Skills Demonstrated

* Data Analysis using SQL
* Business Query Formulation
* Analytical Thinking
* Database Schema Understanding
* Advanced Query Optimization
* Real-world Problem Solving

---

## 📌 Why This Project Matters

This project simulates real-world business analytics scenarios such as:

* Revenue optimization
* Customer segmentation
* Regional demand analysis
* Product popularity tracking

It reflects practical SQL skills required for:

* Data Analyst
* Business Analyst
* Data Scientist roles

---

