
## New🚀 Unlocking Insights with Power BI 🚀
I’ve just built an interactive Power BI dashboard that provides deep insights into sales, delivery performance, and customer behaviours. With multiple visuals, it’s designed to help decision-makers understand key metrics at a glance.

🔹 Key Metrics & Cards:

•	Sum of Sales: Total sales revenue.
•	Average Delivery Time: How quickly products are being delivered on average.
•	Quantity Sold: Total quantity sold over a specified period.
•	Returns: Understanding return trends and volumes.

🔹 Visualizations:
•	Clustered Bar Chart: Breakdown of Profits by Product & Sales by Customer.
•	Pie Chart: Sales by Segment to understand where the majority of our sales are coming from.
•	Donut Chart: Sales by Market to identify the most profitable markets.
•	Global Map: Sales by Country to view international sales performance.

🔹 Key DAX Formula Used: For Delivery Time calculation:
DAX
Delivery Time = DATEDIFF(Orders[Order Date], Orders[Ship Date], DAY)  
This provides the number of days between the order date and the ship date, allowing us to monitor delivery efficiency.

🔹 Model View: To ensure accurate data, I’ve connected the Order ID from both the Orders and Returns tables. This connection ensures that the Returns card updates in real time with the return data.

![Screenshot (32)](https://github.com/user-attachments/assets/b0f023a9-35fe-4fa0-8ee6-48fe6b8ca970)
