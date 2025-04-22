# Pizza-Sales-Visualization

Content:
=========
This Power BI dashboard provides a detailed overview of sales performance for a pizza company. It consolidates key performance indicators (KPIs), order trends, product performance, and category-based sales data to aid in decision-making and strategic planning.

Columns:
===========
pizza_id: The index.
order_id: The order number.
pizza_name_id: Pizza id by name and size.
quantity: Order quantity.
order_date: The order date.
order_time: The order time.
unit_price: Price of each unit of pizza based on type, category, and size.
total_price: Total order value.
pizza_size: Pizza size.
pizza_category: Pizza category.
pizza_ingredients: Pizza ingredients list.
pizza_name: Name of the pizza ordered.

Missing Values: 
================
There were no missing values.

Number of Entries:
==================
48620 * 12

Problem Statement:
===================
Visualization of the data for company use for business decision and strategy remodelling.


Software/Technology/Tools Used:
=================================
PowerBI


Steps Performed:
=================
1. Cleaned the data:
a) Loaded dataset into Power Query Editor.
b) Updated first row as headers.
c) Shifted the column "pizza_name" after "pizza_name_id".
d) Renamed the column "pizza_id" to "order_number".
e) Added a custom column "time_of_day" based on "order_time".

2. Visualizations


