# Day-26 SQL-Basics-SELECT-WHERE

Overview

I practiced the foundational SQL commands used to retrieve and filter data from databases. These concepts are essential for data analysis, backend development, and data science workflows.

Topics Covered

1. SELECT Statement

Used to retrieve specific columns or all data from a table.

```sql
SELECT * FROM employees;
SELECT name, salary FROM employees;
```

2. WHERE Clause

Used to filter records based on conditions.

```sql
SELECT * FROM employees WHERE salary > 50000;
```

3. SQL Operators

Common operators practiced:

 `=` Equal to
 `>` Greater than
 `<` Less than
 `AND`, `OR`, `NOT`

```sql
SELECT * FROM employees WHERE department = 'IT' AND salary > 60000;
```

4. ORDER BY Clause

Sorts query results.

```sql
SELECT * FROM employees ORDER BY salary DESC;
```

5. LIMIT Clause

Restricts the number of rows returned.

```sql
SELECT * FROM employees ORDER BY salary DESC LIMIT 5;
```

Learning Outcome

Improved understanding of querying databases
Learned how to filter, sort, and limit data efficiently
Strengthened SQL fundamentals for data analysis


