# 🌿 Build With Clarity  
*A space to trace growth—layer by layer, week by week.*

---

## Week 3 Reflection

This week was all about PostgreSQL. I shifted from infrastructure to data designing schemas, inserting realistic records, and solving queries that mirrored real-world business logic.

---

### 🧱 Schema Setup

I created a mini sales database with four tables:

- `customers`: customer_id, name, region, signup_date  
- `products`: product_id, name, category, unit_price  
- `orders`: order_id, customer_id, order_date, status, payment_method  
- `order_items`: order_id, product_id, quantity, unit_price  

Inserted:
- 20 rows into `customers` and `products`  
- 80 rows into `orders`  
-   230 rows into `order_items`

---

### 🔍 Query Practice

Solved **50 queries** :

- Filtering, sorting, and aggregations  
- Joins across multiple tables  
- Window functions for ranking and cumulative metrics  
- Business logic: revenue, churn, RFM, basket analysis  
- Rollups and percent contributions
  
---

### 💡 Reflections

Window functions felt tricky at first. I paused, broke them down, and realized:

> “Problems feel big until you understand the concept behind them.”

This week taught me how to think in terms of relationships, not just rows. Querying became less about syntax and more about logic.


> “Data isn’t just stored — it’s understood.”
