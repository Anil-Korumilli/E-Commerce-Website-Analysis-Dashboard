# E-Commerce-Website-Analysis-Dashboard

# 📊 Madhav Sales Analysis Dashboard

🔎 Overview

The Madhav Sales Dashboard is an interactive data visualization and analysis tool built using Power BI. It provides a comprehensive view of sales performance, customer insights, product trends, and regional analysis. The dashboard helps businesses make data-driven decisions by monitoring KPIs and identifying patterns in sales data.

# 🛠 Tech Stack

Power BI – Dashboard creation & data visualization

Excel / CSV (Orders & Details) – Raw data storage

DAX (Data Analysis Expressions) – For calculated measures and KPIs

Power Query – Data transformation and cleaning

# 📂 Data Sources

The analysis is based on the following datasets:

Orders.csv → Contains sales order records including order date, region, category, quantity, sales, and profit.

Details.csv → Contains additional details related to products, customers, and order transactions.

# ✨ Features

✔ Interactive dashboard with filters (by category, region, customer, etc.)

✔ Key metrics: Total Sales, Profit, Quantity Sold, Average Discount

✔ Trend analysis: Monthly & yearly sales performance

✔ Regional insights: Top-performing regions and weak markets

✔ Customer analysis: High-value customers & order patterns

✔ Product analysis: Best-selling and least-performing products

✔ Drill-down capability for deeper insights

# 🔄 Full Process Overview

1.Data Collection

💠Imported datasets (Orders.csv & Details.csv) into Power BI.

2.Data Cleaning & Transformation (Power Query)

💠Removed duplicates and null values.

💠Standardized column names and formats.

💠Created relationships between Orders and Details tables.

3.Data Modeling

💠Established star schema with fact table (Orders) and dimension tables (Details).

💠Built relationships for category, region, and customer analysis.

4.Measure Creation (DAX)

💠Defined calculated fields such as:

💠Total Sales = SUM(Orders[Sales])

💠Total Profit = SUM(Orders[Profit])

💠Profit Margin = DIVIDE([Total Profit], [Total Sales])

💠Sales Growth = (Current - Previous) / Previous

5.Dashboard Design

💠Developed multiple report pages for Sales Overview, Regional Analysis, Customer Insights, and Product Trends.

💠Used slicers, cards, bar charts, line charts, and maps for interactive visuals.

💠Applied filters for Year, Region, Category, and Customer Segments.

6.Final Output

💠Delivered an interactive Power BI dashboard providing real-time business intelligence.

# 📸 Snapshot

![Dashboard Preview](https://github.com/Anil-Korumilli/E-Commerce-Website-Analysis-Dashboard/blob/main/Snapshot%20of%20dashboard.png)


# 🚀 Goal

The goal of this project is to build an end-to-end sales analytics solution that enables businesses to:

💠Monitor KPIs in real-time.

💠Identify sales opportunities and risks.

💠Improve decision-making with actionable insights.
