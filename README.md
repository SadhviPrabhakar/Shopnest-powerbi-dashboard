ShopNest Store Sales & Delivery Analysis (Power BI)

An interactive Power BI dashboard that analyses sales, ratings, payments and delivery performance for an online store (2016 to 2018).

Dashboard

*Business questions answered:
1.Which product categories and states drive the most sales?
2.Which categories have the highest and lowest customer ratings?
3.How do delayed orders compare with on-time orders each month?
4.Which payment methods do customers use?
5.How do sales change by quarter and by year?
*Key insights
Total sales are 13.59M with an average rating of 4.07.
The top three categories (health_beauty 1.3M, watches_gifts 1.2M, bed_bath_table 1.0M) bring in about a quarter of all sales.
Sao Paulo (SP) is the biggest state by a wide margin (about 5M), so sales depend heavily on one region.
On-time orders are far higher than delayed orders every month; the most delayed categories are bed_bath_table and health_beauty.
Credit card is 73.9% of payments and boleto 19%.
Yearly revenue rises from 2016 to 2018. The Q4 dip should be read with care because the dataset may not cover every month.
What I did
Loaded and cleaned the tables in Power Query (converted text dates to real dates using locale).
Built the data model and fixed relationships between customers, orders, order items and products.
Wrote DAX measures such as Total Sales = SUM(order_items_dataset[price]) and a rating measure filtered to products with 100+ reviews.
Built 12 visuals with slicers for category, delivery status, quarter and year.
Tools

Power BI, DAX, Power Query

Files
shopnest_dashboard.png: dashboard screenshot
Shopnest_PowerBI_Report_Updated.docx: written report with all 8 questions and charts
Author

Sadhvi P
