# Sales Performance Analysis

## Project Overview

This project analyzes retail sales data using Python and Power BI to identify sales trends, customer purchasing behavior, and performance across product categories, regions, and customer segments.

The objective is to transform raw sales data into meaningful business insights that support data-driven decision-making.

## Business Objectives

* Analyze annual sales performance and year-over-year changes.
* Identify the highest-performing product categories.
* Compare sales performance across regions.
* Understand sales distribution across customer segments.
* Investigate factors contributing to sales declines.
* Build an interactive dashboard to support business analysis.

## Tools

* Python (Pandas)
* Jupyter Notebook
* Power BI

## Dataset

The project uses the Superstore-style Sales Forecasting dataset.

**Source:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

The dataset is not included in this repository. Please obtain it from the original source.

## Key Insights

1. **Overall Sales Performance:** Total sales reached approximately 2.26 million. Sales declined by 4.26% in 2016, then increased by 30.64% in 2017 and 20.30% in 2018.

2. **Top Category:** Technology generated the highest sales at approximately 827,455.87, followed by Furniture and Office Supplies.

3. **Regional Performance:** The West region recorded the highest sales at approximately 710,219.68, while the South recorded the lowest at approximately 389,151.46.

4. **Customer Analysis:** Office Supplies sales declined by approximately 10.96% from 2015 to 2016. Although 174 new customers were acquired, sales from retained customers decreased.

5. **Sub-Category Analysis:** Binders experienced the largest decline among retained customers, decreasing by approximately 15,949.10. Supplies also experienced a significant decline.

6. **Customer Segment:** Corporate experienced the largest sales decline in Office Supplies, while its order count remained almost unchanged.

7. **Shipping Performance:** Average shipping duration was approximately 3.96 days. Standard Class had an average shipping duration of approximately 5 days.

## Dashboard

![Sales Performance Dashboard](dashboard.png)

The Power BI dashboard includes:

* Total Sales
* Total Orders
* Sales by Category
* Sales by Region
* Sales by Customer Segment
* Sales by Sub-Category
* Annual Sales Trend
* Year and Region filters

## Files

* `sales_analysis.ipynb` — Python analysis notebook.
* `Sales_Performance_Dashboard.pbix` — Interactive Power BI dashboard.
* `dashboard.png` — Dashboard preview.

## Conclusion

This project demonstrates the use of Python for exploratory data analysis and Power BI for interactive sales reporting. The analysis identifies overall sales trends, customer purchasing behavior, and specific areas contributing to declining sales.

These findings provide a foundation for further investigation and more informed business decisions.
