    Recommended editors: Visual studio code
    All your files will be executed on Ubuntu 20.04 LTS using MySQL 5.7 (version 5.7.8-rc)
    All your files should end with a new line
    All your SQL queries should have a comment just before (i.e. syntax above)
    All your files should start by a comment describing the task
    All SQL keywords should be in uppercase (SELECT, WHERE…)
    A README.md file, at the root of the folder of the project, is mandatory
    The length of your files will be tested using wc

# Tasks

0. List databases

Write a script that lists all databases of your MySQL server.

1. Create a database

Write a script that creates the database hbtn_0c_0 in your MySQL server.

If the database hbtn_0c_0 already exists, your script should not fail
You are not allowed to use the SELECT or SHOW statements

2. Delete a database

Write a script that deletes the database hbtn_0c_0 in your MySQL server.

If the database hbtn_0c_0 doesn’t exist, your script should not fail
You are not allowed to use the SELECT or SHOW statements

3. List tables

Write a script that lists all the tables of a database in your MySQL server.

The database name will be passed as argument of mysql command (in the following example: mysql is the name of the database)

4. First table

Write a script that creates a table called first_table in the current database in your MySQL server.

first_table description:
id INT
name VARCHAR(256)
The database name will be passed as an argument of the mysql command
If the table first_table already exists, your script should not fail
You are not allowed to use the SELECT or SHOW statements

5. Full description

Write a script that prints the full description of the table first_table from the database hbtn_0c_0 in your MySQL server.

The database name will be passed as an argument of the mysql command
You are not allowed to use the DESCRIBE or EXPLAIN statements

6. List all in table

Write a script that lists all rows of the table first_table from the database hbtn_0c_0 in your MySQL server.

All fields should be printed
The database name will be passed as an argument of the mysql command

7. First add

Write a script that inserts a new row in the table first_table (database hbtn_0c_0) in your MySQL server.

New row:
id = 89
name = Holberton School
The database name will be passed as an argument of the mysql command

8. Count 89

Write a script that displays the number of records with id = 89 in the table first_table of the database hbtn_0c_0 in your MySQL server.

The database name will be passed as an argument of the mysql command

9. Full creation

Write a script that creates a table second_table in the database hbtn_0c_0 in your MySQL server and add multiples rows.

second_table description:
id INT
name VARCHAR(256)
score INT
The database name will be passed as an argument to the mysql command
If the table second_table already exists, your script should not fail
You are not allowed to use the SELECT and SHOW statements
Your script should create these records:
id = 1, name = “John”, score = 10
id = 2, name = “Alex”, score = 3
id = 3, name = “Bob”, score = 14
id = 4, name = “George”, score = 8

# Evaluation Quiz

0. How do you INSERT, UPDATE, or DELETE data in MySQL?

Using the INSERT INTO, UPDATE, or DELETE statement, respectively

1. How do you CREATE or ALTER a table in MySQL?

Using the ALTER TABLE statement

2. What is a PRIMARY KEY?

A key that uniquely identifies a record in a table

3. What is a FOREIGN KEY?

A key that references another table's primary key

4. How do you SELECT data from a table in MySQL?

Using the SELECT statement

5. What are subqueries?

Queries that are nested within another query

6. How do you create a database in MySQL?

Using the CREATE DATABASE statement

7. What are subqueries?

Queries that are nested within another query

8. What are JOIN and UNION?

JOIN is used to combine rows from different tables based on related columns, while UNION is used to combine the result of two or more SELECT statements

9. How do you create a new MySQL user?

CREATE USER statement

10. How do you manage privileges for a user to a database or table?

GRANT statement

11. What is MySQL?

A database management system that uses SQL

12. What is a database?

A collection of related data organized and structured for efficient access

13. What do DDL and DML stand for?

Data Definition Language and Data Manipulation Language

14. What is a relational database?

A database that stores data in a tabular format and establishes relationships between tables

15. How do you use NOT NULL and UNIQUE constraints?

By specifying them in the CREATE TABLE statement

16. How do you retrieve data from multiple tables in one request?

Using the SELECT statement with JOIN

17. What does SQL stand for?

Structured Query Language
