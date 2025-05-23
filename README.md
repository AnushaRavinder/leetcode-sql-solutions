# leetcode-sql-solutions
My solutions to LeetCode SQL problems

1757. Recyclable and Low Fat Products
# Code
```mysql []
SELECT product_id 
FROM Products 
WHERE low_fats='Y' AND recyclable='Y'
