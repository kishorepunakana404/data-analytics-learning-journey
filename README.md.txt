# Week 1 — SQL & Data Import

## Objective
- Learn SQL fundamentals and import CSV data into MySQL using MySQL Workbench.
- Run basic analytical queries and produce quick insights.

## Files
- `sales_data.csv` — sample sales dataset
- `analysis.ipynb` — (for Python analysis later)
- `queries.sql` — SQL queries used this week

## Actions performed
1. Created database `data_analytics` and table `sales` in MySQL.
2. Imported `sales_data.csv` using the Table Data Import Wizard.
3. Ran queries to compute:
   - total rows and total revenue
   - sales by region and top products
   - monthly sales trend (if `OrderDate` present)
   - average quantity by category

## Quick Insights (example)
- Total sales: `<replace-with-number-from-SUM(Sales)>`
- Top region by sales: `<replace-with-region-from-sql>`
- Top product by revenue: `<replace-with-product>`

(Replace the placeholders above with numbers from your query run.)
