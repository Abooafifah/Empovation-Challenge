# Empovation-Challenge
A report analysis on empovation 4-weeks weekly SQL challenge.
# Week 1 challenges:
# Q1.Count the Total Orders
Write a query to count the Total Number of Orders Per Customer order in desc.

# Code:
SELECT Name , COUNT(*) AS Total_orders
FROM Customers C
INNER JOIN Sales S
ON C.CustomerKey=S.CustomerKey
GROUP BY Name
ORDER BY COUNT(*) DESC.
# Output
![image](https://github.com/Abooafifah/Empovation-Challenge/assets/120792738/9ff880b1-72b3-43eb-8659-74a66fa4bce3)

# Q2.List of Products
Write a SQL query to List of Products Sold in 2020
# Code:
SELECT DISTINCT Product_Name 
FROM Products P
INNER JOIN Sales S
ON P.ProductKey=S.ProductKey
WHERE Order_Date BETWEEN '2020-01-01' AND '2020-12-31'

# Q3.Find Customers in a Specific City
Write a query to find all Customer Details from California (CA)

Q4.Calculate Total Sales Quantity
Write a query to calculate the Total Sales Quantity for product 2115
Q5.Store Information Retrieval
Write a query to retrieve the Top 5 Stores with the Most Sales Transactions.
