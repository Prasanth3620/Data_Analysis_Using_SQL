# Retail SQL Analysis Project

This project focuses on analyzing data from a retail company that sells bikes and bike components. The dataset includes customer details, sales transactions, and product information.

## Dataset Overview

- **Customers Table**: Contains customer ID, name, and demographic information.
- **Sales Table**: Includes order date, customer ID, product ID, quantity, price, etc.
- **Products Table**: Contains product ID, name, category, subcategory, and cost.

## Analyses Performed

### 1. Dimensions Exploration
- Explored structure and data types of dimension tables.

### 2. Date Range Exploration
- Identified the start and end dates of sales and customer activity.

### 3. Measures Exploration
- Calculated total sales, average order values, total orders, and other key metrics.

### 4. Magnitude Analysis
- Grouped and summarized data by customer, product, and category.

### 5. Ranking Analysis
- Ranked top customers and products based on sales and order frequency.

### 6. Change Over Time Analysis
- Tracked changes in key metrics over months and years.

### 7. Cumulative Analysis
- Created running totals and moving averages to observe growth trends.

### 8. Performance Analysis (YoY, MoM)
- Compared month-over-month and year-over-year performance.

### 9. Data Segmentation Analysis
- Segmented data by customer type, product category, and region.

### 10. Part-to-Whole Analysis
- Analyzed contributions of categories and products to total revenue.

## Summary Reports

### Customer Report
- Customer segmentation (VIP, Regular, New)
- Total orders, sales, and quantity purchased
- Lifespan and recency
- Average order value and monthly spend

### Product Report
- Product segmentation (High, Mid, Low Performers)
- Total sales, quantity sold, and order count
- Number of unique customers
- Recency, average order revenue, and monthly revenue

## Tools Used

- **SQL** (MySQL)
- Basic and advanced queries including:
  - `JOIN`, `GROUP BY`, `ORDER BY`
  - Window functions like `RANK()`, `ROW_NUMBER()`, `SUM() OVER`

## How to Use

Each SQL file in the repository contains a specific analysis or report. Open the file to view the query and the purpose of the analysis. All queries are commented for clarity.


