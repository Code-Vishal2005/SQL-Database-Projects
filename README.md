**SQL-Repository/
│-- Queries/          # Basic SQL queries
│-- Joins/            # INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN
│-- Functions/        # SQL functions (Aggregate, Scalar, String, Date)
│-- Procedures/       # Stored Procedures & Functions
│-- Triggers/         # SQL Triggers
│-- Projects/         # Real-world SQL projects
│-- README.md         # Documentation**

**🚀 Topics Covered

✅ Database Creation & Management

✅ DDL (CREATE, DROP, ALTER, TRUNCATE)

✅ DML (INSERT, UPDATE, DELETE)

✅ DQL (SELECT, WHERE, GROUP BY, ORDER BY)

✅ Joins & Subqueries

✅ Views & Indexes

✅ Stored Procedures & Functions

✅ Triggers & Transactions

✅ SQL Optimization Techniques**

**-- Find top 5 customers with highest purchase
SELECT customer_id, SUM(amount) AS total_purchase
FROM orders
GROUP BY customer_id
ORDER BY total_purchase DESC
LIMIT 5;**
