# Task 6: Sales Trend Analysis Using Aggregations

##  Objective
This task involves analyzing **monthly sales trends** using SQL aggregation techniques. We aim to extract insights such as monthly revenue, order volume, average order value, and identify top-performing months and products.

---

## Tools Used
- SQL
- Any SQL execution environment (e.g., pgAdmin, DBeaver, SQLite Studio)

---

## Dataset Structure
We work with a single table: `online_sales`

| Column Name | Description                     |
|-------------|---------------------------------|
| order_id    | Unique ID for each order        |
| order_date  | Date when the order was placed  |
| amount      | Total revenue of the order      |
| product_id  | ID of the product ordered       |

---

##  Sample Data

Dummy data has been provided covering various months of 2024 to simulate real-world scenarios. This includes different products and transaction values.

---

##  Key SQL Queries

###  1. Monthly Revenue and Order Volume
Groups data by year and month to calculate revenue and number of orders.

###  2. Top 3 Months by Revenue
Returns the three months with the highest total sales.

###  3. Monthly Average Order Value (AOV)
Calculates the average revenue per order for each month.

###  4. Total Sales by Product
Identifies which products generated the most revenue and how often they were ordered.

###  5. Daily Sales Trend (March 2024)
Shows daily breakdown of revenue and volume for a specific month.

---

##  Files Included

- `sql query script ` – Full SQL script with table creation, dummy data, and analysis queries.

---

##  Learning Outcomes

- Grouping and filtering data by time
- Using aggregation functions like `SUM`, `COUNT`, `AVG`
- Handling NULLs in aggregate calculations
- Extracting actionable business insights from transactional data

