# Dominos-sql-Project
# Domino's SQL Project (MS SQL Server)

This project involves performing SQL queries on a Domino's pizza dataset using Microsoft SQL Server. The analysis is structured in a progressive manner starting from basic SQL to intermediate and advanced-level queries.

---

## Tables Used

1.   **orders**
   - order_id (INT)
   - date (DATE)
   - time (TIME)
   - customer_id (INT)

2. **order_details**
   - order_id (INT)
   - pizza_id (VARCHAR)
   - quantity (INT)

3. **pizzas**
   - pizza_id (VARCHAR)
   - pizza_type_id (VARCHAR)
   - size (VARCHAR)
   - price (FLOAT)

4. **pizza_types**
   - pizza_type_id (VARCHAR)
   - name (VARCHAR)
   - category (VARCHAR)
   - ingredients (TEXT)

---

## 🛠 Environment Setup

- **Database Tool:** Microsoft SQL Server Management Studio (SSMS)
- **Import Method:** SQL Server Import Wizard


---

## 🔍 SQL Query List

**Basic SQL**
1.  Total number of orders  
2.  Total number of pizzas sold  
3.  Total revenue generated  
4.  Average order value  
5.  Unique Pizza Variety Sold  

**Intermediate SQL**
1.  Top 5 most popular pizza size  
2.  Most expensive pizza
3.  Total revenue by pizza category
4.  Average quantity per order
5. Orders placed per date

**Advanced SQL**
1. Total revenue by pizza category
2. Top-performing pizza category by revenue
3. Peak order day of the week
4. Most ordered pizza per category
