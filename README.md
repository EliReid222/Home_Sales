# Home_Sales
Home Sales Analysis with SparkSQL

Welcome to the Home Sales Analysis project, where SparkSQL was used to gain valuable insights from home sales data. The analysis is encapsulated in the Home_sales_colab.ipynb file, meticulously crafted using Google Colab.

Key Features

SparkSQL Tasks
Temporary Views: We establish temporary views to facilitate seamless data manipulation.
Data Partitioning: Efficient data partitioning is implemented, enhancing query performance.
Caching Strategies: Explore the benefits of caching and uncaching temporary tables for optimized processing.
Analysis Highlights
We address several pertinent questions using SparkSQL:

Yearly Average Prices:
Calculate the average price for four-bedroom houses sold each year.
Yearly Average Prices for Specific Features:
Determine the average price of homes built in a specific year with three bedrooms and three bathrooms.
Calculate the average price for homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet.
View Ratings for High-Value Homes:
Identify the "view" rating for homes priced at $350,000 or more.
Caching and Uncaching
Caching Operation: The temporary table "homes" is strategically cached for optimized performance.
Caching Verification: Rigorous verification ensures the successful caching of the temporary table.
Data Partitioning
Partitioning by Date Built: The home sales data is partitioned based on the "date_built" field in formatted parquet format.
Query Execution: Execute a query filtering view ratings with an average price of $350,000 or more. Compare the runtime against the uncached scenario.
Uncaching Operation
Uncaching Process: Efficiently uncach the "home_sales" temporary table for resource optimization.
Verification with PySpark: Thorough verification processes using PySpark confirm the successful uncaching of the "home_sales" temporary table.
