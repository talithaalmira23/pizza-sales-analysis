# 🍕 Pizza Sales Analysis

## Overview

This project analyzes pizza sales data to evaluate sales performance and generate business insights using **Microsoft Excel, Python, and SQL (DuckDB)**.

The same analytical process was implemented across all three tools to demonstrate practical data analysis skills in different environments. The results were then compared to verify consistency and reliability.

## Objectives

- Analyze overall pizza sales performance.
- Calculate key sales metrics, including total revenue, total orders, total quantity sold, and Average Order Value (AOV).
- Evaluate revenue performance across pizza categories.
- Identify opportunities for data-driven business decisions.
- Apply and compare data analysis techniques using Excel, Python, and SQL.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data analysis, calculations, and visualization |
| Python | Data processing, analysis, and visualization |
| SQL (DuckDB) | Data querying, table joins, aggregations, and analysis |
| Google Colab | Python development environment |

## Dataset

The dataset consists of four tables:

| Table | Description |
|---|---|
| `orders` | Order dates and times |
| `order_details` | Order details and pizza quantities |
| `pizzas` | Pizza sizes, prices, and product identifiers |
| `pizza_types` | Pizza names, categories, and ingredients |

The tables were combined to create a master dataset for the analysis.

## Key Metrics

- **Total Revenue:** Total sales revenue generated.
- **Total Orders:** Total number of unique orders placed.
- **Total Quantity:** Total number of pizzas sold.
- **Average Order Value (AOV):** Average revenue generated per order.

## Business Questions

1. What is the overall sales performance of the business?
2. What is the average revenue generated per order?
3. Which pizza categories contribute the most revenue?
4. How is total revenue distributed across pizza categories?
5. What business opportunities can be identified from the analysis?

## Methodology

The same analytical workflow was applied using Excel, Python, and SQL.

### 1. Data Preparation
- Reviewed the structure and contents of the source tables.
- Combined related tables into a master dataset.
- Prepared the data for analysis.

### 2. Data Analysis
- Calculated total revenue, total orders, and total quantity sold.
- Calculated Average Order Value (AOV).
- Analyzed revenue by pizza category.
- Calculated each category's contribution to total revenue.

### 3. Data Visualization
- Created charts to communicate sales performance and revenue distribution.
- Presented analytical results in a format suitable for business interpretation.

### 4. Cross-Tool Validation
- Compared corresponding metrics and analytical results across Excel, Python, and SQL.
- Verified that the results were consistent across all three tools.

## Key Findings

*To be completed with actual results from the analysis.*

Key findings may include:
- Overall sales performance based on total revenue and quantity sold.
- Average revenue generated per order.
- Pizza categories with the highest revenue.
- Revenue contribution of each pizza category.

## Business Recommendations

1. Revenue & Menu Optimization Strategy
- High-Margin Menu Bundling: Combine high-value items like The Thai Chicken Pizza ($43,434.25 total revenue) and The California Chicken Pizza with secondary high-margin sides or drinks. Creating themed "Premium Combo Deals" will increase the overall Average Order Value (AOV) above the current $38.31 benchmark.
- Volume Leader Cross-Selling: Leverage popular volume sellers like The Classic Deluxe Pizza (2,453 units sold) and The Hawaiian Pizza (2,422 units) as anchor items in family-style bundles to clear excess stock or promote newer menu items.
- Menu Engineering & Layout: Redesign physical and digital menus to highlight top revenue drivers (Thai Chicken, Barbecue Chicken, and California Chicken) at the primary focal points to encourage higher-ticket purchases.

2. Supply Chain & Inventory Control
- Ingredient Forecasting: Align inventory management strictly with sales volume. Key ingredients for The Barbecue Chicken Pizza—a top performer in both units sold and total revenue—must be prioritized in stock replenishment to eliminate out-of-stock scenarios.
- Perishable Waste Reduction: Tailor prep levels based on daily volume patterns (day_name) to ensure dough and fresh toppings are prepared efficiently, minimizing food waste during slow days.

3. Operational & Staffing Efficiency
- Peak Hour Staffing: Use hourly transaction logs (hour) to structure kitchen staff and delivery driver schedules around peak order times, ensuring shorter preparation times and improved customer satisfaction.
- Off-Peak Promotional Campaigns: Introduce targeted "Happy Hour" discounts or mid-week promotions during slow operational hours to balance store capacity and maximize equipment usage throughout the day.

## Conclusion

This project demonstrates the application of Microsoft Excel, Python, and SQL to the same pizza sales analysis workflow. By implementing the analysis in three different tools and cross-validating the results, the project showcases practical skills in data preparation, querying, calculations, visualization, and analytical validation.

---

**Author:** Talitha Almira Zada

**Focus Areas:** Data Analytics | SQL | Python | Microsoft Excel | Data Visualization
