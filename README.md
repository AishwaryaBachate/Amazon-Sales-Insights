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

3. Data Modelling

Calculated Columns: Columns for Year, Month, and Day were created to enable detailed time-based analysis.
Measures Created:
Total Sales
Order Count
Average Order Value
Cancellation Rate
Shipped Orders
B2B Sales

4. Data Analysis & Visualization

Sales Performance Overview

Key metrics: Total Sales, Order Count, Average Order Value.

Visualizations: Line Chart for Sales Trend, Column Chart for Sales by Channel, Pie Chart for Sales by Category, Bar Chart for Sales by Size, and a Table for Top Products.


Operational and Customer Insights

Key metrics: Shipped Orders, Cancellation Rate, B2B Sales.

Visualizations: Column Chart for Fulfillment Method Effectiveness, Pie Chart for Order Status Distribution, Bar Chart for B2B vs B2C Segmentation, Map for Geographical Sales Distribution.


Key Insights and Recommendations

 Optimize Fulfillment Strategies:

Amazon Fulfillment vs. Merchant Fulfillment: Since products fulfilled by Amazon have
significantly higher sales (54M vs. 24M), consider encouraging more merchants to use
Amazon’s fulfillment services. This could involve offering incentives or highlighting the
benefits of using Amazon’s fulfillment network.

 Enhance Product Offerings:

Sales by Size: Larger sizes (‘M’ and ‘L’) are the most popular and contribute the most to total
sales. Ensure that these sizes are well-stocked and consider expanding the range of
products available in these sizes to meet customer demand.

 Improve Regional Sales Strategies:

Sales by State: Maharashtra leads in sales, followed by Karnataka. Focus marketing efforts
and resources on these high-performing states to further boost sales. Additionally, investigate
why other states have lower sales and develop targeted strategies to improve performance
in these regions

 Boost City-Specific Sales:

Sales by City: Bengaluru has the highest sales, followed by Hyderabad and Mumbai.
Strengthen marketing campaigns and promotional activities in these top-performing
cities. For cities with lower, analyze local market conditions and customer preferences to
tailor strategies that can drive growth.

 Address Shipment and Delivery Issues:

Shipment Status: With a significant portion of shipments shipped (60.5%) focus on
improving the delivery process and reducing returns. This could involve better packaging,
clearer product descriptions, and enhanced customer service to address issues before
they result in returns.

 Increase Average Order Value:

Average Order Value: Orders fulfilled by merchants have a slightly higher average order
value compared to those fulfilled by Amazon. Explore ways to increase the average
order value for Amazon-fulfilled orders, such as bundling products, offering discounts on
larger purchases, or promoting premium products

Conclusion

This Power BI report provides a comprehensive analysis of Amazon sales data, offering valuable insights into sales trends, product performance, fulfillment efficiency, and customer behavior. By following a structured data analysis process, the report delivers actionable recommendations to enhance business performance.
