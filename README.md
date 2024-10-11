# Pizza-Sales-Analysis
# Problem Statement
With the help of this dashboard, we like to visualize various aspects of pizza sales data to gain insights of business performance. 
We would know about the daily and monthly trend of total orders over a specific time period also shared pizza sales by customer preferences.
Also highlighting Top 5 & Bottom 5 selling pizza based on Revenue, Total Quantity & Total Orders.

# KPI's Requirement
1. Total Revenue
2. Average Order Value
3. Total Pizza Sold
4. Total Orders
5. Average Pizzas Per Order

# Chart Requirement
1. Daily Trend for Total Orders
2. Monthly Trend for Total Orders
3. Percentage of Sales by Pizza Category
4. Percentage of Sales by Pizza Size
5. Total Pizzas by Pizza Catagory
6. Top 5 Sellers by Revenue,Total Quantity & Total Orders
7. Botton 5 Sellers by Revenue,Total Quantity & Total Orders

# DAX Query Used
1. Total Revenue = SUM (pizza_sales[total_price])
2. Total Orders = DISTINCTCOUNT (pizza_sales[order_id])
3. Average Order Value = [Total Revenue] / [Total Orders]
4. Total Pizzas Sold = SUM (pizza_sales[quantity])
5. Average Pizzas Per Order = [Total Pizzas Sold] / [Total Orders]


