# Superstore Sales Analysis using SQL

## Project Overview
This project focuses on analyzing a retail Superstore dataset using SQL to understand sales performance, profitability, discounts impact, and product-level insights.  
The goal is to answer real-world business questions and support data-driven decisions.

---

## Tools & Technologies
- MySQL
- SQL (CTE, Window Functions, Aggregations)
- Superstore Dataset

---
## Dataset Description
The dataset contains order-level sales data including:
- Orders & shipping dates
- Customer and product details
- Sales, quantity, discount, and profit information

## Data Cleaning & Preparation
- Created structured tables
- Checked and handled NULL values
- Removed duplicate records using `ROW_NUMBER()`
- Converted date columns to proper DATE format
- Added derived columns:
  - `profit_status` (Discontinued / Keep)
  - `discount_flag` (Discounted / Non-Discounted)

---
## Key Business Questions Answered
- Total sales, profit, and quantity sold
- Overall profit margin
- Categories with highest sales and profit
- Loss-making products and sub-categories
- Products to discontinue or reprice
- Impact of discounts on sales and profit
- Discounted vs non-discounted order performance

---

## Key Insights
- Certain products generate high sales but negative profit
- Discounted orders increase quantity sold but reduce overall profit
- Some sub-categories consistently operate at a loss
- Discount strategy needs optimization at category level

---

## Skills Demonstrated
- Data cleaning using SQL
- Window functions (`ROW_NUMBER`)
- Business KPI calculations
- Analytical thinking and decision-making
- Writing optimized and readable SQL queries

---
## Project Structure
- `sql_queries.sql` → All SQL queries used for analysis
- `screenshots/` → Output screenshots of important queries
- `README.md` → Project documentation

---

## Conclusion
This project demonstrates how SQL can be used to clean data, analyze business performance, and derive actionable insights for strategic decision-making.

---

## Author
**Suruthi Sri**  
Aspiring Data Analyst
