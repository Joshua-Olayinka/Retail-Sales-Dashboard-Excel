# Superstore Pricing & Profitability Analysis

An Excel-based analysis of the Superstore retail dataset, examining pricing, discounts, and profitability trends to surface actionable business insights.

## Overview

This project analyzes ~10,000 transaction records from a multi-year retail dataset to understand how pricing decisions, discounting, and product category mix affect profitability. The goal was to move beyond raw sales figures and identify *where* a retail business is actually making or losing money, and why.

## Dataset

- **Source**: Sample Superstore dataset (Kaggle)
- **Size**: 9,993 orders, 2014–2017
- **Fields**: Order/ship dates, customer segment, region, product category and sub-category, sales, quantity, discount, and profit

## Tools & Methods

- **Excel** (pivot tables, SUMPRODUCT and aggregation formulas, conditional formatting)
- **Pivot Table Reports**: sales and profit broken down by year/quarter/month, region, category, and shipping mode
- **Analysis & Calculations sheet**: total revenue, profit margin, average discount rate by category, top products by sales, and average order value
- **Sales Performance Dashboard**: visual summary of trends across category, region, and time
- **Discount grouping**: orders bucketed into discount bands (e.g. 0–10%, 10–20%) to isolate the relationship between discount depth and profit

## Dashboard

![Sales Performance Dashboard](images/dashboard.png)

The dashboard ties the analysis together in one view: total revenue ($2.30M), total profit ($286K), and overall profit margin (12%) at a glance, with year and month slicers to filter by period. It also breaks out sales and profit by region, customer segment, and discount band, and ranks sub-categories by profit, the same view that surfaces Tables and Storage as the two sub-categories operating at a loss.

## Key Findings

- **Technology was the most profitable category** ($145,455 in profit), while **Furniture lagged behind** ($18,463), despite reasonable sales volume.
- **Higher discount rates eroded margins** — the dashboard's "Discount % vs Profit Margin" chart shows profit margin turning sharply negative once discounts pass 50%. Furniture was hit hardest, with the highest average discount rate (17.4%) of the three categories and the lowest average profit per order.
- **November consistently posted the highest sales** across multiple years, pointing to a clear seasonal demand pattern (holiday shopping).
- **Tables, specifically, generated negative profit overall** — a sub-category where aggressive discounting outweighed the margin on each sale.
- Regionally, the **Central region's Furniture sales operated at a loss**, while Technology stayed profitable across all four regions.

## Why It Matters

These insights highlight clear pricing and operational inefficiencies. The business should tighten discounting policies on Furniture and eliminate loss-making sub-categories such as Tables. Technology should be protected as the primary profit driver with controlled discount exposure. Additionally, demand forecasting should be aligned with the November peak period to optimize inventory planning and staffing efficiency.

## Author

**Joshua Olayinka**
