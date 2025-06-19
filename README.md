# 📘 Beginner-Friendly SQL Practice Guide

Welcome! 👋  
This repository contains easy-to-follow SQL notes and sample queries perfect for **absolute beginners** who want to learn and practice SQL on their own computer step by step.

---

## 🛠 What You Need

To run the SQL queries in this guide, you need a basic SQL environment. Here are two beginner-friendly options:

### ✅ Option 1: **Install MySQL on your computer**
- Download: [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/)
- Use a GUI tool like **MySQL Workbench** or **DBeaver** for easier query writing.

### ✅ Option 2: **Use an Online SQL Editor**
- Try: [https://sqliteonline.com/](https://sqliteonline.com/)
- OR: [https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all)

---

## 📂 Sample Tables You Need to Create

Before running the queries, create and insert sample data into three tables:

### 1. `movies` table:

```sql
CREATE TABLE movies (
    movie_id INT,
    title VARCHAR(100),
    industry VARCHAR(50),
    studio VARCHAR(100),
    imdb_rating FLOAT
);

INSERT INTO movies VALUES
(1, 'Avengers: Endgame', 'Hollywood', 'Marvel Studios', 8.4),
(2, '3 Idiots', 'Bollywood', 'Vinod Chopra Films', 8.4),
(3, 'Thor: Ragnarok', 'Hollywood', 'Marvel Studios', 7.9),
(4, 'Dangal', 'Bollywood', '', 8.3);
