# analyzing-motorcycle-part-sales
Analyzing Motorcycle Part Sales 🚀
Project Overview
This project analyzes wholesale net revenue for each product line on a monthly basis and per warehouse.

Business Context
You're working for a company that sells motorcycle parts through three warehouses (North, Central, and West). They offer both retail and wholesale sales, with different payment methods (Credit Card, Cash, and Bank Transfer), each incurring a different transaction fee.

The Board of Directors wants a clearer understanding of wholesale revenue trends:

How much revenue each product line generates per month
How revenue varies across different warehouses
Your Task
✅ Calculate net revenue for each product line
✅ Group results by month and by warehouse
✅ Filter only wholesale orders

Dataset Details
The dataset contains a Sales table with the following columns:

Column Name	Data Type	Description
order_number	VARCHAR	Unique order identifier.
date	DATE	Order date (June - August 2021).
warehouse	VARCHAR	Warehouse location (North, Central, West).
client_type	VARCHAR	Order type (Retail or Wholesale).
product_line	VARCHAR	Type of product ordered.
quantity	INT	Number of products ordered.
unit_price	FLOAT	Price per product (in dollars).
total	FLOAT	Total price of the order (in dollars).
payment	VARCHAR	Payment method (Credit Card, Transfer, Cash).
payment_fee	FLOAT	Percentage of total charged as a payment fee.
How to Use This Analysis
💡 For Business Insights:

Identify top-selling product lines in wholesale.
Compare revenue trends across warehouses.
Evaluate the impact of payment fees on net revenue.
💻 For Technical Analysis:

Use SQL queries to extract and filter data.
Visualize trends in Power BI / Tableau.

