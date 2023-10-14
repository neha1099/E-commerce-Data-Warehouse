# E-commerce-Data-Warehouse
In a recent project, I worked on streamlining and analyzing eCommerce data using Python and SQLite. The project's overarching goal was to gain insights into user behavior, product performance, and customer feedback.
Here's a step-by-step breakdown:
1.	Extract Data: The first step involved extracting data from various CSV files, including users' data, product details, orders placed, and product reviews.
2.	Transform Data:
o	The data was then transformed to add more value. For instance, I merged the orders data with the products data to calculate the 'order_value' for each transaction.
3.	Load Data:
o	All transformed datasets were loaded into an SQLite database, creating a structured data warehouse of sorts for our eCommerce data.
4.	Data Analysis:
o	Top-Selling Products: Identified the top 5 products based on the number of units sold.
o	Active Users: Spotlighted users who've placed more than 5 orders, offering insights into our most engaged customers.
o	Average Review Scores: Calculated the average rating for each product, helping us understand product reception and areas of improvement.
This project essentially served as a preliminary data analysis tool for an eCommerce platform, aiding in decision-making and strategy formulation
