Revenue and Profit Analysis of Pizza's Sales
This project focuses on analyzing pizza sales data from 2015 to gain insights into profitability and revenue generation. The analysis aims to identify key factors driving sales, customer preferences, and order patterns. By evaluating pizza performance, profit margins, and peak sales periods, the goal is to recommend strategies to increase revenue and optimize operations, ensuring sustained business growth.


Introduction
Understanding customer preferences and market trends is crucial for businesses to thrive in a competitive environment. The pizza industry is no exception, with customers having a wide range of choices and preferences when it comes to pizza flavors, sizes, and categories. Analyzing sales data allows us to gain a deeper understanding of customer behavior, identify popular pizza choices, and recognize patterns in customer orders.

The main objectives of this analysis are as follows:

Examine customer preferences in terms of pizza size, category, and specific ingredients.
Analyze revenue generation and identify the highest revenue-generating categories and pizzas.
Investigate order patterns, such as peak order times, popular days, and average order quantities.
Uncover any notable trends or patterns in customer behavior and preferences.

Data Analysis Process
In this project, I have followed a systematic approach to analyze the pizza sales data and derive meaningful insights. The analysis process involved the following steps:

Data Collection: The pizza sales data used in this analysis is collected from Kaggle which is the Data Science community. The link to the dataset is given below: https://www.kaggle.com/datasets/shilongzhuang/pizza-sales

Dataset Description: This pizza sales dataset make up 12 relevant features.

pizza_id: The unique identifier for each pizza in the dataset.
order_id: The unique identifier for each pizza order.
pizza_name_id: The identifier for each specific pizza name.
quantity: The number of pizzas ordered in each transaction.
order_date: The date when the pizza order was placed.
order_time: The time at which the pizza order was placed.
unit_price: The price of a single unit of pizza.
total_price: The total price of the pizza order, calculated as the unit price multiplied by the quantity.
pizza_size: The size or dimensions of the pizza. (S,M,L,XL,XXL)
pizza_category: The category or classification of the pizza, indicating its type or style. (Classic, Veggie, Supreme, Chicken)
pizza_ingredients: The list of ingredients used in the pizza preparation.
pizza_name: The name or label assigned to each specific pizza.
Data Preprocessing: I performed data cleaning and transformation to ensure the dataset's quality and suitability for analysis. This included handling missing values, removing duplicates, and formatting data types.

Normalization: The normalization process aims to organize the dataset into multiple tables, minimize redundancy, and establish relationships between entities. Dataset is divided into three tables. pizza table, orders table, OrdersPizza table

SQL Queries: I have utilized SQL queries to extract relevant information from the dataset. This involved querying the database to obtain insights into customer preferences, revenue generation, and order patterns.

Statistical Analysis: I have applied various statistical techniques to uncover patterns and trends in the data. This included calculating summary statistics, identifying peak order times, and examining seasonal variations in sales.

