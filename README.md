# Homework #2 — Database Design Using Semantic Models

Normalizing the source table to 1NF, 2NF, 3NF + ER diagram + tables created in MySQL.

## Files
- `p1_1nf.png` — table in 1NF
- `p2_2nf.png` — tables in 2NF
- `p3_3nf.png` — tables in 3NF
- `p4_er_diagram.png` — ER diagram (MySQL Workbench)
- `p5_schema_workbench.1.png` — expanded schema in Workbench
- `p5_schema_workbench.2.png` — expanded schema in Workbench
- `goit-rdb-hw-02.mwb` — MySQL Workbench model file

## Tables
- `customers` (customer_id, customer_name, customer_address)
- `orders` (order_id, customer_id, order_date)
- `order_items` (id, order_id, product_name, quantity)
