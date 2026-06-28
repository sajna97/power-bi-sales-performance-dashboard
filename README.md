Sales Performance Dashboard — Power BI

An interactive sales performance dashboard built in Power BI Desktop, using Microsoft's free Financial Sample dataset. This project was built end-to-end as a hands-on learning exercise — from data cleaning and modeling to DAX measures and final report design.

📊 What's in the report

The dashboard has three pages:

1. Sales Summary


KPI cards for Total Sales, Total Profit, and Sales YoY %
Bar chart: Sales by Country (with gradient coloring)
Line chart: Sales trend across 2013–2014
Country slicer to filter the entire page
Product breakdown table


2. Regional Breakdown


Country-level table: Total Sales & Total Profit, with conditional (red-to-green) formatting on profit
Bar chart: Total Profit by Country (gradient-colored)
Synced with the Country slicer from page 1


3. Product Analysis


Table comparing Total Sales, Total Profit, and Profit Margin % by product
Bar chart: Profit Margin % by Product (gradient-colored)
Surfaces an insight not visible from raw sales numbers alone — the best-selling product isn't the most profitable one


🧠 Skills demonstrated


Data cleaning & type correction in Power Query Editor
Building a dedicated Date table (DAX CALENDAR()) and relating it to the fact table
Writing DAX measures: Total Sales, Total Profit, Profit Margin %, and time intelligence (SAMEPERIODLASTYEAR, YoY growth)
Interactive slicers with cross-page syncing
Conditional formatting (color scales) on both tables and charts
Multi-page report design with a consistent theme


Tools & Data


Tool: Power BI Desktop (free)
Dataset: Microsoft Financial Sample — fictional company sales data, 2013–2014
