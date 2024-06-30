![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/c0b27846-1556-42af-b768-1569b6713a5f)
# Empovation-Challenge June SQL Report Analysis
# Introduction
_This report provides a detailed documentation of the analysis conducted for all SQL queries from Week 1 to Week 4 of the challenge. The objective is to evaluate query performance, document data cleaning processes, derive business insights, and provide recommendations for future improvements. The analysis covers the period from [3/06/2024] to [28/06/2024]._
# Summary of Queries
Total Queries Executed: 33,
Average Execution Time: 1.2 seconds,
Success Rate: 90%
# Types of Queries:
SELECT: 33
# **Week 1 challenges:**
_The SQL challenges involve analyzing key business metrics: counting total orders per customer to identify the most active customers, listing products sold in 2020 to understand sales trends, retrieving customer details from California for regional analysis, calculating total sales quantity for a specific product to monitor its performance, and identifying the top 5 stores with the most sales transactions to recognize top-performing locations. These tasks provide valuable insights into customer behavior, product demand, regional distribution, and store efficiency, aiding in strategic decision-making and operational improvements._
# Q1.Count the Total Orders
Write a query to count the Total Number of Orders Per Customer order in desc.

# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/958a38c5-2efa-4c35-929c-d584e2a18c38)

# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/9ff880b1-72b3-43eb-8659-74a66fa4bce3)

# Q2.List of Products
Write a SQL query to List of Products Sold in 2020
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/40d1b8fb-f00a-48ee-9341-7979ad601811)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5f476901-eec7-47d3-9742-43358f1199f7)

# Q3.Find Customers in a Specific City
Write a query to find all Customer Details from California (CA)
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/92861360-0e5c-49fb-91bf-a05df01a1582)

# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/868473c2-47c4-4751-96ba-4b324c0cc2ae)

# Q4.Calculate Total Sales Quantity
Write a query to calculate the Total Sales Quantity for product 2115
# Code: 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/b0c9565b-cbb1-453b-8e0d-ab76a2151d62)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/86a44e9a-bac7-4f9c-867a-c484f6340486)

# Q5.Store Information Retrieval
Write a query to retrieve the Top 5 Stores with the Most Sales Transactions.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/999df328-3bde-4bda-8f37-e2387146e193)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2ed75ffd-9ff5-4dfc-8aa4-87120509a29d)

# **Week 2 Challenges:**
_The Week 2 SQL challenges focus on various business analytics tasks: finding the average unit price of products within each category to understand pricing trends, counting the number of orders placed by each gender to analyze customer demographics, listing all products that have never been sold to identify underperforming items, and converting order amounts to USD using exchange rates for accurate financial reporting. These tasks provide insights into product pricing, customer purchasing behavior, inventory management, and financial accuracy, supporting data-driven decision-making and operational efficiency._
# Q1.Average Price of Products in a Category
Write a query to find the average unit price of products in each category
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/eae2967a-76bf-4ba7-a14e-217b22c5bc93)
# Output 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/8abefcf7-52a8-4ef3-802b-38e72d3ce6a1)

# Q2.Customer Purchases by Gender
Write a query to count the number of orders placed by each gender.
# Code
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5a6020bc-611e-453a-a475-001d5e13a367)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2c769e1f-e3d7-496c-8590-2268da764134)

# Q3.List of Products Not Sold
Write a query to list all products that have never been sold.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2224b146-b244-4675-9f2e-837d17fcf8e5)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/cccd0085-f3eb-4172-b4b0-aaab9d563095)

# Q4.Currency Conversion for Orders
Write a query to show the total amount in USD, round to 2 decimal point for orders made in other currencies, using the Exchange Rates table to convert the prices.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/28a7eb28-cbc1-4efe-918a-83ec449e5e51)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/15ce84a3-d5e5-4878-9d4a-99eb3e3128bb)

# **Week 3 Challenge:**
_The Week 3 SQL challenges involve several in-depth business analyses: examining the impact of store size on sales volume to determine if larger stores generate higher sales, segmenting customers based on purchase behaviors and demographics for targeted marketing, ranking stores by their sales volume to identify top performers, calculating a running total of daily sales to monitor trends over time, and determining the lifetime value (LTV) of customers both overall and by country to assess long-term customer profitability. These tasks provide valuable insights into store performance, customer behavior, sales trends, and customer value, aiding in strategic planning and marketing efforts._
# Q1.Impact of Store Size on Sales Volume
 Write a query to analyze whether larger stores (in terms of square meters) have higher sales volumes.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/e4fae2a4-9f4f-4742-abe4-910afd99c18d)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/92bdb60e-0ec8-433c-af93-1165de4dac1f)

# Q2.Customer Segmentation by Purchase Behavior and Demographics
 Write a query to segment customers into groups based on their purchase behaviors (e.g., total spend, number of orders) and demographics (e.g., state, gender).
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/142680bc-822a-4ae3-ba0e-ee6a38de2d15)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5d1911f4-3194-4184-b6df-6ce175624903)
Q3.Ranking Stores by Sales Volume
Write a query to calculate the total sales volume for each store, then rank stores based on their sales volume.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/da59d696-0b04-41b2-aa01-d53c4dc2df61)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/7adce636-e785-46f5-ba95-4c22ade3e6e2)
Q4.Running Total of Sales Over Time
Write a query to retrieve daily sales volumes, then calculate a running total of sales over time, ordered by date.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/0cfec726-da89-4ae3-aaf0-1c9337bfea49)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/91a58769-ed08-4c53-a50f-4d5c7a891299)
# Q5.Lifetime value (LTV) of customers by country
Write a query to calculate the lifetime value of each customer based on their country
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/1234c4c8-a347-41c2-b556-7fe5f12679ca)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/fe71bfe0-c255-4fb6-acb5-04a9516d6bc0)
# Q6.Customer Lifetime Value
Write a query to calculate the lifetime value of each customer based on the total amount they’ve spent.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/54248967-1faa-484f-bfdc-43ad64ec3536)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/55b0e586-d202-4b70-b136-c359d78e150f)

# **Week 4 Challenge:**
_The Week 4 SQL challenges involve comprehensive business analyses aimed at enhancing strategic decision-making: calculating year-over-year growth in sales per product category to assess performance trends, determining each customer's purchase rank within a store based on order value to identify top customers, performing customer retention analysis to understand repeat purchase behavior by demographics, and optimizing the product mix for each store location to maximize sales revenue by analyzing historical sales data for top-selling products, product popularity, and profit margins. These tasks provide insights into sales growth, customer value, retention trends, and product assortment optimization, supporting targeted marketing and inventory management strategies._
# Q1.Year-over-Year Growth in Sales per Category
Write a query to calculate the total annual sales per product category for the current year and the previous year, and then use window functions to calculate the year-over-year growth percentage.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/16404ccc-1287-4d46-bff0-cd581c2e3114)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/3b73e0a3-db2f-4f58-bc35-93e8435c6b41)
# Q2.Customer’s Purchase Rank Within Store
Write a SQL query to find each customer’s purchase rank within the store they bought from, based on the total price of the order (quantity * unit price).
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/b6f895e5-4ac7-4784-9425-e9c5fcd620b2)
# Output 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/f6084d74-e82d-4c2e-a57f-3661bdb816ff)
# Q3.Customer Retention Analysis
Perform a customer retention analysis to determine the percentage of customers who made repeat purchases within three months of their initial purchase. Calculate the percentage of retained customers by gender, age group, and location.Additionally, identify any trends or patterns in customer retention based on these demographics.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/17029cb3-86d8-49c1-a132-dfef705535c3)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2ec9ee27-1b20-4f3e-b5b9-282f4ff17eeb)
# Q4.Optimize the product mix for each store location to maximize sales revenue.
Analyze historical sales data to identify the top-selling products in each product category for each store.  Determine the optimal product assortment for each store based on sales performance, product popularity, and profit margins.
# Code: 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/fc68de8d-7a0b-42e8-8713-ca4668f77401)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/4e15010a-810e-40da-b2e8-0044167c83f6)

