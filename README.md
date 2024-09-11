# Pizza Sales Project - SQL Database Analysis

## Overview
This project utilizes SQL to extract valuable insights from pizza sales data to help improve business operations. The project focuses on answering key business questions and analyzing sales patterns based on historical data of orders, pizzas, pizza types, and their prices.

## Data Files
The analysis is based on the following CSV files:

1. **order_details.csv** - Contains detailed information about each order, including the pizza type and size.
2. **orders.csv** - Contains order-level details such as order time and date.
3. **pizza_types.csv** - Contains metadata about each pizza type (category, ingredients).
4. **pizzas.csv** - Contains pizza size and price information for each pizza type.

## Questions Answered
The following queries were addressed using SQL to provide insights for better decision-making:

### Basic Queries:
1. **Retrieve the total number of orders placed**  
   Helps gauge overall business activity and volume.
   
2. **Calculate the total revenue generated from pizza sales**  
   Provides insights into the financial performance of the pizza business.

3. **Identify the highest-priced pizza**  
   Helps in pricing strategy evaluation.

4. **Identify the most common pizza size ordered**  
   Useful for optimizing inventory and understanding customer preferences.

5. **List the top 5 most ordered pizza types along with their quantities**  
   Identifies the most popular pizzas, helping in menu optimization.

### Intermediate Queries:
1. **Find the total quantity of each pizza category ordered**  
   Useful for understanding demand by pizza category.

2. **Analyze the distribution of orders by hour of the day**  
   Provides insights into peak ordering times, useful for staffing and promotions.

3. **Find the category-wise distribution of pizzas**  
   Helps understand customer preferences across different pizza categories.

4. **Group orders by date and calculate the average number of pizzas ordered per day**  
   Analyzes daily demand trends for better forecasting.

5. **Determine the top 3 most ordered pizza types based on revenue**  
   Helps identify the best-performing products in terms of sales revenue.

### Advanced Queries:
1. **Calculate the percentage contribution of each pizza type to total revenue**  
   Helps in identifying the most profitable products.

2. **Analyze the cumulative revenue generated over time**  
   Tracks financial performance growth and provides insights for long-term business strategy.

3. **Determine the top 3 most ordered pizza types based on revenue for each pizza category**  
   Helps identify the top-performing pizzas in each category, assisting in inventory and marketing optimization.

## Key Insights
- The analysis revealed the most popular pizza types, sizes, and categories, allowing for inventory optimization.
- Peak ordering hours were identified, enabling better staffing and promotional efforts.
- Revenue distribution insights were used to determine which pizzas contribute most to overall revenue, aiding in product and pricing strategies.

## Technology Stack
- **SQL**: To perform data extraction, transformation, and analysis.
- **CSV**: Data sources are in CSV format and loaded into SQL for querying.

## How to Use
1. Import the CSV files into your preferred SQL database.
2. Use the SQL queries developed in this project to retrieve the insights.
3. Customize the queries as needed to answer additional questions or tailor the insights to specific business needs.

## Future Improvements
- Enhance the analysis by incorporating customer feedback data.
- Use predictive analytics to forecast future sales based on historical data.
- Explore additional business metrics such as customer lifetime value and retention rates.

---

This README serves as a comprehensive overview of the project, detailing its purpose, data, and the insights extracted using SQL queries.
