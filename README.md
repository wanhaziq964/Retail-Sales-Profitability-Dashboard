# Global Retail Sales Performance & Profitability Dashboard

This project analyzes over 34,000 retail transactions to understand where a multinational retailer is actually profitable. It covers the full workflow from raw data to a stakeholder-ready dashboard: cleaning the data in Python, exploring it for patterns, then building an interactive Power BI dashboard.

![Dashboard Preview](dashboard-preview.png)

## Problem Statement

A retailer selling Accessories, Clothing, and Bikes across the US, UK, France, and Germany had no consolidated view of its own profitability. Leadership could see individual transactions but had no easy way to tell which regions, products, or customer segments were actually driving profit. This made it difficult to plan marketing spend or catch pricing issues. This project builds that view.

## Dataset

- **Source:** Kaggle, Sales Data for Economic Data Analysis (https://www.kaggle.com/datasets/abhishekrp1517/sales-data-for-economic-data-analysis/data)
- **Size:** 34,866 transactions after cleaning, 15 columns
- **Coverage:** January 2015 to July 2016, across the United States, United Kingdom, France, and Germany
- **Fields:** transaction date, customer age and gender, country and state, product category and sub category, quantity, unit cost and price, and total cost and revenue

## Approach

**Data Cleaning (Python, pandas)**
Removed a blank row, dropped an unused column, corrected data types, confirmed there were no duplicate records, and derived Profit and Profit Margin from Revenue and Cost.

**Exploratory Data Analysis (Python, matplotlib)**
Looked at performance by product category, country, gender, age group, and month to surface the patterns worth building into the dashboard.

**Dashboard Build (Power BI)**
Built an interactive dashboard with KPI cards for revenue, profit, and margin, a monthly revenue and profit trend chart, a category level revenue versus margin chart, and slicers for country and customer age so a stakeholder can explore the data themselves.

## Key Findings

Bikes generate the most revenue of any category but have the weakest margin, at roughly 2.9%. Accessories brings in less revenue but holds the strongest margin, around 18.6%. This is worth a closer look at Bikes pricing or cost structure.

The United States drives the most revenue but has one of the weakest margins, around 6.8%. Germany produces less revenue overall but is by far the most profitable market, with a margin near 22.6%.

Customers aged 25 to 44 make up the majority of total revenue, making this group the core demographic for marketing focus.

Profitability improved substantially from 2015 into 2016. Profit grew faster than revenue over that period, which points to improving margins rather than just higher sales volume.

## Skills Demonstrated

**Technical:** Python (pandas, matplotlib), data cleaning and validation, DAX measures, Power BI dashboard development, Git and GitHub version control

**Analytical:** profitability analysis, customer segmentation, geographic and category performance analysis, stakeholder facing data storytelling

## How to Run This Project

1. Open the Jupyter notebook in VS Code or Jupyter Lab to see the data cleaning and exploratory analysis (requires Python with pandas, numpy, and matplotlib installed)
2. Open the .pbix file in Power BI Desktop to explore the interactive dashboard

## Data Source

Dataset sourced from Kaggle. This project was built as a self directed portfolio piece to practice the full data analysis workflow, from raw data through to a stakeholder ready dashboard.

---
Created by Wan Haziq
