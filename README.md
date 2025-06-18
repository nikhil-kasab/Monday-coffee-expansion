# ☕ Monday Coffee Expansion Analysis

This repository contains a structured SQL-based data analysis project designed to evaluate potential expansion opportunities for **Monday Coffee**, a fictional coffee retailer. The analysis investigates sales performance, customer demographics, and market potential across multiple cities.

---

## 📌 Project Description

The **Monday Coffee Expansion Analysis** aims to assist business stakeholders in identifying high-potential cities for store expansion based on historical sales, customer behavior, rental costs, and demographic data. All queries and insights are developed using **MySQL**, and the logic is documented in the [`Solutions.sql`](Solutions.sql) file.

---

## 🛠️ Technologies Used

- **MySQL** – SQL query development and execution
- **Structured Query Language (SQL)** concepts:
  - `SELECT`, `JOIN`, `GROUP BY`, `ORDER BY`
  - Aggregate functions: `SUM()`, `COUNT()`, `ROUND()`, `AVG()`
  - Subqueries and Common Table Expressions (CTEs) using `WITH`
  - Window functions: `DENSE_RANK()`, `LAG()`
  - Date functions: `EXTRACT(YEAR|MONTH|QUARTER FROM ...)`
  - Conditional filtering with `WHERE`
  - Data formatting using `::numeric`

---

## 📊 Key Analysis & Features

- **Estimated Coffee Consumers** per city based on population
- **Quarterly Revenue Analysis** (Q4 2023)
- **Top-Selling Products** and sales volumes
- **City-wise Revenue vs. Rent Comparison**
- **Average Sales per Customer**
- **Customer Segmentation** by city and product types
- **Monthly Sales Growth Rate** by city
- **Market Potential Ranking** based on multiple metrics

---

## ❓ Key Business Questions Answered

1. **How many people are likely to consume coffee in each city?**
2. **What was the total coffee sales revenue in Q4 2023, and which cities contributed the most?**
3. **Which coffee products sell the most, and where?**
4. **What is the average sales per customer per city?**
5. **Which cities offer the best balance of revenue and rent cost?**
6. **Which cities show promising customer acquisition trends?**
7. **What are the top 3 selling products in each city?**
8. **How is the monthly sales growth rate evolving by city?**
9. **Which cities show the strongest potential for new store expansion?**

---

## 📁 File Reference

- [`Solutions.sql`](Solutions.sql): Contains all SQL queries structured around key business questions and includes CTEs, joins, window functions, and aggregation logic for deep analysis.

---

## 📬 Contributions

Feel free to fork the repository, suggest improvements, or contribute your own analytical additions via pull requests.
