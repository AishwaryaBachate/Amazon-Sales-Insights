# Amazon-Sales-Insights
Amazon Sales Analysis Power BI Report
Project Overview
This project involves the analysis of Amazon sales data using Power BI. The goal is to provide actionable insights into sales performance, product trends, fulfillment efficiency, and customer behavior. The analysis is presented in a two-page Power BI report, with each page focusing on different aspects of the business.

Data Sources
File: Amazon Sale Report.csv
Description: The dataset includes detailed sales information such as order IDs, dates, statuses, fulfillment methods, sales channels, product categories, sizes, quantities sold, shipping details, and financial metrics like amount and currency.
Data Processing Steps
1. Data Collection
The data was initially collected in a CSV file format, representing Amazon sales transactions.
2. Data Cleaning & Interpretation
Irrelevant Columns Removed: Columns with no data or that were not useful for the analysis were removed (e.g., New, PendingS).
Data Type Conversion: The Date column was converted from text to a proper date format. New columns for Day, Month, and Year were created for better time-based analysis.
Handling Missing Values: Missing values in important columns like Amount and ship-city were addressed appropriately.
Standardization: Text data (e.g., order statuses, fulfillment methods) was standardized to ensure consistency.
3. Data Modelling
Calculated Columns: Columns for Year, Month, and Day were created to enable detailed time-based analysis.
Measures Created:
Total Sales
Order Count
Average Order Value
Cancellation Rate
Shipped Orders
B2B Sales
Sales by Category
Sales by Region
4. Data Analysis & Visualization
Page 1: Sales Performance Overview
Key metrics: Total Sales, Order Count, Average Order Value.
Visualizations: Line Chart for Sales Trend, Column Chart for Sales by Channel, Pie Chart for Sales by Category, Bar Chart for Sales by Size, and a Table for Top Products.
Page 2: Operational and Customer Insights
Key metrics: Shipped Orders, Cancellation Rate, B2B Sales.
Visualizations: Column Chart for Fulfillment Method Effectiveness, Pie Chart for Order Status Distribution, Bar Chart for B2B vs B2C Segmentation, Map for Geographical Sales Distribution.
