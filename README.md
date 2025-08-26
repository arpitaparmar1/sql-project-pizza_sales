🍕 Pizza Sales Analysis
This project provides a comprehensive analysis of pizza sales data using SQL. The goal is to extract actionable insights that can help a pizza business improve its performance, from understanding popular products to optimizing operations
<br>


📜 Project Description
This project utilizes SQL to query and analyze a relational database of pizza sales. The analysis focuses on key business metrics and trends, including:

Total Revenue and Sales Volume: Calculating total revenue, orders, and the average order value.

Product Performance: Identifying the best-selling and least-selling pizzas and categories.

Temporal Trends: Analyzing sales patterns by hour of the day, day of the week, and month to understand peak times.

Operational Efficiency: Measuring the average order preparation and delivery time.
<br>


⚙️ Database Schema
The project is built on a simple relational database with four tables:

orders: Stores order details such as order_id, date, and time.

order_details: Connects orders to pizzas, storing order_details_id, order_id, pizza_id, and quantity.

pizzas: Contains information about each specific pizza, including pizza_id, pizza_type_id, size, and price.

pizza_types: Describes the different types of pizzas, with pizza_type_id, name, category, and ingredients.


📈 Key Insights
This project helps answer critical business questions, such as:

What is the total revenue and how does it compare to the number of orders?

Which pizzas and categories should we promote more, and which ones should we consider discounting?

Are there specific hours, days, or months where we see a significant increase in sales?

How can we improve our order fulfillment process to reduce average delivery time?

🛠️ How to Use

To use this project, you will need a SQL database (e.g., MySQL, PostgreSQL, or SQLite).

Clone the repository:

Bash
https://github.com/arpitaparmar1/sql-project-pizza_sales

git clone [repository-url]

Import data:
Use the provided CSV files to populate the tables in your database.
Run queries:
Execute the SQL queries from the queries.sql file to perform the analysis.
