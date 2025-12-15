
# SQL50 — Clean Solutions Repository

> A structured, readable, and interview-ready collection of **all 50 SQL50 solutions**.

---

## Purpose

This README is designed to:
- Look **clean and professional** on GitHub
- Make each solution **easy to scan and review**
- Serve as a **SQL reference + interview prep repo**
This repository contains my solutions to the SQL50 problem set.
The goal of this project is not just to solve problems, but to:
- Write clean, readable, and idiomatic SQL
- Use correct joins, window functions, and aggregations
- Demonstrate production-style query structure

## Solutions

## 1757. Recyclable and Low Fat Products

```sql
SELECT p.product_id
FROM Products AS p
WHERE p.low_fats = 'Y' AND p.recyclable = 'Y';
