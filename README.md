
🧠 SQL50 – Complete Solutions

This repository contains my solutions to the SQL50 problem set.
The goal of this project is not just to solve problems, but to:
- Write clean, readable, and idiomatic SQL
- Use correct joins, window functions, and aggregations
- Demonstrate production-style query structure

🧪 Solutions

1757. Recyclable and Low Fat Products
-- Solution
SELECT p.product_id
FROM Products AS p
WHERE p.low_fats = 'Y' AND p.recyclable = 'Y'
