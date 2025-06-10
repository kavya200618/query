# query
# Task 6: Sales Trend Analysis Using Aggregations

## Objective
Analyze sales trends by aggregating:
- Monthly Revenue
- Monthly Order Volume

This task helps in understanding time-based groupings and extracting insights using SQL aggregation techniques.

---

## Tools Used
- SQL (PostgreSQL / MySQL / SQLite)
- Pandas, Matplotlib, Seaborn (for optional EDA)
- Google Colab / Jupyter Notebook
- GitHub for version control and submission

---

## Dataset Overview
The dataset used is named `online_sales`, with the following key columns:
- `order_date` – Date the order was placed
- `amount` – Revenue per order
- `product_id` – Product identifier
- `order_id` – Unique ID of each order

---

## SQL Operations Used
- `EXTRACT(MONTH FROM order_date)` – Extract month from date
- `GROUP BY` and `ORDER BY` – Grouping and sorting data
- `SUM(amount)` – Calculate monthly revenue
- `COUNT(DISTINCT order_id)` – Calculate monthly order volume
- `LIMIT` – Retrieve top N records

---

## Insights and Outcomes
- Identified months with highest sales revenue
- Observed patterns in order volume over time
- Compared revenue and volume to understand business trends

---

## Files Included
- `SQL_Query.sql`: SQL script with aggregation queries
- `TASK 6 DA.pdf`: EDA and SQL output report
- `README.md`: Documentation and task explanation

---

## Sample Interview Questions Covered
1. How do you group data by month and year?
2. What is the difference between `COUNT(*)` and `COUNT(DISTINCT column)`?
3. How do you calculate monthly revenue?
4. What are aggregate functions in SQL?
5. How do you handle NULL values in aggregation?
6. What is the role of `GROUP BY` and `ORDER BY` in SQL?
7. How do you fetch the top 3 months by sales?

---

## Submission
- Repository created and all files uploaded
- GitHub Link submitted as per internship guidelines
- Submission Time: Within the 10:00 AM to 10:00 PM window

---

## Author
**Kavya Chalichemala**   
Vel Tech Rangarajan Dr. Sagunthala R&D Institute of Science & Technology  
Email: chalichemalakavya@gmail.com  
Location: Chennai, India
