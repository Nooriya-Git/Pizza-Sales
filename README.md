# Pizza Sales Dashboard Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Files in the Repository](#files-in-the-repository)
- [Data Column Description](#data-column-description)
- [Dashboard Summary](#dashboard-summary)
- [Key Insights](#key-insights)
- [SQL Queries](#sql-queries)
- [How to use this Repository](#how-to-use-this-repository)
  
## Project Overview
 This collection includes an examination of pizza sales data, analyzed using SQL and presented in an Excel dashboard. The goal of the project is to reveal findings regarding sales patterns, customer choices and business performance. The SQL inquiries utilized to extract these findings are also accessible, in the collection.
 
 ## Objectives
- Discover the types and sizes of pizzas to get insights, into what customers prefer.
- Study the sales patterns for each day and time to figure out when people order the most.
- Assess how well each pizza option is doing, pointing out which ones are selling well and which ones aren't.
- Compute important figures like earnings average order amount and number of pizzas, per order to gauge how the business is doing overall.
  
 ## Files in the Repository
 - Pizza_sales_dashboard.xlsx: The Excel file containing the raw data, the dashboard, and pivot tables.
 - SQL_Queries.pdf: A collection of SQL queries used for analyzing the data.
 - README.md: This document.
   
## Data Column Description
The dataset used for this analysis consists of the following columns:

 - `pizza_id`: Unique identifier for each pizza.
- `order_id`: Unique identifier for each order.
- `order_pizza_name_id`: Combined identifier for each pizza within an order.
- `quantity`: Number of pizzas ordered.
- `order_date`: Date and time when the order was placed.
- `order_day`: Day of the week when the order was placed.
- `pizza_size`: Size of the pizza (e.g., Small, Medium, Large).
- `pizza_category`: Category of the pizza (e.g., Classic, Supreme, Veggie, Chicken).
- `pizza_ingredients`: Ingredients used in the pizza.
- `pizza_name`: Name of the pizza.
- `unit_price`: Price per unit of the pizza.
- `total_price`: Total price for the quantity ordered.
  
## Dashboard Summary

The dashboard provides a holistic view of the pizza sales data, offering insights into revenue, order patterns, and pizza popularity. Below is a detailed explanation of the key sections and findings:

1. **Key Metrics**
  - Total Revenue : The total revenue generated from pizza sales is $817,860.
  - Average Order Value : The average value of an order is $38.31.
  - Total Pizzas Sold : A total of 49,574 pizzas were sold during the analysis period.
  - Total Orders : There were 21,350 individual orders.
  - Average Pizzas Per Order : On average, 2.32 pizzas were included in each order.
2. **Busiest Days and Times**
 - Days : Sales are highest on Fridays and Saturdays, indicating a weekend surge in demand.
 - Times : Peak ordering times are between 12 PM - 1 PM and 4 PM - 8 PM, suggesting lunch and dinner rushes.
3. **Daily Trend for Total Orders**
 - Trends : The number of orders remains relatively steady throughout the week, peaking on Thursday with 3,538 orders and showing a slight decline on Saturday with 3,158 orders.
4. **Hourly Trend for Total Orders**
 - Hourly Breakdown : Orders start to rise around 9 AM, peaking at 7 PM with 2,399 orders, before tapering off towards the end of the night.
5. **Sales by Category & Size**
 - Category : The Classic category is the top contributor to sales and order volumes.
 - Size: Large pizzas are the most popular, making up the largest portion of sales.
6. **% of Sales by Pizza Category**
 - Chicken : 23.45%
 - Classic : 22.13%
 - Supreme : 24.26%
 - Veggie : 30.16%
 The Veggie category is the most popular, followed by Supreme and Chicken.
7. **% of Sales by Pizza Size**
 - Large : 38.05% of total sales.
 - Medium : 31.65% of total sales.
 - Regular : 29.06% of total sales.
 - X-Large : 1.17% of total sales.
 - XX-Large : 0.07% of total sales.
 Large pizzas dominate the sales, reflecting customer preference for value.
8. **Total Pizza Sold by Pizza Category**
 - Classic : 14,888 pizzas sold.
 - Supreme : 11,897 pizzas sold.
 - Veggie : 11,649 pizzas sold.
 - Chicken : 11,050 pizzas sold.
9. **Best & Worst Sellers**
- Top 5 Best Sellers:
  - The Classic Deluxe Pizza: 2,453 units sold.
  - The Barbecue Chicken Pizza: 2,432 units sold.
  - The Hawaiian Pizza: 2,422 units sold.
  - The Pepperoni Pizza: 2,418 units sold.
  - The Thai Chicken Pizza: 2,371 units sold.
- Bottom 5 Worst Sellers:
  - The Soppressata Pizza: 961 units sold.
  - The Spinach Supreme Pizza : 950 units sold.
  - The Calabrese Pizza : 937 units sold.
  - The Mediterranean Pizza : 894 units sold.
  - The Brie Carre Pizza : 490 units sold.
 10. **Time Filter**
 - The dashboard includes a time-based filter that allows users to explore sales data across different months of 2015.

## Key Insights
#### Customer Preferences

Customers show a liking, for Veggie and Classic pizzas making them popular choices among the menu options.
The preference for pizzas is evident from the sales volume indicating that customers often choose bigger sizes possibly due to the perceived value or for group gatherings.
#### Sales Trends

Weekends, Fridays and Saturdays witness an increase in orders underscoring the importance of weekend promotions in driving sales.
Peak order times around lunch and dinner can inform decisions related to staffing and inventory management.
#### Product Performance

While popular choices like Classic Deluxe and Barbecue Chicken pizzas continue to be sellers, specialty flavors such as Brie Carre are not meeting expectations. This might necessitate a reevaluation of the menu offerings or targeted marketing efforts.
#### Revenue Contribution

With an average order value of $38.31 and total revenue figures there is clear evidence of healthy customer spending habits, within the pizza business segment.
## SQL Queries
The SQL queries used to analyze the data are included in the SQL_Queries.pdf file. These queries address various analytical needs such as:

- Filtering sales by category, size, and time.
- Calculating total revenue and order values.
- Identifying best and worst-selling pizzas.
- Analyzing hourly and daily sales trends.

## How to use this Repository
- Clone the repository to your local machine.
- Open the Pizza_sales_dashboard.xlsx file to interact with the dashboard and explore the insights.
- Review the SQL queries in SQL_Queries.pdf to understand how the data was processed and analyzed.

## Visual Dashboard Overview

![Screenshot 2024-08-09 010149](https://github.com/user-attachments/assets/9d45d87d-d13b-4968-9442-8db0a9bbd0ef)

## Conclusion 
This project successfully demonstrates the power of data analysis and visualization in transforming raw sales data into valuable insights. The findings provide a clear understanding of customer preferences and sales trends, enabling more informed business decisions.

Thank you for exploring the pizza sales analysis project. We look forward to continuing to leverage data-driven approaches to drive business forward. Feel free to reach out with any questions or suggestions!

