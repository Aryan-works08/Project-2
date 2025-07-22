# SQL Sales Analytics Project

This project demonstrates data analysis using **PostgreSQL** on a sales dataset. It covers beginner to advanced SQL concepts including filtering, aggregation, grouping, window functions, subqueries, and more.

---

## Dataset Description

The dataset contains sales transaction records with the following columns:

| Column Name     | Data Type     | Description                                 |
|-----------------|---------------|---------------------------------------------|
| Rep             | VARCHAR(15)   | Name of the sales representative            |
| Region          | VARCHAR(8)    | Sales region                                |
| Deals_Date      | DATE          | Date when the deal was closed               |
| Sales_Closed    | INT           | Number of deals closed                      |
| Revenue         | INT           | Revenue generated from the deal             |
| Customer_Type   | VARCHAR(10)   | Type of customer (e.g., New, Returning)     |
| Product         | VARCHAR(10)   | Product sold (e.g., Laptop, Phone, etc.)    |

---

## Objectives

- Perform data cleaning and filtering.
- Analyze sales performance by rep, region, and product.
- Use aggregate functions and groupings.
- Apply window functions for rankings and cumulative insights.
- Extract advanced business insights using subqueries.

---

## Tools & Technologies

- **PostgreSQL** (SQL database)
- **psql** CLI / pgAdmin
- **Git** for version control
- Optional: **Excel** / **Power BI** for visualization (not part of this repo)

---

## Key SQL Topics Covered

- Basic SELECT, WHERE, ORDER BY
- Aggregate Functions: `SUM()`, `AVG()`, `COUNT()`, `MAX()`
- GROUP BY and HAVING
- Joins and subqueries
- Window Functions: `RANK()`, `ROW_NUMBER()`, `SUM() OVER()`, `AVG() OVER()`
- Date functions and filtering
- Handling NULLs and calculated fields
