![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/c0b27846-1556-42af-b768-1569b6713a5f)
# Empovation-Challenge June SQL Report Analysis
# Introduction
_This report provides a detailed documentation of the analysis conducted for all SQL queries from Week 1 to Week 4 of the challenge. The objective is to evaluate query performance, document data cleaning processes, derive business insights, and provide recommendations for future improvements. The analysis covers the period from [3/06/2024] to [28/06/2024]._
# Summary of Queries
Total Queries Executed: 41,
Average Execution Time: 1.2 seconds,
Success Rate: 90%
# Types of Queries:
SELECT: 33,
WITH: 8
# Query Examples:
# SELECT:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/fedbc26a-23d2-43d7-81b4-e4c0cb31c6e3)
# WITH:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/74d80573-52e0-4b71-8bd4-fc781709972b)

# DETAILED ANALYSIS FOR EACH WEEK:
# **Week 1 challenges:**
_The SQL challenges involve analyzing key business metrics: counting total orders per customer to identify the most active customers, listing products sold in 2020 to understand sales trends, retrieving customer details from California for regional analysis, calculating total sales quantity for a specific product to monitor its performance, and identifying the top 5 stores with the most sales transactions to recognize top-performing locations. These tasks provide valuable insights into customer behavior, product demand, regional distribution, and store efficiency, aiding in strategic decision-making and operational improvements._
# Q1.Count the Total Orders
Write a query to count the Total Number of Orders Per Customer order in desc.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/958a38c5-2efa-4c35-929c-d584e2a18c38)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/9ff880b1-72b3-43eb-8659-74a66fa4bce3)
# Execution time: 
1 second
# Insights:
Gaspare Trevisan had the highest number of orders, followed by Paul Warren and Fabrice Lamoureux.
# Q2.List of Products
Write a SQL query to List of Products Sold in 2020
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/40d1b8fb-f00a-48ee-9341-7979ad601811)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5f476901-eec7-47d3-9742-43358f1199f7)
# Execution time: 
1 second
# Insights:
The products sold in 2020 were about 2000 and included the following:Fabrikam SLR Camera 35" X358 Gold,Proseware Laser Fax Printer M250 White,A. Datum Point n' Shoot Digital Camera M500 Grey, etc.
# Q3.Find Customers in a Specific City
Write a query to find all Customer Details from California (CA)
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/92861360-0e5c-49fb-91bf-a05df01a1582)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/868473c2-47c4-4751-96ba-4b324c0cc2ae)
# Execution time: 
1 second
# Insights:
There are about 715 customers from the State,"California",United States and it comprised of the following cities: Los Angeles,Irvine, Dublin,Walnut Creek,Graden Crove, etc.
# Q4.Calculate Total Sales Quantity
Write a query to calculate the Total Sales Quantity for product 2115
# Code: 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/b0c9565b-cbb1-453b-8e0d-ab76a2151d62)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/86a44e9a-bac7-4f9c-867a-c484f6340486)
# Execution time: 
1 second
# Insights:
Only 127 of the product(Contoso Water Heater) with product key= 2115 was sold.
# Q5.Store Information Retrieval
Write a query to retrieve the Top 5 Stores with the Most Sales Transactions.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/999df328-3bde-4bda-8f37-e2387146e193)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2ed75ffd-9ff5-4dfc-8aa4-87120509a29d)
# Correct Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/78391278-d866-4b52-b63b-d5108456369d)
# Correct Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/287cf3d2-c441-460b-9afb-e7093bc3afe7)
# Execution time: 
1 second
# Insights:
The Top 5 stores with most sales transactions are stores with storekeys: 0,55,50,54 and 9.
# **Week 2 Challenges:**
_The Week 2 SQL challenges focus on various business analytics tasks: finding the average unit price of products within each category to understand pricing trends, counting the number of orders placed by each gender to analyze customer demographics, listing all products that have never been sold to identify underperforming items, and converting order amounts to USD using exchange rates for accurate financial reporting. These tasks provide insights into product pricing, customer purchasing behavior, inventory management, and financial accuracy, supporting data-driven decision-making and operational efficiency._
# Q1.Average Price of Products in a Category
Write a query to find the average unit price of products in each category
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/eae2967a-76bf-4ba7-a14e-217b22c5bc93)
# Output 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/8abefcf7-52a8-4ef3-802b-38e72d3ce6a1)
# Execution time: 
1 second
# Insights:
Average price for the categories such as Home Appliances, TV and Video and Cameras and camcorders are 537.80,497.59 and 400.32 respectively.
# Q2.Customer Purchases by Gender
Write a query to count the number of orders placed by each gender.
# Code
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5a6020bc-611e-453a-a475-001d5e13a367)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2c769e1f-e3d7-496c-8590-2268da764134)
# Execution time: 
1 second
# Insights:
Males made more purchases than the females.
# Q3.List of Products Not Sold
Write a query to list all products that have never been sold.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2224b146-b244-4675-9f2e-837d17fcf8e5)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/cccd0085-f3eb-4172-b4b0-aaab9d563095)
# Execution time: 
1 second
# Insights:
The products not sold includes:Fabrikam SLR Camera 35" X358 Gold,A. Datum Point n' Shoot Digital Camera M500 Grey,Proseware Laser Fax Printer M250 White. etc.
# Q4.Currency Conversion for Orders
Write a query to show the total amount in USD, round to 2 decimal point for orders made in other currencies, using the Exchange Rates table to convert the prices.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/28a7eb28-cbc1-4efe-918a-83ec449e5e51)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/15ce84a3-d5e5-4878-9d4a-99eb3e3128bb)
# Correct Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/65caff24-edfb-48e2-8b50-80658cc28b8c)
# Correct Output:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2221501a-5116-4914-aa54-93e79526e757)
# Execution time: 
25 seconds
# Insights:
There are quite a lot of foreign purchases. Amazing!
# **Week 3 Challenge:**
_The Week 3 SQL challenges involve several in-depth business analyses: examining the impact of store size on sales volume to determine if larger stores generate higher sales, segmenting customers based on purchase behaviors and demographics for targeted marketing, ranking stores by their sales volume to identify top performers, calculating a running total of daily sales to monitor trends over time, and determining the lifetime value (LTV) of customers both overall and by country to assess long-term customer profitability. These tasks provide valuable insights into store performance, customer behavior, sales trends, and customer value, aiding in strategic planning and marketing efforts._
# Q1.Impact of Store Size on Sales Volume
 Write a query to analyze whether larger stores (in terms of square meters) have higher sales volumes.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/e4fae2a4-9f4f-4742-abe4-910afd99c18d)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/92bdb60e-0ec8-433c-af93-1165de4dac1f)
# Execution time: 
1 second
# Insights:
The largest store(about 2105 square meters) with storekey=8 had a total sale of 4188,next Largest Store were those with square meteres of 2100(storekey=39,30,37 and 41) had a total sale of 3284,3182,3028 and 1379 resepectively.
The store with the largest sales(41311) is the online store with storekey=0,however the largest sales for the physical store was that of storekey=9(1500 square metres) with about 4894 Total sales
# Q2.Customer Segmentation by Purchase Behavior and Demographics
 Write a query to segment customers into groups based on their purchase behaviors (e.g., total spend, number of orders) and demographics (e.g., state, gender).
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/142680bc-822a-4ae3-ba0e-ee6a38de2d15)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/5d1911f4-3194-4184-b6df-6ce175624903)
# Execution time: 
1 second
# Insights:
The Customers were segmented into Gender,Spend category and Order frequency.
For the spend_category those whose  total_expenses were higher than 1000USD we tag them 'High Spender',
those whose  total_expenses were between 500USD and 1000USD were tagged 'Medium Spender'
and those whose  total_expenses were lower than 500 USD were tagged 'Low Spender'
For the order_frequency those whose  number_of_orders were higher than 10 were tagged 'Frequent Buyer'
those whose  number_of_orders were between 5 AND 10 were tagged 'Occasional Buyer'
those whose  number_of_orders were less than 5 were tagged 'Infrequent Buyer'  
# Q3.Ranking Stores by Sales Volume
Write a query to calculate the total sales volume for each store, then rank stores based on their sales volume.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/da59d696-0b04-41b2-aa01-d53c4dc2df61)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/7adce636-e785-46f5-ba95-4c22ade3e6e2)
# Execution time: 
1 second
# Insights:
The first 3 stores with according to sales volume are stores with storekeys=(0, 99 and 55) with 41311,4894 and 4826 total sales respectively.
# Q4.Running Total of Sales Over Time
Write a query to retrieve daily sales volumes, then calculate a running total of sales over time, ordered by date.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/0cfec726-da89-4ae3-aaf0-1c9337bfea49)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/91a58769-ed08-4c53-a50f-4d5c7a891299)
# Execution time: 
1 second
# Insights:
The total daily sales were calculated for the whole time the store was in operation.
# Q5.Lifetime value (LTV) of customers by country
Write a query to calculate the lifetime value of each customer based on their country
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/1234c4c8-a347-41c2-b556-7fe5f12679ca)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/fe71bfe0-c255-4fb6-acb5-04a9516d6bc0)
# Execution time: 
1 second
# Insights:
The TOP 3 countries with the highest average LTV;5235.1263 USD,4707.9563USD and 4671.0297USD, are The United States, Germany and Italy respectively.
# Q6.Customer Lifetime Value
Write a query to calculate the lifetime value of each customer based on the total amount they’ve spent.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/54248967-1faa-484f-bfdc-43ad64ec3536)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/55b0e586-d202-4b70-b136-c359d78e150f)
# Execution time: 
1 second
# Insights:
Matthew Flemming with customerkey=1702221 has the highest LTV of about 61871.70 USD
# **Week 4 Challenge:**
_The Week 4 SQL challenges involve comprehensive business analyses aimed at enhancing strategic decision-making: calculating year-over-year growth in sales per product category to assess performance trends, determining each customer's purchase rank within a store based on order value to identify top customers, performing customer retention analysis to understand repeat purchase behavior by demographics, and optimizing the product mix for each store location to maximize sales revenue by analyzing historical sales data for top-selling products, product popularity, and profit margins. These tasks provide insights into sales growth, customer value, retention trends, and product assortment optimization, supporting targeted marketing and inventory management strategies._
# Q1.Year-over-Year Growth in Sales per Category
Write a query to calculate the total annual sales per product category for the current year and the previous year, and then use window functions to calculate the year-over-year growth percentage.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/16404ccc-1287-4d46-bff0-cd581c2e3114)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/3b73e0a3-db2f-4f58-bc35-93e8435c6b41)
# Execution time: 
1 second
# Q2.Customer’s Purchase Rank Within Store
Write a SQL query to find each customer’s purchase rank within the store they bought from, based on the total price of the order (quantity * unit price).
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/b6f895e5-4ac7-4784-9425-e9c5fcd620b2)
# Output 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/f6084d74-e82d-4c2e-a57f-3661bdb816ff)
# Execution time: 
1 second
# Q3.Customer Retention Analysis
Perform a customer retention analysis to determine the percentage of customers who made repeat purchases within three months of their initial purchase. Calculate the percentage of retained customers by gender, age group, and location.Additionally, identify any trends or patterns in customer retention based on these demographics.
# Code:
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/17029cb3-86d8-49c1-a132-dfef705535c3)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/2ec9ee27-1b20-4f3e-b5b9-282f4ff17eeb)
# Execution time: 
1 second
# Q4.Optimize the product mix for each store location to maximize sales revenue.
Analyze historical sales data to identify the top-selling products in each product category for each store.  Determine the optimal product assortment for each store based on sales performance, product popularity, and profit margins.
# Code: 
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/fc68de8d-7a0b-42e8-8713-ca4668f77401)
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/4e15010a-810e-40da-b2e8-0044167c83f6)
# Execution time: 
30 seconds

# Conclusion
**_This report highlights the performance and challenges of SQL queries executed over the past month, covering Weeks 1 to 4. By addressing the identified issues and following the recommendations, we can enhance database efficiency and query performance, leading to more reliable and faster data retrieval processes. The documented data cleaning, business insights, and recommendations provide a comprehensive understanding of the current state and future steps for improvement._**

