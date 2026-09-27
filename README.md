Here is the README based on the project details, methodology, and findings from your data analytics career simulation:

# Data Analytics and Visualization – Career Simulation 2

## Project Overview

This project involves examining an ecommerce sales dataset comprising **34,500 transaction records** using SQL for data processing and Power BI to build an interactive dashboard showcasing key business metrics.

* **Developer**: Brenden Heitz



---

## Methodology & Workflow

1. **Data Sourcing & Configuration**: The real-world ecommerce dataset was imported into MySQL and organized under the `sales_project` database within the `sales_transactions` table.


2. **Data Processing & SQL Analysis**: Row counts were verified, sample records were inspected, and core measures were computed using SQL queries (including total sales over time, category/region breakdowns, and average order value).


3. **Power BI Dashboard Construction**: Built using Power BI Desktop (`Project2_SalesDashboard.pbix`), combining visuals for total sales over time, regional distribution, category performance, and order value insights.



---

## Key Dashboard Metrics & Findings

* **Sales Trends Over Time**: Sales peaked in **2024** relative to both 2023 and 2025.


* **Sales by Category**: **Electronics** was the top-performing product segment, followed by Home and Sports.


* **Sales by Region**: The **South** recorded the highest sales figures, with notable contributions from the North and West regions.



---

## Technical Challenges & Solutions

* **MySQL Secure Import Directory**: Loading the CSV file initially restricted imports to a specific secure directory; this was resolved by locating the correct `secure_file_priv` path and moving the file to the designated Uploads folder.


* **Date-Based Querying**: Grouping data for time-series analysis was addressed by applying a compatible date-grouping approach.


* **Power BI Interface**: Handled by building visuals incrementally (line chart $\rightarrow$ category/region charts $\rightarrow$ full integration) and testing interactivity.