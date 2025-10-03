# SQL-Interview-Questions
Repository with dataset to practice SQL iterview questions

# 📊 SQL Interview Practice Dataset  

This repository contains a **toy dataset** designed to practice common SQL interview questions.  
The dataset is lightweight but realistic, reflecting a simple **e-commerce scenario** with customers, orders, and order details.  

It is used in the Medium article:  
👉 [**“11 SQL Interview Questions You’ll Definitely Be Asked (With Simple Examples)”**](#)  
 

---

## Dataset Files  

| File | Description |
|------|------------|
| `customers.csv`     | One row per customer. Columns: `customer_id`, `first_name`, `last_name`, `email`. |
| `orders.csv`        | One row per order. Columns: `order_id`, `order_date`, `customer_id`. |
| `order_details.csv` | One row per product within an order. Columns: `order_id`, `product_id`, `quantity`, `price`. |


- **One customer** can have **many orders**  
- **One order** can have **many order details** (products purchased)  

---

## 🔍 Example Use Cases  

This dataset is useful for practicing:  

- Primary Key vs Foreign Key  
- `WHERE` vs `HAVING`  
- `INNER JOIN` vs `LEFT JOIN`  
- Removing duplicates with `ROW_NUMBER()`  
- Using `COALESCE`, `CASE`, aggregate functions  
- `UNION` vs `UNION ALL`  
- `PARTITION BY` vs `GROUP BY`  

---

## How to Use

1. **Download or clone** this repository.  
2. Import the CSVs into your database of choice (PostgreSQL, MySQL, SQLite, etc.).  
3. Run the practice queries from the article.

## License

This dataset is released under the **MIT License**.
Free to use for learning, interview prep, and teaching purposes.
