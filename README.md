<h1 align="center"> Relational Databases and SQL </h1>

# Content

1. [Chapter 1: Introduction to Databases and SQL](#chapter1)
    - [Chapter 1 - Part 1: What is a Database and Why Use One?](#chapter1part1)
      - [Chapter 1 - Part 1.1: What is a Database?](#chapter1part1.1)
      - [Chapter 1 - Part 1.2: Why Use a Database?](#chapter1part1.2)
      - [Chapter 1 - Part 1.3: Real-World Applications](#chapter1part1.3)
    - [Chapter 1 - Part 2: Understanding Relational Databases and Tables](#chapter1part2)
      - [Chapter 1 - Part 2.1: Core Principles of Relational Databases](#chapter1part2.1)
      - [Chapter 1 - Part 2.2: Normalization](#chapter1part2.2)
      - [Chapter 1 - Part 2.3: Data Integrity](#chapter1part2.3)
      - [Chapter 1 - Part 2.4: The "Online Bookstore" Database](#chapter1part2.4)
    - [Chapter 1 - Part 3: Introduction to SQL: The Language of Databases](#chapter1part3)
      - [Chapter 1 - Part 3.1: Core Principles of Relational Databases](#chapter1part3.1)
      - [Chapter 1 - Part 3.2: What is SQL?](#chapter1part3.2)
      - [Chapter 1 - Part 3.3: SQL vs. Other Programming Languages](#chapter1part3.3)
      - [Chapter 1 - Part 3.4: SQL Statements and Syntax](#chapter1part3.4)
      - [Chapter 1 - Part 3.5: Data Types in SQL](#chapter1part3.5)
      - [Chapter 1 - Part 3.6: SQL Operators](#chapter1part3.6)
      - [Chapter 1 - Part 3.7: SQL Functions](#chapter1part3.7)
      - [Chapter 1 - Part 3.8: Different categories of SQL commands: DDL, DML, DCL, TCL, and DQL](#chapter1part3.8)
    - [Chapter 1 - Part 4: Setting Up Your SQL Environment (e.g., SQLite, MySQL, PostgreSQL)](#chapter1part4)
      - [Chapter 1 - Part 4.1: Choosing a Database Management System (DBMS)](#chapter1part4.1)
      - [Chapter 1 - Part 4.2: Setting Up SQLite](#chapter1part4.2)
      - [Chapter 1 - Part 4.3: Setting Up MySQL](#chapter1part4.3)
      - [Chapter 1 - Part 4.4: Setting Up PostgreSQL](#chapter1part4.4)
      - [Chapter 1 - Part 4.5: Setting Up DuckDB](#chapter1part4.5)
      - [Chapter 1 - Part 4.6: Connecting to a Database from a Programming Language](#chapter1part4.6)
    - [Chapter 1 - Part 5: Connecting to a Database and Running Basic Commands](#chapter1part5)
      - [Chapter 1 - Part 5.1: Establishing a Database Connection](#chapter1part5.1)
      - [Chapter 1 - Part 5.2: Running Basic SQL Commands](#chapter1part5.2)
    - [Chapter 1 - Part 6: Case Study Introduction: The "Online Bookstore" Database](#chapter1part6)
      - [Chapter 1 - Part 6.1: Introducing the Online Bookstore Database](#chapter1part6.1)
      - [Chapter 1 - Part 6.2: Detailed Table Schemas](#chapter1part6.2)
      - [Chapter 1 - Part 6.3: Example Scenarios and Queries](#chapter1part6.3)
2. [Chapter 2: Retriving Data with SELECT Statements](#chapter2)
    - [Chapter 2 - Part 1: Basic SELECT Statements: Choosing Columns](#chapter2part1)
      - [Chapter 2 - Part 1.1: Basic Syntax of the SELECT Statement](#chapter2part1.1)
      - [Chapter 2 - Part 1.2: Selecting Specific Columns](#chapter2part1.2)
      - [Chapter 2 - Part 1.3: Selecting All Columns Using the Asterisk (*) Wildcard](#chapter2part1.3)
      - [Chapter 2 - Part 1.4: Column Order in the SELECT Statement](#chapter2part1.4)
      - [Chapter 2 - Part 1.5: Retrieve only the unique values](#chapter2part1.5)
    - [Chapter 2 - Part 2: Filtering Data with WHERE Clauses: Conditions and Operators](#chapter2part2)
      - [Chapter 2 - Part 2.1: Understanding the WHERE Clause](#chapter2part2.1)
      - [Chapter 2 - Part 2.2: Comparison Operators](#chapter2part2.2)
      - [Chapter 2 - Part 2.3: Logical Operators](#chapter2part2.3)
      - [Chapter 2 - Part 2.4: Special Operators](#chapter2part2.4)
      - [Chapter 2 - Part 2.5: Operator Precedence](#chapter2part2.5)
      - [Chapter 2 - Part 2.6: Case Sensitivity](#chapter2part2.6)
      - [Chapter 2 - Part 2.7: Case() Functions](#chapter2part2.7)
      - [Chapter 2 - Part 2.8: Performance Considerations](#chapter2part2.8)
    - [Chapter 2 - Part 3: Sorting Data with ORDER BY: Ascending and Descending](#chapter2part3)
      - [Chapter 2 - Part 3.1: Understanding the ORDER BY Clause](#chapter2part3.1)
      - [Chapter 2 - Part 3.2: Practical Examples and Demonstrations](#chapter2part3.2)
    - [Chapter 2 - Part 4: Limiting Results with LIMIT: Retrieving Top N Rows](#chapter2part4)
      - [Chapter 2 - Part 4.1: Understanding the LIMIT Clause](#chapter2part4.1)
    - [Chapter 2 - Part 5: Using Aliases for Columns and Tables: Improving Readability](#chapter2part5)
      - [Chapter 2 - Part 5.1: Understanding Aliases](#chapter2part5.1)
      - [Chapter 2 - Part 5.2: Practical Examples and Demonstrations](#chapter2part5.2)
    - [Chapter 2 - Part 6: Practical Exercise: Querying the Bookstore Database](#chapter2part6)
      - [Chapter 2 - Part 6.1: Bookstore Database Schema](#chapter2part6.1)
      - [Chapter 2 - Part 6.2: Practical Exercises](#chapter2part6.2)
3. [Chapter 3: Working with Multiple Tables: Join](#chapter3)
    - [Chapter 3 - Part 1: Understanding Primary and Foreign Keys](#chapter3part1)
      - [Chapter 3 - Part 1.1: Understanding Primary Keys](#chapter3part1.1)
      - [Chapter 3 - Part 1.2: Understanding Foreign Keys](#chapter3part1.2)
      - [Chapter 3 - Part 1.3: Practical Examples and Demonstrations](#chapter3part1.3)
    - [Chapter 3 - Part 2: Introduction to JOINs: Combining Data from Multiple Tables](#chapter3part2)
      - [Chapter 3 - Part 2.1: Understanding Primary and Foreign Keys](#chapter3part2.1)
      - [Chapter 3 - Part 2.2: Introduction to JOINs: Combining Data from Multiple Tables](#chapter3part2.2)
      - [Chapter 3 - Part 2.3: Practical Examples and Demonstrations](#chapter3part2.3)
    - [Chapter 3 - Part 3: INNER JOIN: Retrieving Matching Rows](#chapter3part3)
      - [Chapter 3 - Part 3.1: Understanding INNER JOIN](#chapter3part3.1)
      - [Chapter 3 - Part 3.2: Practical Examples and Demonstrations](#chapter3part3.2)
    - [Chapter 3 - Part 4: LEFT JOIN (LEFT OUTER JOIN): Retrieving All Rows from the Left Table](#chapter3part4)
      - [Chapter 3 - Part 4.1: Understanding the LEFT JOIN](#chapter3part4.1)
      - [Chapter 3 - Part 4.2: Practical Examples Using the Bookstore Database](#chapter3part4.2)
    - [Chapter 3 - Part 5: RIGHT JOIN (RIGHT OUTER JOIN): Retrieving All Rows from the Right Table](#chapter3part5)
      - [Chapter 3 - Part 5.1: Understanding the RIGHT JOIN](#chapter3part5.1)
      - [Chapter 3 - Part 5.2: Practical Examples](#chapter3part5.2)
    - [Chapter 3 - Part 6: FULL OUTER JOIN: Retrieving All Rows from Both Tables](#chapter3part6)
      - [Chapter 3 - Part 6.1: Understanding FULL OUTER JOIN](#chapter3part6.1)
      - [Chapter 3 - Part 6.2: Practical Examples](#chapter3part6.2)
      - [Chapter 3 - Part 6.3: Real-World Application](#chapter3part6.3)
    - [Chapter 3 - Part 7: Practical Exercise: Joining Tables in the Bookstore Database](#chapter3part7)
      - [Chapter 3 - Part 7.1: Setting Up the Bookstore Database (Reminder)](#chapter3part7.1)
      - [Chapter 3 - Part 7.2: Exercise 1: Retrieving Book Titles and Author Names](#chapter3part7.2)
      - [Chapter 3 - Part 7.3: Exercise 2: Finding Customers and Their Orders](#chapter3part7.3)
      - [Chapter 3 - Part 7.4: Exercise 3: Retrieving Book Titles and Order Information](#chapter3part7.4)
      - [Chapter 3 - Part 7.5: Exercise 4: Using LEFT JOIN to Find Authors Without Books](#chapter3part7.5)
      - [Chapter 3 - Part 7.6: Exercise 5: Combining Different JOIN Types](#chapter3part7.6)
4. [Chapter 4: Data Manipulation: INSERT; UPDATE, and DELETE](#chapter4)
    - [Chapter 4 - Part 1: Inserting New Data with INSERT INTO](#chapter4part1)
      - [Chapter 4 - Part 1.1: Basic INSERT INTO Syntax](#chapter4part1.1)
      - [Chapter 4 - Part 1.2: Inserting Data into Specific Columns](#chapter4part1.2)
      - [Chapter 4 - Part 1.3: Inserting Multiple Rows](#chapter4part1.3)
      - [Chapter 4 - Part 1.4: Inserting Data from Another Table](#chapter4part1.4)
      - [Chapter 4 - Part 1.5: Data Type Considerations](#chapter4part1.5)
      - [Chapter 4 - Part 1.6: Handling Errors and Constraints](#chapter4part1.6)
      - [Chapter 4 - Part 1.7: Best Practices for INSERT INTO Statements](#chapter4part1.7)
    - [Chapter 4 - Part 2: Updating Existing Data with UPDATE](#chapter4part2)
      - [Chapter 4 - Part 2.1: The Basic Syntax of UPDATE](#chapter4part2.1)
      - [Chapter 4 - Part 2.2: Understanding the WHERE Clause](#chapter4part2.2)
      - [Chapter 4 - Part 2.3: Updating with Values from Another Table (Advanced)](#chapter4part2.3)
      - [Chapter 4 - Part 2.4: Important Considerations and Best Practices](#chapter4part2.4)
    - [Chapter 4 - Part 3: Deleting Data with DELETE FROM](#chapter4part3)
      - [Chapter 4 - Part 3.1: The DELETE FROM Statement: Basic Syntax](#chapter4part3.1)
      - [Chapter 4 - Part 3.2: Using the WHERE Clause Effectively](#chapter4part3.2)
      - [Chapter 4 - Part 3.3: The Importance of WHERE and the Dangers of Accidental Deletion](#chapter4part3.3)
    - [Chapter 4 - Part 4: Understanding Transactions: Ensuring Data Integrity](#chapter4part4)
      - [Chapter 4 - Part 4.1: Understanding the ACID Properties](#chapter4part4.1)
      - [Chapter 4 - Part 4.2: Managing Transactions in SQL](#chapter4part4.2)
      - [Chapter 4 - Part 4.3: Implicit vs. Explicit Transactions](#chapter4part4.3)
      - [Chapter 4 - Part 4.4: Savepoints: Rolling Back to a Specific Point](#chapter4part4.4)
      - [Chapter 4 - Part 4.5: Concurrency Control and Isolation Levels](#chapter4part4.5)
      - [Chapter 4 - Part 4.6: Practical Exercise: Implementing a Book Purchase Transaction](#chapter4part4.6)
      - [Chapter 4 - Part 4.7: Real-World Applications](#chapter4part4.7)
    - [Chapter 4 - Part 5: Practical Exercise: Modifying Data in the Bookstore Database](#chapter4part5)
      - [Chapter 4 - Part 5.1: Inserting New Data with INSERT INTO](#chapter4part5.1)
      - [Chapter 4 - Part 5.2: Updating Existing Data with UPDATE](#chapter4part5.2)
      - [Chapter 4 - Part 5.3: Deleting Data with DELETE FROM](#chapter4part5.3)
      - [Chapter 4 - Part 5.4: Understanding Transactions: Ensuring Data Integrity](#chapter4part5.4)
      - [Chapter 4 - Part 5.5: Importance of Backups and Data Recovery](#chapter4part5.5)
    - [Chapter 4 - Part 6: Importance of Backups and Data Recovery](#chapter4part6)
      - [Chapter 4 - Part 6.1: Why Backups are Essential](#chapter4part6.1)
      - [Chapter 4 - Part 6.2: Types of Backups](#chapter4part6.2)
      - [Chapter 4 - Part 6.3: Backup Strategies](#chapter4part6.3)
      - [Chapter 4 - Part 6.4: Data Recovery Process](#chapter4part6.4)
      - [Chapter 4 - Part 6.5: Testing Your Backups](#chapter4part6.5)
      - [Chapter 4 - Part 6.6: Real-World Application](#chapter4part6.6)
5. [Chapter 5: Aggregate Functions and Grouping](#chapter5)
    - [Chapter 5 - Part 1: Introduction to Aggregate Functions: COUNT, SUM, AVG, MIN, MAX](#chapter5part1)
      - [Chapter 5 - Part 1.1: Understanding Aggregate Functions](#chapter5part1.1)
      - [Chapter 5 - Part 1.2: COUNT() Function](#chapter5part1.2)
      - [Chapter 5 - Part 1.3: SUM() Function](#chapter5part1.3)
      - [Chapter 5 - Part 1.4: AVG() Function](#chapter5part1.4)
      - [Chapter 5 - Part 1.5: MIN() and MAX() Functions](#chapter5part1.5)
      - [Chapter 5 - Part 1.6: Combining Aggregate Functions](#chapter5part1.6)
      - [Chapter 5 - Part 1.7: Real-World Application](#chapter5part1.7)
    - [Chapter 5 - Part 2: Grouping Data with GROUP BY: Analyzing Data Subsets](#chapter5part2)
      - [Chapter 5 - Part 2.1: Understanding the GROUP BY Clause](#chapter5part2.1)
      - [Chapter 5 - Part 2.2: Practical Examples Using the Bookstore Database](#chapter5part2.2)
    - [Chapter 5 - Part 3: Filtering Groups with HAVING: Applying Conditions to Aggregated Data](#chapter5part3)
      - [Chapter 5 - Part 3.1: Understanding the HAVING Clause](#chapter5part3.1)
      - [Chapter 5 - Part 3.2: Practical Examples Using the Bookstore Database](#chapter5part3.2)
      - [Chapter 5 - Part 3.3: Real-World Application](#chapter5part3.3)
    - [Chapter 5 - Part 4: Combining Aggregate Functions and Joins](#chapter5part4)
      - [Chapter 5 - Part 4.1: Understanding the Synergy of Aggregate Functions and Joins](#chapter5part4.1)
      - [Chapter 5 - Part 4.2: Practical Examples in the Bookstore Database](#chapter5part4.2)
      - [Chapter 5 - Part 4.3: Filtering Groups with HAVING](#chapter5part4.3)
    - [Chapter 5 - Part 5: Practical Exercise: Analyzing Sales Data in the Bookstore Database](#chapter5part5)
      - [Chapter 5 - Part 5.1: Introduction to Aggregate Functions](#chapter5part5.1)
      - [Chapter 5 - Part 5.2: Grouping Data with GROUP BY](#chapter5part5.2)
      - [Chapter 5 - Part 5.3: Filtering Groups with HAVING](#chapter5part5.3)
      - [Chapter 5 - Part 5.4: Combining Aggregate Functions and Joins](#chapter5part5.4)
    - [Chapter 5 - Part 6: Common SQL Errors and Troubleshooting](#chapter5part6)
      - [Chapter 5 - Part 6.1: Common SQL Error Types](#chapter5part6.1)
      - [Chapter 5 - Part 6.2: Troubleshooting Techniques](#chapter5part6.2)
      - [Chapter 5 - Part 6.3: Practical Examples and Demonstrations](#chapter5part6.3)
6. [Chapter 6: Scalar Functions](#chapter6)
7. [Chapter 7: Case manipulation Functions](#chapter7)
8. [Chapter 8: Character manipulation Functions](#chapter8)
9. [Chapter 9: Case() Functions](#chapter9)
10. [Chapter 10: Set Operators](#chapter10)
11. [Chapter 11: Subqueries and Views](#chapter11)
    - [Chapter 11 - Part 1: Introduction to Subqueries: Queries Within Queries](#chapter11part1)
      - [Chapter 11 - Part 1.1: Understanding Subqueries](#chapter11part1.1)
      - [Chapter 11 - Part 1.2: Using Subqueries in WHERE Clauses](#chapter11part1.2)
      - [Chapter 11 - Part 1.3: Using Subqueries in SELECT Clauses](#chapter11part1.3)
      - [Chapter 11 - Part 1.4: Table Subqueries in the FROM Clause](#chapter11part1.4)
      - [Chapter 11 - Part 1.5: Table Subqueries in the HAVING Clause](#chapter11part1.5)
    - [Chapter 11 - Part 2: Using Subqueries in WHERE Clauses](#chapter11part2)
      - [Chapter 11 - Part 2.1: Understanding Subqueries in WHERE Clauses](#chapter11part2.1)
      - [Chapter 11 - Part 2.2: Single-Row Subqueries](#chapter11part2.2)
      - [Chapter 11 - Part 2.3: Multiple-Row Subqueries](#chapter11part2.3)
      - [Chapter 11 - Part 2.4: Correlated Subqueries](#chapter11part2.4)
    - [Chapter 11 - Part 3: Using Subqueries in SELECT Clauses](#chapter11part3)
      - [Chapter 11 - Part 3.1: Understanding Subqueries in the SELECT Clause](#chapter11part3.1)
      - [Chapter 11 - Part 3.2: Uncorrelated Subqueries in the SELECT Clause](#chapter11part3.2)
      - [Chapter 11 - Part 3.3: Correlated Subqueries in the SELECT Clause](#chapter11part3.3)
      - [Chapter 11 - Part 3.4: Practical Considerations and Best Practices](#chapter11part3.4)
    - [Chapter 11 - Part 4: Creating Views: Virtual Tables for Simplified Queries](#chapter11part4)
      - [Chapter 11 - Part 4.1: Understanding Views](#chapter11part4.1)
      - [Chapter 11 - Part 4.2: Creating Simple Views](#chapter11part4.2)
      - [Chapter 11 - Part 4.3: Creating Complex Views](#chapter11part4.3)
      - [Chapter 11 - Part 4.4: Advantages and Disadvantages of Using Views](#chapter11part4.4)
      - [Chapter 11 - Part 4.5: Updatable Views](#chapter11part4.5)
      - [Chapter 11 - Part 4.6: Dropping Views](#chapter11part4.6)
    - [Chapter 11 - Part 5: Advantages and Disadvantages of Using Views](#chapter11part5)
      - [Chapter 11 - Part 5.1: Advantages of Using Views](#chapter11part5.1)
      - [Chapter 11 - Part 5.2: Disadvantages of Using Views](#chapter11part5.2)
      - [Chapter 11 - Part 5.3: Practical Examples and Demonstrations](#chapter11part5.3)
    - [Chapter 11 - Part 6: Practical Exercise: Creating and Using Views in the Bookstore Database](#chapter11part6)
      - [Chapter 11 - Part 6.1: Creating Views](#chapter11part6.1)
      - [Chapter 11 - Part 6.2: Using Views](#chapter11part6.2)
      - [Chapter 11 - Part 6.3: Advantages and Disadvantages of Using Views](#chapter11part6.3)
12. [Chapter 12: CTE (Common Table Expression)](#chapter12)
13. [Chapter 13: Advanced SQL Concepts and Best Practices](#chapter13)
    - [Chapter 13 - Part 1: Introduction to Indexes: Improving Query Performance](#chapter13part1)
      - [Chapter 13 - Part 1.1: Understanding Indexes](#chapter13part1.1)
      - [Chapter 13 - Part 1.2: Types of Indexes](#chapter13part1.2)
      - [Chapter 13 - Part 1.3: Indexing Strategies](#chapter13part1.3)
      - [Chapter 13 - Part 1.4: Practical Examples and Demonstrations](#chapter13part1.4)
    - [Chapter 13 - Part 2: Understanding Different Types of Indexes](#chapter13part2)
      - [Chapter 13 - Part 2.1: Understanding Index Basics](#chapter13part2.1)
      - [Chapter 13 - Part 2.2: Types of Indexes](#chapter13part2.2)
      - [Chapter 13 - Part 2.3: Choosing the Right Index](#chapter13part2.3)
      - [Chapter 13 - Part 2.4: Indexing Strategies for the Bookstore Database](#chapter13part2.4)
    - [Chapter 13 - Part 3: Using EXPLAIN to Analyze Query Performance](#chapter13part3)
      - [Chapter 13 - Part 3.1: Introduction to EXPLAIN](#chapter13part3.1)
      - [Chapter 13 - Part 3.2: Interpreting EXPLAIN Output](#chapter13part3.2)
      - [Chapter 13 - Part 3.3: Optimizing Queries Based on EXPLAIN Output](#chapter13part3.3)
    - [Chapter 13 - Part 4: SQL Injection Prevention: Writing Secure Queries](#chapter13part4)
      - [Chapter 13 - Part 4.1: Understanding SQL Injection](#chapter13part4.1)
      - [Chapter 13 - Part 4.2: Preventing SQL Injection: Secure Coding Practices](#chapter13part4.2)
    - [Chapter 13 - Part 5: Introduction to Stored Procedures and Functions](#chapter13part5)
      - [Chapter 13 - Part 5.1: Understanding Stored Procedures](#chapter13part5.1)
      - [Chapter 13 - Part 5.2: Understanding Functions](#chapter13part5.2)
      - [Chapter 13 - Part 5.3: Real-World Applications](#chapter13part5.3)
    - [Chapter 13 - Part 6: Best Practices for Writing Clean and Efficient SQL Code](#chapter13part6)
      - [Chapter 13 - Part 6.1: Importance of Code Readability](#chapter13part6.1)
      - [Chapter 13 - Part 6.2: Writing Efficient SQL Queries](#chapter13part6.2)
    - [Chapter 13 - Part 7: Next Steps: Further Learning and Resources](#chapter13part7)
      - [Chapter 13 - Part 7.1: Delving Deeper: Advanced SQL Topics](#chapter13part7.1)
      - [Chapter 13 - Part 7.2: Online Resources and Communities](#chapter13part7.2)
      - [Chapter 13 - Part 7.3: Practical Projects and Exercises](#chapter13part7.3)
      - [Chapter 13 - Part 7.4: Best Practices for Continuous Learning](#chapter13part7.4)

     
<div align="center"><img src="img/example-w1054-h609.png" width=1054 height=609><br><sub>Example - (<a href='https://github.com/vitorstabile'>Work by Vitor Garcia</a>) </sub></div>

|               |                 |                 |                 |                 |                 |                 |                 |                 | 
| :-----------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
  
## <a name="chapter1"></a>Chapter 1: Introduction to Databases and SQL

#### <a name="chapter1part1"></a>Chapter 1 - Part 1: What is a Database and Why Use One?

#### <a name="chapter1part1.1"></a>Chapter 1 - Part 1.1: What is a Database?

#### <a name="chapter1part1.2"></a>Chapter 1 - Part 1.2: Why Use a Database?

#### <a name="chapter1part1.3"></a>Chapter 1 - Part 1.3: Real-World Applications

#### <a name="chapter1part2"></a>Chapter 1 - Part 2: Understanding Relational Databases and Tables

#### <a name="chapter1part2.1"></a>Chapter 1 - Part 2.1: Core Principles of Relational Databases

#### <a name="chapter1part2.2"></a>Chapter 1 - Part 2.2: Normalization

#### <a name="chapter1part2.3"></a>Chapter 1 - Part 2.3: Data Integrity

#### <a name="chapter1part2.4"></a>Chapter 1 - Part 2.4: The "Online Bookstore" Database

#### <a name="chapter1part3"></a>Chapter 1 - Part 3: Introduction to SQL: The Language of Databases

#### <a name="chapter1part3.1"></a>Chapter 1 - Part 3.1: Core Principles of Relational Databases

#### <a name="chapter1part3.2"></a>Chapter 1 - Part 3.2: What is SQL?

#### <a name="chapter1part3.3"></a>Chapter 1 - Part 3.3: SQL vs. Other Programming Languages

#### <a name="chapter1part3.4"></a>Chapter 1 - Part 3.4: SQL Statements and Syntax

#### <a name="chapter1part3.5"></a>Chapter 1 - Part 3.5: Data Types in SQL

#### <a name="chapter1part3.6"></a>Chapter 1 - Part 3.6: SQL Operators

#### <a name="chapter1part3.7"></a>Chapter 1 - Part 3.7: SQL Functions

#### <a name="chapter1part3.8"></a>Chapter 1 - Part 3.8: Different categories of SQL commands: DDL, DML, DCL, TCL, and DQL

<div align="center"><img src="img/sqlcommands-w984-h1104.jpg" width=984 height=1104><br><sub>SQL commands - (<a href='https://github.com/vitorstabile'>Work by Vitor Garcia</a>) </sub></div>

These categories represent the core functionalities you'll use to interact with databases.

- **Data Definition Language (DDL):**
  - **Purpose:** DDL is used to define and manage the structure of your database. Think of it as the blueprint for your database.
    - **Common Commands:**
      - ```CREATE```: Used to create database objects like tables, indexes, and views.
        - Example: ```CREATE TABLE Employees (ID INT, Name VARCHAR(255));```
      - ```ALTER```: Used to modify the structure of existing database objects.
        - Example: ```ALTER TABLE Employees ADD COLUMN Salary DECIMAL(10, 2);```
      - ```DROP```: Used to delete database objects.
        - Example: ```DROP TABLE Employees;```
      - ```TRUNCATE```: Used to remove all data from a table, but the table structure remains.
        - Example: ```TRUNCATE TABLE Employees;```
      - ```RENAME```: Used to rename a database object.
        - Example: ```RENAME TABLE Employees TO Staff;```
       
- **Data Manipulation Language (DML):**
  - **Purpose:** DML is used to manipulate the data stored within the database. This includes inserting, updating, and deleting data.
    - **Common Commands:**
      - ```INSERT```: Used to insert new data into a table.
        - Example: ```INSERT INTO Employees (ID, Name) VALUES (1, 'John Doe');```
      - ```UPDATE```: Used to modify existing data in a table.
        - Example: ```UPDATE Employees SET Salary = 50000 WHERE ID = 1;```
      - ```DELETE```: Used to delete data from a table.
        - Example: ```DELETE FROM Employees WHERE ID = 1;```
       
- **Data Control Language (DCL):**
  - **Purpose:** DCL is used to control access and permissions within the database. It's all about security and who can do what.
    - **Common Commands:**
      - ```GRANT```: Used to grant privileges to users or roles.
        - Example: ```GRANT SELECT, INSERT ON Employees TO user1;```
      - ```REVOKE```: Used to revoke privileges from users or roles.
        - Example: ```REVOKE SELECT ON Employees FROM user1;```
       
- **Transaction Control Language (TCL):**
  - **Purpose:** TCL is used to manage transactions within the database. Transactions are sequences of operations that should be treated as a single unit of work.
    - **Common Commands:**
      - ```COMMIT```: Used to save all changes made during a transaction.
      - ```ROLLBACK```: Used to undo all changes made during a transaction, reverting the database to its previous state.
      - ```SAVEPOINT```: Used to set a point within a transaction to which you can later rollback.
     
- **Data Query Language (DQL):**
  - **Purpose:** DQL is used to query and retrieve data from the database. The primary DQL command is ```SELECT```.
    - **Common Commands:**
      - ```SELECT```: Used to retrieve data from one or more tables.
        - Example: ```SELECT * FROM Employees; (selects all columns and rows)```
        - Example: ```SELECT Name, Salary FROM Employees WHERE Salary > 40000;``` (selects specific columns and filters rows)

#### <a name="chapter1part4"></a>Chapter 1 - Part 4: Setting Up Your SQL Environment (e.g., SQLite, MySQL, PostgreSQL, DuckDB)

#### <a name="chapter1part4.1"></a>Chapter 1 - Part 4.1: Choosing a Database Management System (DBMS)

#### <a name="chapter1part4.2"></a>Chapter 1 - Part 4.2: Setting Up SQLite

#### <a name="chapter1part4.3"></a>Chapter 1 - Part 4.3: Setting Up MySQL

#### <a name="chapter1part4.4"></a>Chapter 1 - Part 4.4: Setting Up PostgreSQL

Setting up a PostgreSQL environment involves a few more steps than SQLite, but it's still straightforward. Here's a guide to get you started

**1. Download and Install PostgreSQL:**

- **Windows:**
  - Download the installer from the official PostgreSQL website (https://www.postgresql.org/download/windows/).
  - Run the installer and follow the on-screen instructions.
  - You'll be prompted to set a password for the ```postgres``` user (the default administrative user). Remember this password!
  - The installer may also ask if you want to install pgAdmin, a graphical administration tool. It's highly recommended to install it.

- **macOS:**
  - Using Homebrew: If you have Homebrew installed, you can use the following commands in your terminal:
    
  ```
  brew install postgresql
  brew services start postgresql
  ```
  
  - Using the EDB Installer: Download the installer from the official PostgreSQL website (https://www.postgresql.org/download/macosx/). This is similar to the Windows installer.

- **Linux (Debian/Ubuntu):**

```
sudo apt update
sudo apt install postgresql postgresql-contrib
```

- **Linux (Fedora/CentOS/RHEL):**

```
sudo dnf install postgresql-server postgresql-contrib
sudo postgresql-setup initdb
sudo systemctl start postgresql
sudo systemctl enable postgresql
```

**2. Verify the Installation:**

- **Windows:**
  - Open pgAdmin (if you installed it). You should see a server connection to PostgreSQL. If not, you may need to manually add a server connection, using ```localhost``` or ```127.0.0.1``` as the hostname, port ```5432``` (the default), and the ```postgres``` user.

- **macOS (Homebrew):**
  - In your terminal, try:

```
psql --version
```

  - This should print the PostgreSQL version.

- **Linux:**
  -  In your terminal, try:
 
```
psql --version
```

  - This should print the PostgreSQL version.

**3. Connect to the PostgreSQL Server:**

- **Using ```psql``` (command-line):**
  - Open your terminal or command prompt.
  - Type ```psql -U postgres``` and press Enter. You'll be prompted for the password you set during installation.
  - If successful, you'll see the ```postgres=#``` prompt. You're now connected to the PostgreSQL server as the ```postgres``` user.
 
- **Using pgAdmin (GUI):**
  - Open pgAdmin.
  - If you don't already have a server connection, create one (right-click on "Servers" and choose "Create" -> "Server").
  - Enter the connection details:
    - **Name:** A descriptive name for the connection (e.g., "Local PostgreSQL").
    - **Host name/address:** ```localhost``` or ```127.0.0.1```.
    - **Port:** ```5432``` (default).
    - **Maintenance database:** ```postgres```.
    - **Username:** ```postgres```.
    - **Password:** The password you set during installation.
  - Click "Save". You should now be able to connect to the server.
 
**4. Create a Database (for the Bookstore):**

- **Using ```psql```:**

```sql
CREATE DATABASE bookstore;
```
- **Using pgAdmin:**
  - Right-click on the server connection in pgAdmin.
  - Choose "Create" -> "Database".
  - Enter "bookstore" as the database name.
  - Click "Save".

**5. Connect to the ```bookstore``` Database:**

- **Using ```psql```:**

```sql
\c bookstore
```
(This is a ```psql``` command, not an SQL command.) You should now see the ```bookstore=#``` prompt.

- **Using pgAdmin:**
  - In pgAdmin, expand the server connection.
  - You should see the "bookstore" database listed. You can now right-click on it and choose "Query Tool" to open a query window connected to the ```bookstore``` database.

**Important Considerations:**

- **Firewall:** Make sure your firewall isn't blocking connections to port 5432.
- **Security:** The ```postgres``` user is a superuser. For production environments, it's crucial to create separate users with more limited privileges.
- **pgAdmin:** pgAdmin is a powerful tool for managing PostgreSQL databases. Explore its features to create tables, run queries, and manage users.

#### <a name="chapter1part4.5"></a>Chapter 1 - Part 4.5: Setting Up DuckDB

setting up DuckDB is remarkably simple compared to other SQL environments like MySQL or PostgreSQL. DuckDB is an in-process SQL OLAP database management system. This means it runs directly within your application's process and doesn't require a separate server. It stores data in a single file (or in memory), making it very easy to set up and use.

Here's how to set up a DuckDB environment:

**1. Download and Install DuckDB CLI:**

- **Windows:**
  - Download the CLI from the DuckDB Repoitory (https://github.com/duckdb/duckdb/releases/download/v1.2.2/duckdb_cli-windows-amd64.zip).
  - Extract the content of the zip file
  - Run the .exe file
 
- **macOS**
  - In your terminal, try:

```
curl https://install.duckdb.org | sh
```

- **Linux:**
  -  In your terminal, try:
 
```
curl https://install.duckdb.org | sh
```

#### <a name="chapter1part4.6"></a>Chapter 1 - Part 4.6: Connecting to a Database from a Programming Language

#### <a name="chapter1part5"></a>Chapter 1 - Part 5: Connecting to a Database and Running Basic Commands

#### <a name="chapter1part5.1"></a>Chapter 1 - Part 5.1: Establishing a Database Connection

#### <a name="chapter1part5.2"></a>Chapter 1 - Part 5.2: Running Basic SQL Commands

#### <a name="chapter1part6"></a>Chapter 1 - Part 6: Case Study Introduction: The "Online Bookstore" Database

#### <a name="chapter1part6.1"></a>Chapter 1 - Part 6.1: Introducing the Online Bookstore Database

#### <a name="chapter1part6.2"></a>Chapter 1 - Part 6.2: Detailed Table Schemas

#### <a name="chapter1part6.3"></a>Chapter 1 - Part 6.3: Example Scenarios and Queries

## <a name="chapter2"></a>Chapter 2: Retriving Data with SELECT Statements

#### <a name="chapter2part1"></a>Chapter 2 - Part 1: Basic SELECT Statements: Choosing Columns

#### <a name="chapter2part1.1"></a>Chapter 2 - Part 1.1: Basic Syntax of the SELECT Statement

#### <a name="chapter2part1.2"></a>Chapter 2 - Part 1.2: Selecting Specific Columns

#### <a name="chapter2part1.3"></a>Chapter 2 - Part 1.3: Selecting All Columns Using the Asterisk (*) Wildcard

#### <a name="chapter2part1.4"></a>Chapter 2 - Part 1.4: Column Order in the SELECT Statement

#### <a name="chapter2part1.5"></a>Chapter 2 - Part 1.5: Retrieve only the unique values

The ```DISTINCT``` keyword is used to retrieve only the unique values from a specified column (or columns) in a table. It eliminates duplicate rows from the result set.

Let's say in our "Online Bookstore" database, we have a books table with the following data:


| book_id | title                    | author          | genre        |
| :-----: | :----------------------: | :-------------: | :----------: |
| 1       | "The Great Novel"        |  "Jane Doe"     | "Fiction"    |
| 2       | "Data Science Handbook"  |  "John Smith"   | "Technical"  |
| 3       | "The Great Novel"        |  "Jane Doe"     | "Fiction"    |
| 4       | "SQL for Beginners"      |  "Alice Brown"  | "Technical"  |
| 5       | "The Great Novel"        | "Jane Doe"      | "Fiction"    |
| 6       | "Advanced SQL"           | "Michael Davis" | "Technical"  |

If we want to find out the unique genres in our ```books``` table, we can use the following query:

```sql
SELECT DISTINCT genre
FROM books;
```

| genre        |
| :----------: |
| "Fiction"    |
| "Technical"  |

As you can see, even though "Fiction" appears three times and "Technical" appears three times in the ```books``` table, the ```DISTINCT``` keyword ensures that each genre is listed only once in the result set.

**Important Notes:**

- ```DISTINCT``` applies to all the columns listed in the ```SELECT``` statement. If you have ```SELECT DISTINCT column1, column2```, the result will show unique combinations of ```column1v and ```column2```.

- ```DISTINCT``` is case-sensitive. For example, "Fiction" and "fiction" would be considered different values.

- ```DISTINCT``` can impact performance, especially on large tables. The database needs to sort the data to identify unique rows.

#### <a name="chapter2part2"></a>Chapter 2 - Part 2: Filtering Data with WHERE Clauses: Conditions and Operators

#### <a name="chapter2part2.1"></a>Chapter 2 - Part 2.1: Understanding the WHERE Clause

#### <a name="chapter2part2.2"></a>Chapter 2 - Part 2.2: Comparison Operators

#### <a name="chapter2part2.3"></a>Chapter 2 - Part 2.3: Logical Operators

#### <a name="chapter2part2.4"></a>Chapter 2 - Part 2.4: Special Operators

#### <a name="chapter2part2.5"></a>Chapter 2 - Part 2.5: Operator Precedence

#### <a name="chapter2part2.6"></a>Chapter 2 - Part 2.6: Case Sensitivity

#### <a name="chapter2part2.7"></a>Chapter 2 - Part 2.7: Case() Functions

#### <a name="chapter2part2.8"></a>Chapter 2 - Part 2.8: Performance Considerations

#### <a name="chapter2part3"></a>Chapter 2 - Part 3: Sorting Data with ORDER BY: Ascending and Descending

#### <a name="chapter2part3.1"></a>Chapter 2 - Part 3.1: Understanding the ORDER BY Clause

#### <a name="chapter2part3.2"></a>Chapter 2 - Part 3.2: Practical Examples and Demonstrations

#### <a name="chapter2part4"></a>Chapter 2 - Part 4: Limiting Results with LIMIT: Retrieving Top N Rows

#### <a name="chapter2part4.1"></a>Chapter 2 - Part 4.1: Understanding the LIMIT Clause

#### <a name="chapter2part5"></a>Chapter 2 - Part 5: Using Aliases for Columns and Tables: Improving Readability

#### <a name="chapter2part5.1"></a>Chapter 2 - Part 5.1: Understanding Aliases

#### <a name="chapter2part5.2"></a>Chapter 2 - Part 5.2: Practical Examples and Demonstrations

#### <a name="chapter2part6"></a>Chapter 2 - Part 6: Practical Exercise: Querying the Bookstore Database

#### <a name="chapter2part6.1"></a>Chapter 2 - Part 6.1: Bookstore Database Schema

#### <a name="chapter2part6.2"></a>Chapter 2 - Part 6.2: Practical Exercises

## <a name="chapter3"></a>Chapter 3: Working with Multiple Tables: Join

#### <a name="chapter3part1"></a>Chapter 3 - Part 1: Understanding Primary and Foreign Keys

#### <a name="chapter3part1.1"></a>Chapter 3 - Part 1.1: Understanding Primary Keys

#### <a name="chapter3part1.2"></a>Chapter 3 - Part 1.2: Understanding Foreign Keys

#### <a name="chapter3part1.3"></a>Chapter 3 - Part 1.3: Practical Examples and Demonstrations

#### <a name="chapter3part2"></a>Chapter 3 - Part 2: Introduction to JOINs: Combining Data from Multiple Tables

#### <a name="chapter3part2.1"></a>Chapter 3 - Part 2.1: Understanding Primary and Foreign Keys

#### <a name="chapter3part2.2"></a>Chapter 3 - Part 2.2: Introduction to JOINs: Combining Data from Multiple Tables

#### <a name="chapter3part2.3"></a>Chapter 3 - Part 2.3: Practical Examples and Demonstrations

#### <a name="chapter3part3"></a>Chapter 3 - Part 3: INNER JOIN: Retrieving Matching Rows

#### <a name="chapter3part3.1"></a>Chapter 3 - Part 3.1: Understanding INNER JOIN

#### <a name="chapter3part3.2"></a>Chapter 3 - Part 3.2: Practical Examples and Demonstrations

#### <a name="chapter3part4"></a>Chapter 3 - Part 4: LEFT JOIN (LEFT OUTER JOIN): Retrieving All Rows from the Left Table

#### <a name="chapter3part4.1"></a>Chapter 3 - Part 4.1: Understanding the LEFT JOIN

#### <a name="chapter3part4.2"></a>Chapter 3 - Part 4.2: Practical Examples Using the Bookstore Database

#### <a name="chapter3part5"></a>Chapter 3 - Part 5: RIGHT JOIN (RIGHT OUTER JOIN): Retrieving All Rows from the Right Table

#### <a name="chapter3part5.1"></a>Chapter 3 - Part 5.1: Understanding the RIGHT JOIN

#### <a name="chapter3part5.2"></a>Chapter 3 - Part 5.2: Practical Examples

#### <a name="chapter3part6"></a>Chapter 3 - Part 6: FULL OUTER JOIN: Retrieving All Rows from Both Tables

#### <a name="chapter3part6.1"></a>Chapter 3 - Part 6.1: Understanding FULL OUTER JOIN

#### <a name="chapter3part6.2"></a>Chapter 3 - Part 6.2: Practical Examples

#### <a name="chapter3part6.3"></a>Chapter 3 - Part 6.3: Real-World Application

#### <a name="chapter3part7"></a>Chapter 3 - Part 7: Practical Exercise: Joining Tables in the Bookstore Database

#### <a name="chapter3part7.1"></a>Chapter 3 - Part 7.1: Setting Up the Bookstore Database (Reminder)

#### <a name="chapter3part7.2"></a>Chapter 3 - Part 7.2: Exercise 1: Retrieving Book Titles and Author Names

#### <a name="chapter3part7.3"></a>Chapter 3 - Part 7.3: Exercise 2: Finding Customers and Their Orders

#### <a name="chapter3part7.4"></a>Chapter 3 - Part 7.4: Exercise 3: Retrieving Book Titles and Order Information

#### <a name="chapter3part7.5"></a>Chapter 3 - Part 7.5: Exercise 4: Using LEFT JOIN to Find Authors Without Books

#### <a name="chapter3part7.6"></a>Chapter 3 - Part 7.6: Exercise 5: Combining Different JOIN Types

## <a name="chapter4"></a>Chapter 4: Data Manipulation: INSERT; UPDATE, and DELETE

#### <a name="chapter4part1"></a>Chapter 4 - Part 1: Inserting New Data with INSERT INTO

#### <a name="chapter4part1.1"></a>Chapter 4 - Part 1.1: Basic INSERT INTO Syntax

#### <a name="chapter4part1.2"></a>Chapter 4 - Part 1.2: Inserting Data into Specific Columns

#### <a name="chapter4part1.3"></a>Chapter 4 - Part 1.3: Inserting Multiple Rows

#### <a name="chapter4part1.4"></a>Chapter 4 - Part 1.4: Inserting Data from Another Table

#### <a name="chapter4part1.5"></a>Chapter 4 - Part 1.5: Data Type Considerations

#### <a name="chapter4part1.6"></a>Chapter 4 - Part 1.6: Handling Errors and Constraints

#### <a name="chapter4part1.7"></a>Chapter 4 - Part 1.7: Best Practices for INSERT INTO Statements

#### <a name="chapter4part2"></a>Chapter 4 - Part 2: Updating Existing Data with UPDATE

#### <a name="chapter4part2.1"></a>Chapter 4 - Part 2.1: The Basic Syntax of UPDATE

#### <a name="chapter4part2.2"></a>Chapter 4 - Part 2.2: Understanding the WHERE Clause

#### <a name="chapter4part2.3"></a>Chapter 4 - Part 2.3: Updating with Values from Another Table (Advanced)

#### <a name="chapter4part2.4"></a>Chapter 4 - Part 2.4: Important Considerations and Best Practices

#### <a name="chapter4part3"></a>Chapter 4 - Part 3: Deleting Data with DELETE FROM

#### <a name="chapter4part3.1"></a>Chapter 4 - Part 3.1: The DELETE FROM Statement: Basic Syntax

#### <a name="chapter4part3.2"></a>Chapter 4 - Part 3.2: Using the WHERE Clause Effectively

#### <a name="chapter4part3.3"></a>Chapter 4 - Part 3.3: The Importance of WHERE and the Dangers of Accidental Deletion

#### <a name="chapter4part4"></a>Chapter 4 - Part 4: Understanding Transactions: Ensuring Data Integrity

#### <a name="chapter4part4.1"></a>Chapter 4 - Part 4.1: Understanding the ACID Properties

#### <a name="chapter4part4.2"></a>Chapter 4 - Part 4.2: Managing Transactions in SQL

#### <a name="chapter4part4.3"></a>Chapter 4 - Part 4.3: Implicit vs. Explicit Transactions

#### <a name="chapter4part4.4"></a>Chapter 4 - Part 4.4: Savepoints: Rolling Back to a Specific Point

#### <a name="chapter4part4.5"></a>Chapter 4 - Part 4.5: Concurrency Control and Isolation Levels

#### <a name="chapter4part4.6"></a>Chapter 4 - Part 4.6: Practical Exercise: Implementing a Book Purchase Transaction

#### <a name="chapter4part4.7"></a>Chapter 4 - Part 4.7: Real-World Applications

#### <a name="chapter4part5"></a>Chapter 4 - Part 5: Practical Exercise: Modifying Data in the Bookstore Database

#### <a name="chapter4part5.1"></a>Chapter 4 - Part 5.1: Inserting New Data with INSERT INTO

#### <a name="chapter4part5.2"></a>Chapter 4 - Part 5.2: Updating Existing Data with UPDATE

#### <a name="chapter4part5.3"></a>Chapter 4 - Part 5.3: Deleting Data with DELETE FROM

#### <a name="chapter4part5.4"></a>Chapter 4 - Part 5.4: Understanding Transactions: Ensuring Data Integrity

#### <a name="chapter4part5.5"></a>Chapter 4 - Part 5.5: Importance of Backups and Data Recovery

#### <a name="chapter4part6"></a>Chapter 4 - Part 6: Importance of Backups and Data Recovery

#### <a name="chapter4part6.1"></a>Chapter 4 - Part 6.1: Why Backups are Essential

#### <a name="chapter4part6.2"></a>Chapter 4 - Part 6.2: Types of Backups

#### <a name="chapter4part6.3"></a>Chapter 4 - Part 6.3: Backup Strategies

#### <a name="chapter4part6.4"></a>Chapter 4 - Part 6.4: Data Recovery Process

#### <a name="chapter4part6.5"></a>Chapter 4 - Part 6.5: Testing Your Backups

#### <a name="chapter4part6.6"></a>Chapter 4 - Part 6.6: Real-World Application

## <a name="chapter5"></a>Chapter 5: Aggregate Functions and Grouping

#### <a name="chapter5part1"></a>Chapter 5 - Part 1: Introduction to Aggregate Functions: COUNT, SUM, AVG, MIN, MAX

#### <a name="chapter5part1.1"></a>Chapter 5 - Part 1.1: Understanding Aggregate Functions

#### <a name="chapter5part1.2"></a>Chapter 5 - Part 1.2: COUNT() Function

#### <a name="chapter5part1.3"></a>Chapter 5 - Part 1.3: SUM() Function

#### <a name="chapter5part1.4"></a>Chapter 5 - Part 1.4: AVG() Function

#### <a name="chapter5part1.5"></a>Chapter 5 - Part 1.5: MIN() and MAX() Functions

#### <a name="chapter5part1.6"></a>Chapter 5 - Part 1.6: Combining Aggregate Functions

#### <a name="chapter5part1.7"></a>Chapter 5 - Part 1.7: Real-World Application

#### <a name="chapter5part2"></a>Chapter 5 - Part 2: Grouping Data with GROUP BY: Analyzing Data Subsets

#### <a name="chapter5part2.1"></a>Chapter 5 - Part 2.1: Understanding the GROUP BY Clause

#### <a name="chapter5part2.2"></a>Chapter 5 - Part 2.2: Practical Examples Using the Bookstore Database

#### <a name="chapter5part3"></a>Chapter 5 - Part 3: Filtering Groups with HAVING: Applying Conditions to Aggregated Data

#### <a name="chapter5part3.1"></a>Chapter 5 - Part 3.1: Understanding the HAVING Clause

#### <a name="chapter5part3.2"></a>Chapter 5 - Part 3.2: Practical Examples Using the Bookstore Database

#### <a name="chapter5part3.3"></a>Chapter 5 - Part 3.3: Real-World Application

#### <a name="chapter5part4"></a>Chapter 5 - Part 4: Combining Aggregate Functions and Joins

#### <a name="chapter5part4.1"></a>Chapter 5 - Part 4.1: Understanding the Synergy of Aggregate Functions and Joins

#### <a name="chapter5part4.2"></a>Chapter 5 - Part 4.2: Practical Examples in the Bookstore Database

#### <a name="chapter5part4.3"></a>Chapter 5 - Part 4.3: Filtering Groups with HAVING

#### <a name="chapter5part5"></a>Chapter 5 - Part 5: Practical Exercise: Analyzing Sales Data in the Bookstore Database

#### <a name="chapter5part5.1"></a>Chapter 5 - Part 5.1: Introduction to Aggregate Functions

#### <a name="chapter5part5.2"></a>Chapter 5 - Part 5.2: Grouping Data with GROUP BY

#### <a name="chapter5part5.3"></a>Chapter 5 - Part 5.3: Filtering Groups with HAVING

#### <a name="chapter5part5.4"></a>Chapter 5 - Part 5.4: Combining Aggregate Functions and Joins

#### <a name="chapter5part6"></a>Chapter 5 - Part 6: Common SQL Errors and Troubleshooting

#### <a name="chapter5part6.1"></a>Chapter 5 - Part 6.1: Common SQL Error Types

#### <a name="chapter5part6.2"></a>Chapter 5 - Part 6.2: Troubleshooting Techniques

#### <a name="chapter5part6.3"></a>Chapter 5 - Part 6.3: Practical Examples and Demonstrations

## <a name="chapter6"></a>Chapter 6: Scalar Functions

## <a name="chapter7"></a>Chapter 7: Case manipulation Functions

## <a name="chapter8"></a>Chapter 8: Character manipulation Functions

## <a name="chapter9"></a>Chapter 9: Case() Functions

## <a name="chapter10"></a>Chapter 10: Set Operators

## <a name="chapter11"></a>Chapter 11: Subqueries and Views

#### <a name="chapter11part1"></a>Chapter 11 - Part 1: Introduction to Subqueries: Queries Within Queries

#### <a name="chapter11part1.1"></a>Chapter 11 - Part 1.1: Understanding Subqueries

#### <a name="chapter11part1.2"></a>Chapter 11 - Part 1.2: Using Subqueries in WHERE Clauses

#### <a name="chapter11part1.3"></a>Chapter 11 - Part 1.3: Using Subqueries in SELECT Clauses

#### <a name="chapter11part1.4"></a>Chapter 11 - Part 1.4: Table Subqueries in the FROM Clause

#### <a name="chapter11part1.5"></a>Chapter 11 - Part 1.5: Table Subqueries in the HAVING Clause

#### <a name="chapter11part2"></a>Chapter 11 - Part 2: Using Subqueries in WHERE Clauses

#### <a name="chapter11part2.1"></a>Chapter 11 - Part 2.1: Understanding Subqueries in WHERE Clauses

#### <a name="chapter11part2.2"></a>Chapter 11 - Part 2.2: Single-Row Subqueries

#### <a name="chapter11part2.3"></a>Chapter 11 - Part 2.3: Multiple-Row Subqueries

#### <a name="chapter11part2.4"></a>Chapter 11 - Part 2.4: Correlated Subqueries

#### <a name="chapter11part3"></a>Chapter 11 - Part 3: Using Subqueries in SELECT Clauses

#### <a name="chapter11part3.1"></a>Chapter 11 - Part 3.1: Understanding Subqueries in the SELECT Clause

#### <a name="chapter11part3.2"></a>Chapter 11 - Part 3.2: Uncorrelated Subqueries in the SELECT Clause

#### <a name="chapter11part3.3"></a>Chapter 11 - Part 3.3: Correlated Subqueries in the SELECT Clause

#### <a name="chapter11part3.4"></a>Chapter 11 - Part 3.4: Practical Considerations and Best Practices

#### <a name="chapter11part4"></a>Chapter 11 - Part 4: Creating Views: Virtual Tables for Simplified Queries

#### <a name="chapter11part4.1"></a>Chapter 11 - Part 4.1: Understanding Views

#### <a name="chapter11part4.2"></a>Chapter 11 - Part 4.2: Creating Simple Views

#### <a name="chapter11part4.3"></a>Chapter 11 - Part 4.3: Creating Complex Views

#### <a name="chapter11part4.4"></a>Chapter 11 - Part 4.4: Advantages and Disadvantages of Using Views

#### <a name="chapter11part4.5"></a>Chapter 11 - Part 4.5: Updatable Views

#### <a name="chapter11part4.6"></a>Chapter 11 - Part 4.6: Dropping Views

#### <a name="chapter11part5"></a>Chapter 11 - Part 5: Advantages and Disadvantages of Using Views

#### <a name="chapter11part5.1"></a>Chapter 11 - Part 5.1: Advantages of Using Views

#### <a name="chapter11part5.2"></a>Chapter 11 - Part 5.2: Disadvantages of Using Views

#### <a name="chapter11part5.3"></a>Chapter 11 - Part 5.3: Practical Examples and Demonstrations

#### <a name="chapter11part6"></a>Chapter 11 - Part 6: Practical Exercise: Creating and Using Views in the Bookstore Database

#### <a name="chapter11part6.1"></a>Chapter 11 - Part 6.1: Creating Views

#### <a name="chapter11part6.2"></a>Chapter 11 - Part 6.2: Using Views

#### <a name="chapter11part6.3"></a>Chapter 11 - Part 6.3: Advantages and Disadvantages of Using Views

## <a name="chapter12"></a>Chapter 12: CTE (Common Table Expression)

## <a name="chapter13"></a>Chapter 13: Advanced SQL Concepts and Best Practices

#### <a name="chapter13part1"></a>Chapter 13 - Part 1: Introduction to Indexes: Improving Query Performance

#### <a name="chapter13part1.1"></a>Chapter 13 - Part 1.1: Understanding Indexes

#### <a name="chapter13part1.2"></a>Chapter 13 - Part 1.2: Types of Indexes

#### <a name="chapter13part1.3"></a>Chapter 13 - Part 1.3: Indexing Strategies

#### <a name="chapter13part1.4"></a>Chapter 13 - Part 1.4: Practical Examples and Demonstrations

#### <a name="chapter13part2"></a>Chapter 13 - Part 2: Understanding Different Types of Indexes

#### <a name="chapter13part2.1"></a>Chapter 13 - Part 2.1: Understanding Index Basics

#### <a name="chapter13part2.2"></a>Chapter 13 - Part 2.2: Types of Indexes

#### <a name="chapter13part2.3"></a>Chapter 13 - Part 2.3: Choosing the Right Index

#### <a name="chapter13part2.4"></a>Chapter 13 - Part 2.4: Indexing Strategies for the Bookstore Database

#### <a name="chapter13part3"></a>Chapter 13 - Part 3: Using EXPLAIN to Analyze Query Performance

#### <a name="chapter13part3.1"></a>Chapter 13 - Part 3.1: Introduction to EXPLAIN

#### <a name="chapter13part3.2"></a>Chapter 13 - Part 3.2: Interpreting EXPLAIN Output

#### <a name="chapter13part3.3"></a>Chapter 13 - Part 3.3: Optimizing Queries Based on EXPLAIN Output

#### <a name="chapter13part4"></a>Chapter 13 - Part 4: SQL Injection Prevention: Writing Secure Queries

#### <a name="chapter13part4.1"></a>Chapter 13 - Part 4.1: Understanding SQL Injection

#### <a name="chapter13part4.2"></a>Chapter 13 - Part 4.2: Preventing SQL Injection: Secure Coding Practices

#### <a name="chapter13part5"></a>Chapter 13 - Part 5: Introduction to Stored Procedures and Functions

#### <a name="chapter13part5.1"></a>Chapter 13 - Part 5.1: Understanding Stored Procedures

#### <a name="chapter13part5.2"></a>Chapter 13 - Part 5.2: Understanding Functions

#### <a name="chapter13part5.3"></a>Chapter 13 - Part 5.3: Real-World Applications

#### <a name="chapter13part6"></a>Chapter 13 - Part 6: Best Practices for Writing Clean and Efficient SQL Code

#### <a name="chapter13part6.1"></a>Chapter 13 - Part 6.1: Importance of Code Readability

#### <a name="chapter13part6.2"></a>Chapter 13 - Part 6.2: Writing Efficient SQL Queries

#### <a name="chapter13part7"></a>Chapter 13 - Part 7: Next Steps: Further Learning and Resources

#### <a name="chapter13part7.1"></a>Chapter 13 - Part 7.1: Delving Deeper: Advanced SQL Topics

#### <a name="chapter13part7.2"></a>Chapter 13 - Part 7.2: Online Resources and Communities

#### <a name="chapter13part7.3"></a>Chapter 13 - Part 7.3: Practical Projects and Exercises

#### <a name="chapter13part7.4"></a>Chapter 13 - Part 7.4: Best Practices for Continuous Learning
