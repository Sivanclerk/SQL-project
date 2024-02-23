This project entails the development and utilization of a relational database system designed to manage and analyze e-commerce transaction data for a hypothetical online shopping platform named `SHOPPING_AS`. The core of this system is structured around two primary tables: `orderinfo` and `userinfo`, which store order-related details and user demographics, respectively.

### Database Schema

- **`orderinfo` Table**: Captures each transaction's essential details, including the order ID (`order_id`), the user ID of the customer (`user_id`), payment status (`ispaid`), the transaction amount (`price`), and the time of payment (`paidtime`). This table is pivotal for tracking sales transactions and analyzing payment behaviors.

- **`userinfo` Table**: Stores information about the users, including a unique user ID (`user_id`), the user's gender (`sex`), and their date of birth (`birth`). This demographic information is crucial for understanding the customer base and tailoring marketing strategies accordingly.

### SQL Queries

The project encompasses a series of SQL queries designed to extract insightful analytics from the stored data, including:

1. **Monthly Order Counts**: Aggregates the number of unique users placing orders each month, providing insight into the platform's monthly engagement and growth.

2. **Repurchase and Repeat Purchase Rates**: Calculates critical metrics for customer loyalty, including the repurchase rate (indicating customers who make another purchase in the following month) and the repeat purchase rate (highlighting customers who make multiple purchases within the same month).

3. **Gender-based Consumption Frequency**: Analyzes the difference in consumption patterns between male and female users, offering insights into gender preferences and spending habits.

4. **First and Last Purchase Interval**: For users with multiple purchases, this analysis determines the time interval between their first and last transactions, which can help in understanding customer retention and lifecycle.

5. **Age Group Consumption Analysis**: Segments users into different age groups and compares their total spending, enabling targeted marketing strategies based on age-related preferences.

6. **Pareto Principle in Consumption (80/20 Rule)**: Investigates the principle that a small percentage of customers (top 20%) contribute to a significant portion of sales, helping to identify and focus on high-value customers.

### Objective

The objective of this project is to leverage structured query language (SQL) for data manipulation and analysis, enabling the business to make informed decisions based on comprehensive insights into customer behavior, sales trends, and demographic segmentation. This analytical approach aims to enhance customer satisfaction, optimize marketing efforts, and ultimately drive revenue growth for the online shopping platform.
