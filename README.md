# 🍕 Pizza Sales Analysis

## Overview

This project analyzes pizza sales data to identify sales trends, revenue performance, and product category performance. The analysis was conducted using **Microsoft Excel, Python, and SQL (DuckDB)** to explore the data, answer business questions, and create visualizations.

The results from all three tools were cross-validated to ensure consistency and reliability.

## Objectives

- Analyze overall pizza sales performance.
- Identify monthly revenue and sales quantity trends.
- Examine sales performance by day of the week.
- Compare revenue contributions across pizza categories.
- Generate data-driven insights to support business decisions.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data analysis, calculations, and visualization |
| Python | Data processing, analysis, and visualization |
| SQL (DuckDB) | Data querying, table joins, aggregations, and analysis |
| Google Colab | Python development environment |

## Dataset

The dataset contains four tables:

| Table | Description |
|---|---|
| `orders` | Order dates and times |
| `order_details` | Pizza quantities and order details |
| `pizzas` | Pizza sizes, prices, and product identifiers |
| `pizza_types` | Pizza names, categories, and ingredients |

The tables were combined using SQL JOIN operations to create a master table for further analysis.

### Key Metrics

- **Total Revenue:** Total sales revenue generated.
- **Total Quantity Sold:** Total number of pizzas sold.
- **Revenue by Month:** Monthly revenue performance.
- **Sales by Day of the Week:** Sales distribution across weekdays.
- **Revenue by Pizza Category:** Revenue contribution of each pizza category.

## Business Questions

1. How does revenue change from month to month?
2. Which days of the week generate the most pizza sales?
3. Which pizza categories contribute the most revenue?
4. How does the quantity sold compare across different periods and categories?
5. What business opportunities can be identified from the sales trends?

## Methodology

### 1. Data Preparation
- Reviewed the structure and contents of the source tables.
- Combined related tables to create a master dataset.
- Prepared the data for consistent analysis across tools.

### 2. SQL Analysis
- Used JOIN operations to combine the four tables.
- Applied aggregate functions such as `SUM()` and `COUNT(DISTINCT ...)` where appropriate.
- Grouped data by month, day of the week, and pizza category.
- Calculated revenue contribution percentages.
- Sorted results according to chronological order or revenue performance.

### 3. Python Analysis
- Processed and analyzed the dataset.
- Calculated sales and revenue metrics.
- Created visualizations to communicate the findings.

### 4. Excel Analysis
- Analyzed sales and revenue metrics.
- Created charts to identify trends and compare performance.

### 5. Validation
Compared the corresponding results from Excel, Python, and SQL to confirm that the reported metrics were consistent.

## Visualizations

Visualizations are designed to highlight the following aspects of pizza sales:

- Monthly revenue trends.
- Sales quantity by day of the week.
- Revenue by pizza category.
- Revenue contribution percentage by category.

*Add your exported charts or screenshots to this section when available.*

## Key Findings

*Add the actual findings from your analysis here.*

Examples of findings to document:
- The month with the highest and lowest revenue.
- The day with the highest sales quantity.
- The pizza category with the largest revenue contribution.
- Potential opportunities to improve sales performance.

All findings should be supported by the actual analysis results.

## Business Recommendations

*Develop recommendations based on the findings.*

Potential areas to consider include:
- Sales promotions during lower-performing periods.
- Inventory planning based on sales quantity trends.
- Marketing strategies for high-performing pizza categories.
- Further investigation into products or periods with lower revenue.

Recommendations should be finalized after reviewing the actual results.

## Project Structure

```text
pizza-sales-analysis/
├── README.md
├── excel/
│   └── pizza_sales_analysis.xlsx
├── python/
│   └── pizza_sales_analysis.ipynb
├── sql/
│   └── pizza_sales_analysis.sql
└── visuals/
    ├── monthly_revenue.png
    └── category_revenue.png
```

*The filenames above are examples. Adjust the structure to match the files included in the repository.*

## Conclusion

This project demonstrates the use of Excel, Python, and SQL to analyze sales data, develop visualizations, and derive business insights. Cross-validation across the three tools helps ensure consistency in the analytical results.

The project strengthened practical skills in data preparation, SQL querying, data analysis, visualization, and analytical validation.

---

**Author:** Talitha Almira Zada

**Focus Areas:** Data Analytics | SQL | Python | Microsoft Excel | Data Visualization
