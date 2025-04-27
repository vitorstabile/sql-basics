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
      - [Chapter 1 - Part 3.1: What is SQL?](#chapter1part3.1)
      - [Chapter 1 - Part 3.2: SQL vs. Other Programming Languages](#chapter1part3.2)
      - [Chapter 1 - Part 3.3: SQL Statements and Syntax](#chapter1part3.3)
      - [Chapter 1 - Part 3.4: Data Types in SQL](#chapter1part3.4)
      - [Chapter 1 - Part 3.5: SQL Operators](#chapter1part3.5)
      - [Chapter 1 - Part 3.6: SQL Functions](#chapter1part3.6)
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
    - [Chapter 4 - Part 5: Importance of Backups and Data Recovery](#chapter4part5)
      - [Chapter 4 - Part 5.1: Why Backups are Essential](#chapter4part5.1)
      - [Chapter 4 - Part 5.2: Types of Backups](#chapter4part5.2)
      - [Chapter 4 - Part 5.3: Backup Strategies](#chapter4part5.3)
      - [Chapter 4 - Part 5.4: Data Recovery Process](#chapter4part5.4)
      - [Chapter 4 - Part 5.5: Testing Your Backups](#chapter4part5.5)
      - [Chapter 4 - Part 5.6: Real-World Application](#chapter4part5.6)
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
    - [Chapter 5 - Part 4: Combining Aggregate Functions and Joins](#chapter5part4)
      - [Chapter 5 - Part 4.1: Understanding the Synergy of Aggregate Functions and Joins](#chapter5part4.1)
      - [Chapter 5 - Part 4.2: Practical Examples in the Bookstore Database](#chapter5part4.2)
      - [Chapter 5 - Part 4.3: Filtering Groups with HAVING](#chapter5part4.3)
    - [Chapter 5 - Part 5: Practical Exercise: Analyzing Sales Data in the Bookstore Database](#chapter5part5)
      - [Chapter 5 - Part 5.1: Introduction to Aggregate Functions](#chapter5part5.1)
      - [Chapter 5 - Part 5.2: Grouping Data with GROUP BY](#chapter5part5.2)
      - [Chapter 5 - Part 5.3: Filtering Groups with HAVING](#chapter5part5.3)
      - [Chapter 5 - Part 5.4: Combining Aggregate Functions and Joins](#chapter5part5.4)
    - [Chapter 5 - Part 6: Aggregate function with ANY_VALUE()](#chapter5part6)
    - [Chapter 5 - Part 7: Common SQL Errors and Troubleshooting](#chapter5part7)
      - [Chapter 5 - Part 7.1: Common SQL Error Types](#chapter5part7.1)
      - [Chapter 5 - Part 7.2: Troubleshooting Techniques](#chapter5part7.2)
      - [Chapter 5 - Part 7.3: Practical Examples and Demonstrations](#chapter5part7.3)
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
30. [Appendix A: Useful DuckDB Code Snippet](#appendixa)
    - [Appendix A - Part 1: Remove characters from VARCHARS using REGEXP_REPLACE](#appendixapart1)
    - [Appendix A - Part 2: Check if a column have different values in other column](#appendixapart2)
    - [Appendix A - Part 3: Check for duplicate lines](#appendixapart3)
    - [Appendix A - Part 4: Find a character in a VARCHAR field](#appendixapart4)
    - [Appendix A - Part 5: Split a field and create new columns](#appendixapart5)
    - [Appendix A - Part 6: Split a field and aggregate values](#appendixapart6)
    - [Appendix A - Part 7: Select just even numbers](#appendixapart7)
    - [Appendix A - Part 8: Find the difference of Duplicates](#appendixapart8)
    - [Appendix A - Part 9: Find the Min and Max Length of a String and ordered alphabetically](#appendixapart9)
    - [Appendix A - Part 10: Find Cities that starts with a,e,i,o or u](#appendixapart10)
    - [Appendix A - Part 11: Find Cities that starts and ends with a,e,i,o or u with regex](#appendixapart11)
    - [Appendix A - Part 12: Find Cities that not starts and ends with a,e,i,o or u](#appendixapart12)
    - [Appendix A - Part 13: Using more than One order By](#appendixapart13)

     
<div align="center"><img src="img/example-w1054-h609.png" width=1054 height=609><br><sub>Example - (<a href='https://github.com/vitorstabile'>Work by Vitor Garcia</a>) </sub></div>

|               |                 |                 |                 |                 |                 |                 |                 |                 | 
| :-----------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
|               |                 |                 |                 |                 |                 |                 |                 |                 |
  
## <a name="chapter1"></a>Chapter 1: Introduction to Databases and SQL

#### <a name="chapter1part1"></a>Chapter 1 - Part 1: What is a Database and Why Use One?

Databases are the backbone of modern data management, enabling efficient storage, retrieval, and manipulation of information. Understanding what a database is and why we use one is fundamental to working with data in any field. This lesson will explore the core concepts of databases, their advantages, and real-world applications, setting the stage for your journey into the world of SQL.

#### <a name="chapter1part1.1"></a>Chapter 1 - Part 1.1: What is a Database?

At its core, a database is an organized collection of structured information, or data, typically stored electronically in a computer system. Databases are designed to allow efficient storage, retrieval, modification, and deletion of data, along with various data management operations. Think of it as a highly organized digital filing cabinet, far more powerful and efficient than a physical one.

**Key Characteristics of a Database**


- **Structured Data:** Data within a database is organized in a predefined format, making it easier to search, sort, and analyze. This structure is typically defined by a schema, which specifies the types of data that can be stored and the relationships between different pieces of data.

- **Persistence:** Data in a database is persistent, meaning it remains stored even when the system is powered off. This ensures that information is not lost and can be accessed whenever needed.

- **Organization:** Databases provide mechanisms for organizing data logically, such as tables, indexes, and views. This organization allows for efficient retrieval of specific data elements.

- **Data Integrity:** Databases enforce rules and constraints to ensure the accuracy and consistency of data. This includes data type validation, uniqueness constraints, and referential integrity.

- **Accessibility:** Databases provide controlled access to data, allowing authorized users and applications to retrieve and modify information while protecting it from unauthorized access.

- **Scalability:** Databases are designed to handle large volumes of data and can be scaled to accommodate growing data needs.

**Database Management Systems (DBMS)**

A Database Management System (DBMS) is the software that interacts with end-users, applications, and the database itself to capture and analyze the data. The DBMS provides the tools necessary to create, manage, and use databases. Popular DBMS examples include MySQL, PostgreSQL, Oracle, Microsoft SQL Server, and SQLite. We will be using SQLite in this course due to its ease of setup and use.

#### <a name="chapter1part1.2"></a>Chapter 1 - Part 1.2: Why Use a Database?

Databases offer numerous advantages over other methods of data storage, such as spreadsheets or simple text files. These advantages make them essential for managing data in modern applications.

**Data Integrity and Consistency**

Databases enforce rules and constraints to ensure data integrity and consistency. This means that the data stored in the database is accurate, reliable, and consistent across all applications and users.

- **Example:** In an online bookstore database, a constraint could be set to ensure that the price of a book is always a positive number. If someone tries to enter a negative price, the database will reject the entry, preventing incorrect data from being stored. Another constraint could ensure that each book has a unique ISBN.

**Data Security**

Databases provide robust security features to protect data from unauthorized access and modification. This includes user authentication, access control, and encryption.

- **Example:** In the online bookstore database, different users can be granted different levels of access. Administrators might have full access to all data, while customers might only be able to access their own order history and account information. Sensitive data, such as credit card numbers, can be encrypted to protect it from being intercepted.

**Data Sharing and Collaboration**

Databases allow multiple users and applications to access and share data simultaneously. This facilitates collaboration and ensures that everyone is working with the same, up-to-date information.

- **Example:** In the online bookstore, multiple employees can access the database at the same time to process orders, update inventory, and manage customer accounts. The database ensures that all changes are synchronized, so everyone sees the most current information.

**Data Redundancy Reduction**

Databases minimize data redundancy by storing data in a structured and organized manner. This reduces storage space and improves data consistency.

- **Example:** Instead of storing customer information multiple times in different tables (e.g., orders, shipping addresses, billing addresses), the customer information is stored once in a dedicated customer table. Other tables then reference this customer table using a unique identifier (customer ID), avoiding duplication of data.

**Efficient Data Retrieval**

Databases provide efficient mechanisms for retrieving data, such as indexing and query optimization. This allows users to quickly find the information they need, even in large datasets.

- **Example:** In the online bookstore, an index can be created on the ```book_title``` column of the ```books``` table. This allows the database to quickly find all books with a specific title, without having to scan the entire table. We will learn more about indexes in Module 7.

**Data Analysis and Reporting**

Databases provide tools for analyzing data and generating reports. This allows users to gain insights from their data and make informed decisions.

- **Example:** The online bookstore can use the database to generate reports on sales trends, popular book categories, and customer demographics. This information can be used to optimize marketing campaigns, improve inventory management, and personalize the customer experience.

#### <a name="chapter1part1.3"></a>Chapter 1 - Part 1.3: Real-World Applications

Databases are used in a wide variety of applications across many industries. Here are a few examples:

- **E-commerce:** Online stores use databases to store product information, customer data, order history, and payment details.

- **Banking:** Banks use databases to manage customer accounts, track transactions, and process loans.

- **Healthcare:** Hospitals use databases to store patient records, manage appointments, and track medical treatments.

- **Social Media:** Social media platforms use databases to store user profiles, posts, comments, and connections.

- **Education:** Universities use databases to manage student records, course information, and grades.

**Hypothetical Scenario: A Local Library**

Imagine a local library that manages its collection using a spreadsheet. As the library grows, the spreadsheet becomes increasingly difficult to manage. It's hard to find specific books, track borrowing history, and prevent data entry errors. By implementing a database, the library can:

- Easily search for books by title, author, or ISBN.
- Track which books are currently checked out and when they are due.
- Manage member information and borrowing history.
- Generate reports on popular books and borrowing trends.
- Ensure data integrity by enforcing rules such as unique ISBNs and valid due dates.

#### <a name="chapter1part2"></a>Chapter 1 - Part 2: Understanding Relational Databases and Tables

Relational databases are the foundation of modern data management. They provide a structured way to store, organize, and retrieve information, ensuring data integrity and consistency. Understanding the principles behind relational databases and how data is organized within tables is crucial for anyone working with SQL. This lesson will delve into the core concepts of relational databases, exploring the structure of tables, the importance of keys, and the relationships that can be established between tables.

#### <a name="chapter1part2.1"></a>Chapter 1 - Part 2.1: Core Principles of Relational Databases

Relational databases are based on the relational model, a theoretical framework introduced by Edgar F. Codd in 1970. This model organizes data into one or more tables (or "relations") of columns and rows, with a unique key identifying each row. The power of relational databases lies in their ability to define relationships between these tables, allowing for efficient data retrieval and manipulation.

**Tables, Rows, and Columns**

The fundamental building block of a relational database is the table. A table is a collection of related data organized in rows and columns.

- **Table:** Represents a collection of entities (e.g., customers, products, orders).
- **Row (or Record):** Represents a single instance of an entity (e.g., a specific customer, a particular product).
- **Column (or Field):** Represents an attribute of the entity (e.g., customer name, product price, order date).

**Example:**

Consider a table named ```Customers```:

| CustomerID    | FirstName       | LastName        | City            |
| :-----------: | :-------------: | :-------------: | :-------------: |
| 1             | John            | Doe             | New York        |
| 2             | Jane            | Smith           | Los Angeles     |
| 3             | David           | Lee             | Chicago         |

In this example:

- ```Customers``` is the table name.

- Each row represents a customer.

- ```CustomerID```, ```FirstName```, ```LastName```, and ```City``` are the columns representing customer attributes.

**Data Types**

Each column in a table is assigned a specific data type. The data type determines the kind of values that can be stored in that column. Common data types include:

- **INTEGER:** Whole numbers (e.g., 1, 100, -5).

- **TEXT (or VARCHAR):** Strings of characters (e.g., "John Doe", "Los Angeles").

- **REAL (or FLOAT):** Floating-point numbers (e.g., 3.14, 2.71).

- **DATE:** Dates (e.g., 2023-10-26).

- **BOOLEAN:** True/False values.

Choosing the appropriate data type for each column is crucial for data integrity and efficiency. For example, using an ```INTEGER``` data type for a ```CustomerID``` column ensures that only whole numbers can be entered, preventing errors.

**Keys: Primary and Foreign**

Keys are essential for uniquely identifying rows within a table and establishing relationships between tables. There are two main types of keys:

- **Primary Key:** A column (or a set of columns) that uniquely identifies each row in a table. A table can have only one primary key. The values in the primary key column(s) must be unique and cannot be NULL.

- **Foreign Key:** A column in one table that refers to the primary key of another table. Foreign keys establish relationships between tables.


**Example:**

Consider two tables: ```Customers``` and ```Orders```.

```Customers``` table:

| CustomerID    | FirstName       | LastName        | City            |
| :-----------: | :-------------: | :-------------: | :-------------: |
| 1             | John            | Doe             | New York        |
| 2             | Jane            | Smith           | Los Angeles     |

```Orders``` table:

| OrderID       | CustomerID      | OrderDate        | TotalAmount    |
| :-----------: | :-------------: | :-------------: | :-------------: |
| 101           | 1               | 2023-10-25      | 100.00          |
| 102           | 2               | 2023-10-26      | 50.00           |
| 103           | 1               | 2023-10-27      | 75.00           |

In this example:

- ```CustomerID``` is the primary key of the ```Customers``` table.
- ```OrderID``` is the primary key of the Orders table.
- ```CustomerID``` in the ```Orders``` table is a foreign key that references the ```CustomerID``` in the ```Customers``` table. This establishes a relationship between customers and their orders.

**Relationships Between Tables**

Relational databases allow you to define relationships between tables using primary and foreign keys. There are three main types of relationships:

- **One-to-Many:** One row in table A can be related to many rows in table B. This is the most common type of relationship. (e.g., One customer can have many orders).

- **One-to-One:** One row in table A can be related to only one row in table B, and vice versa. (e.g., One person can have only one passport).

- **Many-to-Many:** Many rows in table A can be related to many rows in table B. This type of relationship is typically implemented using a junction table (also called an associative table). (e.g., Many students can enroll in many courses, and many courses can have many students).

**Example (One-to-Many):**

As shown in the ```Customers``` and ```Orders``` example above, a customer can have multiple orders. This is a one-to-many relationship.

**Example (Many-to-Many):**

Consider two tables: ```Students``` and ```Courses```.

```Students``` table:


| StudentID     | FirstName       | LastName          |
| :-----------: | :-------------: | :-------------:   |
| 1             | Alice           | Smith             |
| 2             | Bob             | Johnson           |

```Courses``` table:

| CourseID      | CourseName      |
| :-----------: | :-------------: |
| 101           | Math            |
| 102           | Science         |

To represent the many-to-many relationship between students and courses, we need a junction table called ```StudentCourses```:

```StudentCourses``` table:


| StudentID     | CourseID        |
| :-----------: | :-------------: |
| 1             | 101             |
| 1             | 102             |
| 2             | 102             |

In this example:

- ```StudentID``` and ```CourseID``` are foreign keys in the ```StudentCourses``` table, referencing the ```Students``` and ```Courses``` tables, respectively.
- The ```StudentCourses``` table represents which students are enrolled in which courses.

#### <a name="chapter1part2.2"></a>Chapter 1 - Part 2.2: Normalization

Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity. It involves dividing large tables into smaller, more manageable tables and defining relationships between them. There are several normal forms, each with its own set of rules. The most common normal forms are:

- **First Normal Form (1NF):** Eliminates repeating groups of data. Each column should contain only atomic values (i.e., values that cannot be further subdivided).

- **Second Normal Form (2NF):** Must be in 1NF and eliminates redundant data that depends on only part of the primary key. This applies to tables with composite primary keys (i.e., primary keys consisting of multiple columns).

- **Third Normal Form (3NF):** Must be in 2NF and eliminates redundant data that depends on other non-key columns.

**Example (Normalization):**

Consider a table named ```Orders``` with the following structure:

| OrderID       | CustomerID      | CustomerName    | CustomerAddress | OrderDate       | TotalAmount     |
| :-----------: | :-------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| 101           | 1               | John Doe        | 123 Main St     | 2023-10-25      | 100.00          |
| 102           | 2               | Jane Smith      | 456 Oak Ave     | 2023-10-26      | 50.00           |

This table has redundant data: ```CustomerName``` and ```CustomerAddress``` are repeated for each order placed by the same customer. To normalize this table, we can split it into two tables: ```Customers``` and ```Orders```.

```Customers``` table:

| CustomerID      | CustomerName    | CustomerAddress |
| :-------------: | :-------------: | :-------------: |
| 1               | John Doe        | 123 Main St     |
| 2               | Jane Smith      | 456 Oak Ave     |

```Orders``` table:

| OrderID       | CustomerID      | OrderDate       | TotalAmount     |
| :-----------: | :-------------: | :-------------: | :-------------: |
| 101           | 1               | 2023-10-25      | 100.00          |
| 102           | 2               | 2023-10-26      | 50.00           |

Now, the ```CustomerName``` and ```CustomerAddress``` are stored only once in the ```Customers``` table, eliminating redundancy.

#### <a name="chapter1part2.3"></a>Chapter 1 - Part 2.3: Data Integrity

Data integrity refers to the accuracy and consistency of data stored in a database. Relational databases provide several mechanisms to ensure data integrity, including:

- **Constraints:** Rules that enforce data integrity. Common constraints include:
  - **NOT NULL:** Ensures that a column cannot contain ```NULL``` values.
  - **UNIQUE:** Ensures that all values in a column are unique.
  - **PRIMARY KEY:** Uniquely identifies each row in a table and cannot contain ```NULL``` values.
  - **FOREIGN KEY:** Enforces referential integrity, ensuring that values in a foreign key column exist in the referenced primary key column.
  - **CHECK:** Specifies a condition that must be true for all values in a column.
 
- **Transactions:** A sequence of operations that are treated as a single unit of work. If any operation in a transaction fails, the entire transaction is rolled back, ensuring that the database remains in a consistent state. (More on this in Module 4).

**Example (Constraints):**

In the ```Customers``` table, we can add constraints to ensure data integrity:

- ```CustomerID``` cannot be ```NULL``` and must be unique (PRIMARY KEY constraint).
- ```FirstName``` and ```LastName``` cannot be ```NULL``` (NOT NULL constraint).
- ```Email``` must be unique (UNIQUE constraint).
- ```Age``` must be greater than 0 (CHECK constraint).

#### <a name="chapter1part2.4"></a>Chapter 1 - Part 2.4: The "Online Bookstore" Database

Let's consider the "Online Bookstore" database introduced earlier. This database might consist of the following tables:

- ```Books```: Stores information about books (e.g., ```BookID```, ```Title```, ```Author```, ```Price```, ```ISBN```).
- ```Authors```: Stores information about authors (e.g., ```AuthorID```, ```FirstName```, ```LastName```).
- ```Customers```: Stores information about customers (e.g., ```CustomerID```, ```FirstName```, ```LastName```, ```Email```, ```Address```).
- ```Orders```: Stores information about orders (e.g., ```OrderID```, ```CustomerID```, ```OrderDate```, ```TotalAmount```).
- ```OrderItems```: Stores information about the items in each order (e.g., ```OrderItemID```, ```OrderID```, ```BookID```, ```Quantity```, ```Price```).

The relationships between these tables would be:

- One-to-Many: One author can write many books (between ```Authors``` and ```Books```).
- One-to-Many: One customer can place many orders (between ```Customers``` and ```Orders```).
- One-to-Many: One order can have many order items (between ```Orders``` and ```OrderItems```).
- One-to-Many: One book can be included in many order items (between ```Books``` and ```OrderItems```).

This database structure allows us to efficiently store and retrieve information about books, authors, customers, and orders.

#### <a name="chapter1part3"></a>Chapter 1 - Part 3: Introduction to SQL: The Language of Databases

SQL (Structured Query Language): The Language of Databases

SQL is the standard language for interacting with relational database management systems (RDBMS). It allows you to retrieve, manipulate, and manage data stored in databases. Understanding SQL is crucial for anyone working with data, from data analysts and scientists to software developers and database administrators. This lesson will provide a comprehensive introduction to SQL, covering its history, key concepts, and basic syntax. We'll explore how SQL is used to communicate with databases and perform essential operations.

#### <a name="chapter1part3.1"></a>Chapter 1 - Part 3.1: What is SQL?

SQL (Structured Query Language) is a domain-specific language used in programming and designed for managing data held in a relational database management system (RDBMS), or for stream data management system (SDS). It's the standard language for database communication.

**Key Characteristics of SQL**

- **Declarative Language:** SQL is declarative, meaning you specify what data you want, not how to retrieve it. The database system optimizes the query execution.

- **Standardized:** SQL is standardized by ANSI (American National Standards Institute) and ISO (International Organization for Standardization), ensuring a degree of portability across different database systems. However, most database systems have their own extensions to the standard.

- **Data Definition Language (DDL):** SQL includes commands for defining the database schema, such as creating, altering, and dropping tables.

- **Data Manipulation Language (DML):** SQL includes commands for manipulating data, such as inserting, updating, deleting, and retrieving data.

- **Data Control Language (DCL):** SQL includes commands for controlling access to data, such as granting and revoking permissions.

**A Brief History of SQL**

SQL was initially developed at IBM in the early 1970s by Donald D. Chamberlin and Raymond F. Boyce. It was initially called SEQUEL (Structured English Query Language). Later, the name was changed to SQL due to trademark issues.

- **1970s:** IBM developed the first prototype of SQL, called System R.

- **1980s:** SQL became a standard language for relational databases. ANSI and ISO published the first SQL standard in 1986.

- **1990s - Present:** SQL has evolved with new features and extensions, such as object-relational features, XML support, and window functions. Modern databases continue to support and extend SQL.

#### <a name="chapter1part3.2"></a>Chapter 1 - Part 3.2: SQL vs. Other Programming Languages

SQL is different from general-purpose programming languages like Python, Java, or C++.

| Feature           | SQL                                              | General-Purpose Languages (e.g., Python)     |
| :---------------: | :----------------------------------------------: | :------------------------------------------: |
| Purpose           | Managing and querying databases                  | General-purpose programming                  |
| Paradigm          | Declarative                                      | Imperative/Object-Oriented                   |
| Data Handling     | Optimized for relational data	                   | Flexible, handles various data types         |
| Execution         | Database server                                  | Application server/Interpreter               |
| Primary Use Case  | Data retrieval, manipulation, schema definition  | Application logic, system programming, etc.  |

**Example:**

Imagine you want to find all books in the "Online Bookstore" database with a price greater than $25.

- **SQL:** You would write an SQL query that specifies the condition (price > $25) and the table to search. The database system would then efficiently retrieve the matching rows.

- **Python:** You would need to connect to the database, retrieve all rows from the table, iterate through each row, and check if the price is greater than $25.

#### <a name="chapter1part3.3"></a>Chapter 1 - Part 3.3: SQL Statements and Syntax

SQL statements are instructions that you send to the database to perform specific actions. All SQL statements begin with a keyword that identifies the type of statement.

**Basic SQL Statement Structure**

Most SQL statements follow a general structure:

```sql
-- SQL statement
KEYWORD column1, column2, ...
FROM table_name
WHERE condition;
```

- **KEYWORD:** Specifies the action to be performed (e.g., ```SELECT```, ```INSERT```, ```UPDATE```, ```DELETE```).
column1, column2, ...: Specifies the columns to be affected by the statement.

- **table_name:** Specifies the table to which the statement applies.

- **WHERE condition:** Specifies a condition that filters the rows affected by the statement (optional).

**Common SQL Statements**

Here are some of the most common SQL statements:

- **SELECT:** Retrieves data from one or more tables.
- **INSERT:** Inserts new data into a table.
- **UPDATE:** Modifies existing data in a table.
- **DELETE:** Deletes data from a table.
- **CREATE TABLE:** Creates a new table in the database.
- **ALTER TABLE:** Modifies an existing table.
- **DROP TABLE:** Deletes a table from the database.

**Case Sensitivity**

SQL is generally not case-sensitive for keywords. However, it is often case-sensitive for data, depending on the database system and its configuration.

Example:

```sql
SELECT * FROM Books WHERE title = 'The Lord of the Rings'; -- Case-sensitive comparison
SELECT * FROM Books WHERE title = 'the lord of the rings'; -- May not return any results
```

**Comments**

Comments are used to add explanatory notes to your SQL code. They are ignored by the database system.

- **Single-line comments:** Use ```--``` to start a single-line comment.

- **Multi-line comments:** Use ```/*``` to start a multi-line comment and ```*/``` to end it.

Example:

```sql
-- This is a single-line comment
SELECT * FROM Books;

/*
This is a
multi-line comment
*/
SELECT * FROM Authors;
```

#### <a name="chapter1part3.4"></a>Chapter 1 - Part 3.4: Data Types in SQL

Data types specify the type of data that can be stored in a column. Choosing the correct data type is important for data integrity and efficiency.

**Common Data Types**

- **INTEGER:** Stores whole numbers (e.g., 1, 100, -50).

- **REAL/FLOAT:** Stores floating-point numbers (e.g., 3.14, 2.71).

- **TEXT/VARCHAR:** Stores strings of characters (e.g., "Hello", "SQL"). VARCHAR typically requires specifying a maximum length.

- **DATE:** Stores dates (e.g., "2023-10-27").

- **BOOLEAN:** Stores boolean values (e.g., TRUE, FALSE).

Example:

When creating the ```Books``` table in the "Online Bookstore" database, you would need to specify the data type for each column:

```sql
CREATE TABLE Books (
    book_id INTEGER PRIMARY KEY,
    title TEXT NOT NULL,
    author_id INTEGER,
    price REAL,
    publication_date DATE
);
```

In this example:

- ```book_id``` is an integer and the primary key.

- ```title``` is text and cannot be empty (```NOT NULL```).

- ```author_id``` is an integer representing the author's ID.

- ```price``` is a real number representing the book's price.

- ```publication_date``` is a date.

**Choosing the Right Data Type**

Consider the following factors when choosing a data type:

- **Type of data:** What kind of data will be stored in the column (e.g., numbers, text, dates)?

- **Range of values:** What is the minimum and maximum value that the column will store?

- **Storage space:** How much storage space is required for the data type?

- **Performance:** How will the data type affect query performance?

#### <a name="chapter1part3.5"></a>Chapter 1 - Part 3.5: SQL Operators

SQL operators are symbols or keywords used to perform operations on data.

**Types of Operators**

- **Arithmetic Operators:** Used for performing mathematical calculations (+, -, *, /).

- **Comparison Operators:** Used for comparing values (=, >, <, >=, <=, != or <>).

- **Logical Operators:** Used for combining conditions (AND, OR, NOT).

**Arithmetic Operators**

| Operator      | Description       | Example                 |
| :-----------: | :---------------: | :-------------------:   |
| +             | Addition          | ```price + 5```         |
| -             | Subtraction       | ```price - discount```  |
| *             | Multiplication    | ```price * 1.05```      |
| /             | Division          | ```price / 2```         |

**Comparison Operators**

| Operator       | Description                      | Example                               |
| :-----------:  | :------------------------------: | :-------------------:                 |
| =              | Equal to                         | ```price = 25.00```                   |
| >              | Greater than                     | ```price > 25.00```                   |
| <              | Less than                        | ```price < 25.00```                   |
| >=             | Greater than or equal to         | ```price >= 25.00```                  |
| <=             | Less than or equal to            | ```price <= 25.00```                  |
| != or <>       | Not equal to                     | ```price != 25.00```                  |
| BETWEEN        | Between a specified range        | ```price BETWEEN 20.00 AND 30.00```   |
| LIKE           | Pattern matching                 | ```title LIKE 'The%'```               |
| IN             | Equal to one of a set of values  | ```author_id IN (1, 2, 3)```          |
| IS NULL        | Equal to NULL                    | ```publication_date IS NULL```        |
| IS NOT NULL    | Not equal to NULL                | ```publication_date IS NOT NULL```    |

**Logical Operators**

| Operator       | Description                               | Example                                                 |
| :-----------:  | :---------------------------------------: | :------------------------------------:                  |
| AND            | Returns true if both conditions are true  | ```price > 20.00 AND publication_date < '2023-01-01'``` |
| OR             | Returns true if either condition is true  | ```price < 10.00 OR price > 50.00```                    |
| NOT            | Returns true if the condition is false    | ```NOT author_id = 1```                                 |

Example:

To find all books in the "Online Bookstore" database that were published after January 1, 2023, and have a price between $20 and $30, you would use the following query:

```sql
SELECT *
FROM Books
WHERE publication_date > '2023-01-01'
  AND price BETWEEN 20.00 AND 30.00;
```

#### <a name="chapter1part3.6"></a>Chapter 1 - Part 3.6: SQL Functions

SQL functions are pre-defined routines that perform specific tasks. They can be used to manipulate data, perform calculations, and format output.

**Types of Functions**

- **Aggregate Functions:** Calculate a single value from a set of values (e.g., ```COUNT```, ```SUM```, ```AVG```, ```MIN```, ```MAX```).

- **Scalar Functions:** Operate on a single value and return a single value (e.g., ```UPPER```, ```LOWER```, ```LENGTH```, ```ROUND```).

- **Date Functions:** Operate on date values (e.g., ```NOW```, ```DATE```, ```YEAR```, ```MONTH```, ```DAY```).

**Aggregate Functions**

| Operator       | Description                               | Example                                                 |
| :-----------:  | :---------------------------------------: | :------------------------------------:                  |
| COUNT          | Returns the number of rows                | ```SELECT COUNT(*) FROM Books;'```                      |
| SUM            | Returns the sum of values                 | ```SELECT SUM(price) FROM Books;```                     |
| AVG            | Returns the average of values             | ```SELECT AVG(price) FROM Books;```                     |
| MIN            | Returns the minimum value                 | ```SELECT MIN(price) FROM Books;```                     |
| MAX            | Returns the maximum value                 | ```SELECT MAX(price) FROM Books;```                     |

**Scalar Functions**

| Operator       | Description                                             | Example                                    |
| :-----------:  | :-----------------------------------------------------: | :------------------------------------:     |
| UPPER          | Converts a string to uppercase                          | ```SELECT UPPER(title) FROM Books;'```     |
| LOWER          | Converts a string to lowercase                          | ```SELECT LOWER(title) FROM Books;```      |
| LENGTH         | Returns the length of a string                          | ```SELECT LENGTH(title) FROM Books;```     |
| ROUND          | Rounds a number to a specified number of decimal places | ```SELECT ROUND(price, 2) FROM Books;```   |

**Date Functions**

| Operator       | Description                                   | Example                                                 |
| :-----------:  | :-------------------------------------------: | :------------------------------------:                  |
| NOW            | Returns the current date and time             | ```SELECT NOW();'```                                    |
| DATE           | Extracts the date part from a datetime value  | ```SELECT DATE(publication_date) FROM Books;```         |
| YEAR           | Extracts the year from a date value           | ```SELECT YEAR(publication_date) FROM Books;```         |
| MONTH          | Extracts the month from a date value          | ```SELECT MONTH(publication_date) FROM Books;```        |
| DAY            | Extracts the day from a date value            | ```SELECT DAY(publication_date) FROM Books;```          |

Example:

To find the average price of all books in the "Online Bookstore" database, you would use the following query:

```sql
SELECT AVG(price)
FROM Books;
```

To find the title of all books in uppercase, you would use the following query:

```sql
SELECT UPPER(title)
FROM Books;
```

#### <a name="chapter1part3.7"></a>Chapter 1 - Part 3.7: Different categories of SQL commands: DDL, DML, DCL, TCL, and DQL

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

Setting up your SQL environment is a crucial first step in learning how to interact with databases. It involves choosing a database management system (DBMS), installing it, and configuring it so you can start writing and executing SQL queries. This lesson will guide you through the process of setting up popular SQL environments like SQLite and MySQL, providing you with the tools you need to begin your SQL journey.

#### <a name="chapter1part4.1"></a>Chapter 1 - Part 4.1: Choosing a Database Management System (DBMS)

A Database Management System (DBMS) is software that allows you to create, manage, and access databases. Several DBMS options are available, each with its own strengths and weaknesses. For beginners, SQLite and MySQL are excellent choices.

**SQLite**

SQLite is a self-contained, serverless, zero-configuration, transactional SQL database engine. It's embedded directly into the application, meaning it doesn't require a separate server process.

- **Pros:**
  - Easy to set up: No server installation or configuration is needed.
  - Portable: The entire database is stored in a single file, making it easy to move and share.
  - Lightweight: Minimal resource usage, suitable for small to medium-sized projects.
  - Good for learning: Ideal for beginners due to its simplicity.

- **Cons:**
  - Limited concurrency: Not suitable for high-traffic, multi-user applications.
  - Fewer features: Lacks some advanced features found in more robust DBMSs like MySQL or PostgreSQL.

**MySQL**

MySQL is a popular open-source relational database management system (RDBMS). It's a client-server system, meaning it requires a separate server process to run.

- **Pros:**
  - Scalable: Can handle large databases and high traffic loads.
  - Feature-rich: Supports a wide range of SQL features and extensions.
  - Widely used: Large community and extensive documentation.
  - Suitable for web applications: Commonly used in web development.

- **Cons:**
  - More complex setup: Requires installing and configuring a server.
  - Higher resource usage: Requires more system resources than SQLite.
  - Can be overkill for small projects: Might be too complex for simple applications.

**Other DBMS Options**

While SQLite and MySQL are great starting points, other DBMS options exist, such as PostgreSQL, Microsoft SQL Server, and Oracle. These systems offer advanced features and scalability but are generally more complex to set up and manage.

#### <a name="chapter1part4.2"></a>Chapter 1 - Part 4.2: Setting Up SQLite

SQLite is incredibly easy to set up. Since it's serverless, you don't need to install a separate database server. You typically only need to install the SQLite command-line tool or a GUI-based tool.

**Installing the SQLite Command-Line Tool**

The SQLite command-line tool allows you to interact with SQLite databases from your terminal.

- **Windows:**
  - Download the precompiled binaries for Windows from the SQLite website (https://www.sqlite.org/download.html). Look for the "Precompiled Binaries for Windows" section.
  - Download the ZIP archive (e.g., ```sqlite-tools-win32-x86-3450000.zip```).
  - Extract the contents of the ZIP archive to a directory of your choice (e.g., ```C:\sqlite```).
  - Add the directory containing ```sqlite3.exe``` to your system's ```PATH``` environment variable. This allows you to run the ```sqlite3``` command from any directory in your terminal.

- **MacOS:**
  - macOS usually comes with SQLite pre-installed. You can check if it's installed by opening your terminal and running ```sqlite3 --version```.
  - If it's not installed or you want to update to the latest version, you can use a package manager like Homebrew:
  ```
  brew install sqlite
  ```

- **Linux:**
  - Most Linux distributions have SQLite available in their package repositories. You can install it using your distribution's package manager. For example, on Debian/Ubuntu:

```
sudo apt-get update

sudo apt-get install sqlite3
```

On Fedora/CentOS/RHEL:

```
sudo dnf install sqlite
```

**Using the SQLite Command-Line Tool**

- Open your terminal or command prompt.

- To create a new SQLite database, run the following command:

```
sqlite3 bookstore.db
```

This will create a new database file named ```bookstore.db``` (if it doesn't already exist) and open the SQLite command-line interface.

- You can now execute SQL commands directly in the terminal. For example, to create a table:

```sql
CREATE TABLE books (
    id INTEGER PRIMARY KEY,
    title TEXT,
    author TEXT,
    price REAL
);
```

- To exit the SQLite command-line interface, type ```.exit``` and press Enter.

**SQLite GUI Tools**

Several GUI tools are available for managing SQLite databases, providing a more user-friendly interface than the command-line tool. Some popular options include:

- **DB Browser for SQLite:** A free, open-source visual tool for creating, designing, and editing SQLite database files. It's available for Windows, macOS, and Linux.

- **SQLiteStudio:** Another free, open-source SQLite database manager with a wide range of features.

- **Dbeaver:** A universal database tool that supports SQLite and many other DBMSs. It's available in both free (Community Edition) and commercial versions.

These tools typically provide features such as:

- A visual table designer

- A SQL editor with syntax highlighting and autocompletion

- Data browsing and editing

- Import and export functionality

#### <a name="chapter1part4.3"></a>Chapter 1 - Part 4.3: Setting Up MySQL

Setting up MySQL involves installing the MySQL server, configuring it, and creating a user account to access the database.

**Installing the MySQL Server**

- **Windows:**
  - Download the MySQL Installer for Windows from the MySQL website (https://dev.mysql.com/downloads/installer/).
  - Run the installer and choose the "Server Only" or "Full" installation option. The "Full" option includes additional tools like MySQL Workbench.
  - Follow the on-screen instructions to complete the installation. You'll be prompted to set a root password during the installation process. Make sure to remember this password!
 
- **macOS:**
  - Download the DMG archive for macOS from the MySQL website (https://dev.mysql.com/downloads/mysql/).
  - Open the DMG archive and run the installer package.
  - Follow the on-screen instructions to complete the installation. You'll be prompted to set a root password during the installation process. Make sure to remember this password!
  - After installation, you might need to manually start the MySQL server from System Preferences.
 
- **Linux:**
  - The installation process varies depending on your Linux distribution.
  - **Debian/Ubuntu:**

```
sudo apt-get update
  
sudo apt-get install mysql-server
```

During the installation, you'll be prompted to set a root password.

- **Fedora/CentOS/RHEL:**

```
sudo dnf install @mysql
```

After installation, start and enable the MySQL service:

```
sudo systemctl start mysqld
sudo systemctl enable mysqld
```

You'll also need to secure the MySQL installation by running:

```
sudo mysql_secure_installation
```

This script will guide you through setting a root password, removing anonymous users, disallowing remote root login, and removing the test database.

***Connecting to the MySQL Server**

After installing the MySQL server, you can connect to it using the ```mysql``` command-line client or a GUI tool like MySQL Workbench.

**Using the mysql Command-Line Client**

- Open your terminal or command prompt.

- To connect to the MySQL server as the root user, run the following command:

```
mysql -u root -p
```

You'll be prompted to enter the root password that you set during the installation.

- Once connected, you can execute SQL commands directly in the terminal. For example, to create a new database:

```sql
CREATE DATABASE bookstore;
```

- To select the ```bookstore``` database:

```sql
USE bookstore;
```

- To create a table:

```sql
CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(255),
    author VARCHAR(255),
    price DECIMAL(10, 2)
);
```

- To exit the MySQL command-line client, type ```exit``` and press Enter.

**Using MySQL Workbench**

MySQL Workbench is a GUI tool provided by MySQL for managing MySQL servers and databases.

- Launch MySQL Workbench.
- Click the "+" button to create a new connection.
- Enter the connection details:
  - Connection Name: A name for your connection (e.g., "Local MySQL Server").
  - Hostname: ```127.0.0.1``` or ```localhost``` (if the server is running on your local machine).
  - Port: ```3306``` (the default MySQL port).
  - Username: ```root```.
  - Password: Enter the root password you set during the installation.
 
- Click "Test Connection" to verify that the connection is working.
- Click "OK" to save the connection.
- Double-click the connection to open a SQL editor and database management interface.

**Creating a New MySQL User**

It's generally not recommended to use the root user for everyday database operations. Instead, you should create a new user with limited privileges.

- Connect to the MySQL server as the root user using the mysql command-line client or MySQL Workbench.

- Execute the following SQL commands to create a new user:

```sql
CREATE USER 'bookstore_user'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON bookstore.* TO 'bookstore_user'@'localhost';
FLUSH PRIVILEGES;
```

- Replace ```'password'``` with a strong password.
- ```'bookstore_user'@'localhost'``` specifies the username and the host from which the user can connect. In this case, the user can only connect from the local machine.
- ```GRANT ALL PRIVILEGES ON bookstore.*``` grants the user all privileges on the ```bookstore``` database. You can adjust the privileges as needed.
- ```FLUSH PRIVILEGES``` reloads the grant tables, ensuring that the new privileges are applied.


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

While the command-line tools and GUI tools are useful for interacting with databases directly, you'll often want to connect to a database from a programming language like Python. This allows you to build applications that interact with and manipulate data stored in the database.

**Python and SQLite**

Python has built-in support for SQLite through the ```sqlite3``` module.

```py
import sqlite3

# Connect to the database (or create it if it doesn't exist)
conn = sqlite3.connect('bookstore.db')

# Create a cursor object to execute SQL queries
cursor = conn.cursor()

# Execute a SQL query to create a table
cursor.execute('''
    CREATE TABLE IF NOT EXISTS books (
        id INTEGER PRIMARY KEY,
        title TEXT,
        author TEXT,
        price REAL
    )
''')

# Insert some data into the table
cursor.execute("INSERT INTO books (title, author, price) VALUES ('The Lord of the Rings', 'J.R.R. Tolkien', 29.99)")

# Commit the changes
conn.commit()

# Execute a SQL query to retrieve data
cursor.execute("SELECT * FROM books")

# Fetch all the results
rows = cursor.fetchall()

# Print the results
for row in rows:
    print(row)

# Close the connection
conn.close()
```

**Python and MySQL**

To connect to a MySQL database from Python, you'll need to install a MySQL connector library, such as ```mysql-connector-python```.

```
pip install mysql-connector-python
```

```py
import mysql.connector

# Connect to the MySQL database
mydb = mysql.connector.connect(
  host="localhost",
  user="bookstore_user",
  password="password",
  database="bookstore"
)

# Create a cursor object
mycursor = mydb.cursor()

# Execute a SQL query to insert data
sql = "INSERT INTO books (title, author, price) VALUES (%s, %s, %s)"
val = ("The Hitchhiker's Guide to the Galaxy", "Douglas Adams", 12.99)
mycursor.execute(sql, val)

# Commit the changes
mydb.commit()

print(mycursor.rowcount, "record inserted.")

# Execute a SQL query to retrieve data
mycursor.execute("SELECT * FROM books")

# Fetch all the results
myresult = mycursor.fetchall()

# Print the results
for row in myresult:
  print(row)

# Close the connection
mydb.close()
```

These examples demonstrate how to connect to SQLite and MySQL databases from Python, execute SQL queries, and retrieve data. You can adapt these examples to other programming languages by using the appropriate database connector library.

**Python and PostgreSQL**

```
pip install psycopg2-binary
```

```py
import psycopg2

# Connect to the PostgreSQL database
conn = psycopg2.connect(
  host="localhost",
  user="bookstore_user",
  password="password",
  dbname="bookstore"
)

# Create a cursor object
cur = conn.cursor()

# Execute a SQL query to insert data
sql = "INSERT INTO books (title, author, price) VALUES (%s, %s, %s)"
val = ("The Hitchhiker's Guide to the Galaxy", "Douglas Adams", 12.99)
cur.execute(sql, val)

# Commit the changes
conn.commit()

print(cur.rowcount, "record inserted.")

# Execute a SQL query to retrieve data
cur.execute("SELECT * FROM books")

# Fetch all the results
rows = cur.fetchall()

# Print the results
for row in rows:
  print(row)

# Close the connection
cur.close()
conn.close()
```

**Python with DuckDB**

```
pip install duckdb
```

```py
import duckdb

# Connect to the DuckDB database (file-based or in-memory)
conn = duckdb.connect('bookstore.duckdb')

# Create the table if it doesn't exist
conn.execute('''
CREATE TABLE IF NOT EXISTS books (
    title TEXT,
    author TEXT,
    price DOUBLE
)
''')

# Insert data into the table
sql = "INSERT INTO books (title, author, price) VALUES (?, ?, ?)"
val = ("The Hitchhiker's Guide to the Galaxy", "Douglas Adams", 12.99)
conn.execute(sql, val)

print("1 record inserted.")

# Query data from the table
result = conn.execute("SELECT * FROM books").fetchall()

# Print the results
for row in result:
    print(row)

# Close the connection
conn.close()
```

#### <a name="chapter1part5"></a>Chapter 1 - Part 5: Connecting to a Database and Running Basic Commands

Connecting to a database is the crucial first step in interacting with and manipulating data using SQL. This lesson will guide you through the process of establishing a connection to a database using various tools and methods, and then executing basic SQL commands to verify the connection and retrieve initial information. We'll cover essential concepts like database drivers, connection strings, and basic SQL syntax, providing you with the foundational knowledge to begin your SQL journey.

#### <a name="chapter1part5.1"></a>Chapter 1 - Part 5.1: Establishing a Database Connection

Connecting to a database involves several key components: the database management system (DBMS), the client tool or application, and the necessary connection parameters. The process generally involves the following steps:

- **Choosing a Database Client:** Select a tool or application that allows you to connect to and interact with your chosen DBMS. Examples include command-line tools (like ```sqlite3``` for SQLite or ```mysql``` for MySQL), GUI-based tools (like Dbeaver, MySQL Workbench, or pgAdmin), or programming language libraries (like ```sqlite3``` in Python or JDBC in Java).

- **Installing the Necessary Drivers:** Database drivers are software components that enable communication between the client tool and the DBMS. These drivers are specific to the DBMS you are using (e.g., the ```psycopg2``` library for PostgreSQL or the ```mysql-connector-python``` library for MySQL).

- **Constructing the Connection String:** The connection string contains the information needed to locate and authenticate with the database server. This typically includes the server address, port number, database name, username, and password.

- **Establishing the Connection:** Use the client tool or application to establish a connection to the database using the connection string.

- **Verifying the Connection:** Once connected, execute a simple SQL command to verify that the connection is working correctly.

**Database Drivers**

Database drivers act as translators between your application and the database server. They handle the low-level communication protocols and data formatting required for the specific DBMS. Without the correct driver, your application will not be able to connect to the database.

Example:

Imagine you're trying to communicate with someone who only speaks Spanish, and you only speak English. A translator (the database driver) is needed to facilitate the conversation. The translator understands both languages and can convert your English requests into Spanish and vice versa.

Hypothetical Scenario:

A software development company is building a web application that needs to store user data in a PostgreSQL database. The developers choose Python as their programming language. To connect the Python application to the PostgreSQL database, they need to install the psycopg2 driver. This driver allows the Python code to send SQL queries to the PostgreSQL server and receive the results.

**Connection Strings**

A connection string is a string of characters that provides all the necessary information to connect to a database. The format of the connection string varies depending on the DBMS and the client tool being used.

Common elements in a connection string include:

- **Server Address:** The hostname or IP address of the database server.

- **Port Number:** The port number on which the database server is listening for connections (e.g., 3306 for MySQL, 5432 for PostgreSQL).

- **Database Name:** The name of the database to connect to.

- **Username:** The username to use for authentication. 

- **Password:** The password for the specified username.

Example:

A connection string for connecting to a MySQL database using Python might look like this:

```py
import mysql.connector

mydb = mysql.connector.connect(
  host="localhost",
  user="yourusername",
  password="yourpassword",
  database="mydatabase"
)

print(mydb)
```

In this example:

- ```host="localhost"``` specifies that the database server is running on the same machine as the Python script.
- ```user="yourusername"``` specifies the username to use for authentication.
- ```password="yourpassword"``` specifies the password for the user.
- ```database="mydatabase"``` specifies the name of the database to connect to.

Hypothetical Scenario:

A data analyst needs to connect to a SQL Server database hosted on a remote server to extract sales data for a report. They use Microsoft Excel's "Get Data" feature, which requires a connection string. The analyst constructs the following connection string:

```
Driver={SQL Server};Server=sqlserver.example.com;Database=SalesData;Uid=analyst;Pwd=securepassword;
```

This connection string tells Excel to use the SQL Server driver, connect to the server at ```sqlserver.example.com```, access the ```SalesData``` database, and authenticate using the username "analyst" and the password "securepassword".

#### <a name="chapter1part6"></a>Chapter 1 - Part 6: Case Study Introduction: The "Online Bookstore" Database

The "Online Bookstore" database will serve as a practical, real-world example throughout this course. By using a consistent case study, you'll be able to apply the SQL concepts you learn in each module to a familiar scenario, reinforcing your understanding and making the learning process more engaging. This lesson introduces the structure and purpose of this database, setting the stage for hands-on exercises in subsequent modules.

#### <a name="chapter1part6.1"></a>Chapter 1 - Part 6.1: Introducing the Online Bookstore Database

The Online Bookstore database is designed to store information about books, authors, customers, orders, and other relevant data for an online bookstore. It's a relational database, meaning data is organized into tables with relationships between them. This structure allows us to efficiently store, retrieve, and manipulate data using SQL.

**Key Tables in the Database**

Here's an overview of the main tables you'll be working with:

- **Books:** This table stores information about each book, such as its title, ISBN, publication date, price, and author.
- **Authors:** This table stores information about the authors, such as their name, biography, and contact information.
- **Customers:** This table stores information about the bookstore's customers, such as their name, address, email, and phone number.
- **Orders:** This table stores information about customer orders, such as the order date, customer ID, and total amount.
- **Order_Items:** This table stores the individual items included in each order, linking orders to specific books and quantities.

**Relationships Between Tables**

The tables in the database are related to each other through primary and foreign keys. Understanding these relationships is crucial for querying data across multiple tables, which you'll learn about in Module 3.

- **One-to-Many Relationship between Authors and Books:** One author can write multiple books. The ```Books``` table will have a foreign key referencing the ```Authors``` table (typically ```author_id```).

- **One-to-Many Relationship between Customers and Orders:** One customer can place multiple orders. The ```Orders``` table will have a foreign key referencing the ```Customers``` table (typically ```customer_id```).

- **Many-to-Many Relationship between Orders and Books:** One order can contain multiple books, and one book can be included in multiple orders. This relationship is implemented using the ```Order_Items``` table, which acts as a linking table between ```Orders``` and ```Books```. It contains foreign keys referencing both tables (```order_id``` and ```book_id```).

#### <a name="chapter1part6.2"></a>Chapter 1 - Part 6.2: Detailed Table Schemas

Let's examine the structure of each table in more detail, including the columns and data types they contain. This will give you a clear understanding of the data you'll be working with.

**Books Table**

| Column Name         | Data Type           | Description                                        | Example Value           |
| :-----------------: | :-----------------: | :------------------------------------------------: | :---------------------: |
| book_id             | INTEGER             | Primary key, unique identifier for each book       | 1                       |
| isbn                | VARCHAR(20)         | International Standard Book Number                 | 978-0321765723          |
| title               | VARCHAR(255)        | Title of the book                                  | The Lord of the Rings   |
| author_id           | INTEGER             | Foreign key referencing the Authors table          | 12                      |
| publication_date    | DATE                | Date the book was published                        | 2023-03-15              |
| price               | DECIMAL(10, 2)      | Price of the book                                  | 29.99                   |
| genre               | VARCHAR(50)         | Genre of the book                                  | Fantasy                 |

**Authors Table**

| Column Name         | Data Type      | Description       | Example Value     |
| :-----------------: | :-------------: | :-------------: | :-------------: |
| author_id             | INTEGER               | Primary key, unique identifier for each author      | 12          |
| first_name                | VARCHAR(100)               | First name of the author      | J.R.R.           |
| last_name               | VARCHAR(100)               | Last name of the author      | Tolkien          |
| biography           | TEXT               | Short biography of the author      | British author and philologist           |
| publisher    | VARCHAR(100)               | Author's publisher      | Allen & Unwin          |

**Customers Table**

| Column Name         | Data Type      | Description       | Example Value     |
| :-----------------: | :-------------: | :-------------: | :-------------: |
| customer_id             | INTEGER               | Primary key, unique identifier for each customer      | 101          |
| first_name                | VARCHAR(100)               | First name of the customer      | Alice           |
| last_name               | VARCHAR(100)               | Last name of the customer      | Smith          |
| email           | VARCHAR(255)                | Email address of the customer	      | alice.smith@example.com           |
| phone_number    | VARCHAR(20)               | Phone number of the customer      | 555-123-4567          |
| shipping_address    | VARCHAR(255)               | Shipping address of the customer      | 123 Main St, Anytown, USA          |

**Orders Table**

| Column Name         | Data Type      | Description       | Example Value     |
| :-----------------: | :-------------: | :-------------: | :-------------: |
| order_id             | INTEGER               | Primary key, unique identifier for each order      | 201          |
| customer_id                | INTEGER               | Foreign key referencing the Customers table      | 101           |
| order_date               | DATE               | Date the order was placed      | 2024-01-20          |
| total_amount           | DECIMAL(10, 2)                | Total amount of the order	      | 59.98           |
| shipping_address    | VARCHAR(255)               | Shipping address for the order      | 123 Main St, Anytown, USA          |
| order_status    | VARCHAR(50)               | Status of the order      | Shipped          |

**Order_Items Table**

| Column Name         | Data Type      | Description       | Example Value     |
| :-----------------: | :-------------: | :-------------: | :-------------: |
| order_item_id             | INTEGER               | Primary key, unique identifier for each order item      | 301          |
| order_id                | INTEGER               | Foreign key referencing the Orders table      | 201           |
| book_id               | INTEGER               | Foreign key referencing the Books table      | 1          |
| quantity           | INTEGER                | Quantity of the book in the order	      | 2           |
| price    | DECIMAL(10, 2)               | Price of the book at the time of the order      | 29.99          |

#### <a name="chapter1part6.3"></a>Chapter 1 - Part 6.3: Example Scenarios and Queries

To illustrate how this database can be used, let's consider a few example scenarios and the types of queries you might run to retrieve information. Note that the actual SQL syntax will be covered in later modules.

- **Scenario 1: Finding all books by a specific author.** You would query the ```Books``` table, filtering by the ```author_id``` to match the author you're interested in.

- **Scenario 2: Finding all orders placed by a specific customer.** You would query the ```Orders``` table, filtering by the ```customer_id```.

- **Scenario 3: Finding the books included in a specific order.** You would query the ```Order_Items``` table, filtering by the ```order_id```, and then use the ```book_id``` to retrieve the book details from the ```Books``` table.

- **Scenario 4: Calculating the total revenue generated by a specific book.** You would query the ```Order_Items``` table, filtering by the ```book_id```, and then sum the ```price``` multiplied by the ```quantity``` for each order item.

These are just a few examples of the types of queries you can run against the Online Bookstore database. As you progress through the course, you'll learn how to write the SQL code to perform these and many other more complex queries.

## <a name="chapter2"></a>Chapter 2: Retriving Data with SELECT Statements

#### <a name="chapter2part1"></a>Chapter 2 - Part 1: Basic SELECT Statements: Choosing Columns

The ```SELECT``` statement is the foundation of data retrieval in SQL. It allows you to specify which columns you want to see in your results, providing a way to focus on the specific information you need from your database tables. Mastering the art of choosing the right columns is crucial for efficient data analysis and reporting. This lesson will cover the fundamental syntax of the ```SELECT``` statement, how to select specific columns, and how to retrieve all columns using the asterisk (*) wildcard. We'll also explore practical examples using our online bookstore database.

#### <a name="chapter2part1.1"></a>Chapter 2 - Part 1.1: Basic Syntax of the SELECT Statement

The ```SELECT``` statement is used to retrieve data from one or more tables in a database. The basic syntax is as follows:

```sql
SELECT column1, column2, ...
FROM table_name;
```

- ```SELECT```: This keyword indicates that you want to retrieve data.

- ```column1, column2, ...```: This is a comma-separated list of the columns you want to retrieve.

- ```FROM```: This keyword specifies the table from which you want to retrieve the data.

- ```table_name```: This is the name of the table.

For example, to retrieve the ```title``` and ```author``` columns from the books table in our online bookstore database, you would use the following statement:

```sql
SELECT title, author
FROM books;
```

This query will return a result set containing only the ```title``` and ```author``` columns for all rows in the ```books``` table.

#### <a name="chapter2part1.2"></a>Chapter 2 - Part 1.2: Selecting Specific Columns

The power of the SELECT statement lies in its ability to retrieve only the columns you need. This is important for several reasons:

- **Efficiency**: Retrieving only the necessary columns reduces the amount of data transferred from the database server to your application, improving performance.

- **Readability**: Selecting specific columns makes the result set easier to understand and work with.

- **Security**: You can restrict access to sensitive data by only selecting the columns that a user is authorized to view.

Let's consider our online bookstore database. Suppose you want to retrieve the ```title```, ```author```, and ```price``` of all books. You would use the following query:

```sql
SELECT title, author, price
FROM books;
```

This query will return a result set with three columns: ```title```, ```author```, and ```price```. Each row in the result set will represent a book, with its corresponding title, author, and price.

**Example**:

Assume the books table has the following data:

| book_id       | title                     | author            | price           | genre        |
| :-----------: | :-----------------------: | :---------------: | :-------------: | :----------: |
| 1             | The Lord of the Rings     | J.R.R. Tolkien    | 25.00           | Fantasy      |
| 2             | Pride and Prejudice       | Jane Austen       | 12.50           | Romance      |
| 3             | 1984                      | George Orwell     | 18.00           | Dystopian    |
| 4             | The Hitchhiker's Guide... | Douglas Adams     | 15.00           | Science Fic  |

The query ```SELECT title, author, price FROM books;``` would return:

| title                     | author            | price           |
| :-----------------------: | :---------------: | :-------------: |
| The Lord of the Rings     | J.R.R. Tolkien    | 25.00           |
| Pride and Prejudice       | Jane Austen       | 12.50           |
| 1984                      | George Orwell     | 18.00           |
| The Hitchhiker's Guide... | Douglas Adams     | 15.00           |

#### <a name="chapter2part1.3"></a>Chapter 2 - Part 1.3: Selecting All Columns Using the Asterisk (*) Wildcard

In some cases, you may want to retrieve all columns from a table. You can do this using the asterisk (*) wildcard. The syntax is as follows:

```sql
SELECT *
FROM table_name;
```

The asterisk (*) represents all columns in the table. For example, to retrieve all columns from the ```books``` table, you would use the following statement:

```sql
SELECT *
FROM books;
```

This query will return a result set containing all columns in the ```books``` table, in the order they are defined in the table schema.

Caution: While using ```SELECT *``` is convenient, it's generally recommended to explicitly list the columns you need. This is because:

- It's more efficient, as the database doesn't have to retrieve unnecessary data.

- It makes your queries more readable and easier to understand.

- It protects your application from unexpected changes to the table schema. If a new column is added to the table, ```SELECT *``` will automatically include it in the result set, which may break your application if it's not expecting that column.

**Example:**

Using the same ```books``` table data as before, the query ```SELECT * FROM books;``` would return:

| book_id       | title                     | author            | price           | genre        |
| :-----------: | :-----------------------: | :---------------: | :-------------: | :----------: |
| 1             | The Lord of the Rings     | J.R.R. Tolkien    | 25.00           | Fantasy      |
| 2             | Pride and Prejudice       | Jane Austen       | 12.50           | Romance      |
| 3             | 1984                      | George Orwell     | 18.00           | Dystopian    |
| 4             | The Hitchhiker's Guide... | Douglas Adams     | 15.00           | Science Fic  |

#### <a name="chapter2part1.4"></a>Chapter 2 - Part 1.4: Column Order in the SELECT Statement

The order in which you list the columns in the ```SELECT``` statement determines the order in which they appear in the result set. For example, the following two queries will return the same data, but in different column orders:

```sql
SELECT author, title
FROM books;

SELECT title, author
FROM books;
```

The first query will return a result set with the ```author``` column first, followed by the ```title``` column. The second query will return a result set with the ```title``` column first, followed by the ```author``` column.

This can be useful for presenting data in a specific order that is more readable or easier to work with.

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

The ```WHERE``` clause is the cornerstone of targeted data retrieval in SQL. It allows you to specify conditions that filter rows from a table, ensuring you only get the data you need. Without the ```WHERE``` clause, your ```SELECT``` statements would return every single row in a table, which is often inefficient and impractical. This lesson will delve into the syntax, operators, and best practices for using ```WHERE``` clauses effectively.

#### <a name="chapter2part2.1"></a>Chapter 2 - Part 2.1: Understanding the WHERE Clause

The ```WHERE``` clause is used to filter records based on specified conditions. It's placed after the ```FROM``` clause in a ```SELECT``` statement. The basic syntax is as follows:

```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```

The ```condition``` is a Boolean expression that evaluates to either TRUE, FALSE, or UNKNOWN (NULL). Only rows for which the condition evaluates to TRUE are included in the result set.

**Basic Example**

Let's revisit our "Online Bookstore" database. Suppose we want to find all books with a price greater than $25. We can use the following query:

```sql
SELECT title, price
FROM books
WHERE price > 25;
```

This query will return only the title and price of books where the price column is greater than 25.

#### <a name="chapter2part2.2"></a>Chapter 2 - Part 2.2: Comparison Operators

Comparison operators are fundamental to constructing conditions in the ```WHERE``` clause. Here's a breakdown of common comparison operators:

- ```=```: Equal to
- ```>```: Greater than
- ```<```: Less than
- ```>=```: Greater than or equal to
- ```<=```: Less than or equal to
- ```<> or !=```: Not equal to

**Examples Using Comparison Operators**

- **Equal To (=)**: Find all books with the author "Jane Austen":

```sql
SELECT title, author
FROM books
WHERE author = 'Jane Austen';
```

- **Greater Than (>)**: Find all books published after the year 2010:

```sql
SELECT title, publication_year
FROM books
WHERE publication_year > 2010;
```

- **Less Than (<)**: Find all books with a rating less than 4:

```sql
SELECT title, rating
FROM books
WHERE rating < 4;
```

- **Greater Than or Equal To (>=)**: Find all books with a price of $20 or more:

```sql
SELECT title, price
FROM books
WHERE price >= 20;
```

- **Less Than or Equal To (<=)**: Find all books with a rating of 3.5 or less:

```sql
SELECT title, rating
FROM books
WHERE rating <= 3.5;
```

- **Not Equal To (<> or !=)**: Find all books that are not written by "Jane Austen":

```sql
SELECT title, author
FROM books
WHERE author <> 'Jane Austen'; -- Or WHERE author != 'Jane Austen';
```

#### <a name="chapter2part2.3"></a>Chapter 2 - Part 2.3: Logical Operators

Logical operators allow you to combine multiple conditions in a ```WHERE``` clause. The primary logical operators are ```AND```, ```OR```, and ```NOT```.

- ```AND```: Returns TRUE if both conditions are TRUE.

- ```OR```: Returns TRUE if at least one condition is TRUE.

- ```NOT```: Negates a condition.

**Examples Using Logical Operators**

- **AND**: Find all books written by "Jane Austen" published after 1815:

```sql
SELECT title, author, publication_year
FROM books
WHERE author = 'Jane Austen' AND publication_year > 1815;
```

- **OR**: Find all books written by "Jane Austen" or with a price greater than $30:

```sql
SELECT title, author, price
FROM books
WHERE author = 'Jane Austen' OR price > 30;
```

- **NOT**: Find all books that are not in the "Fiction" genre:

```sql
SELECT title, genre
FROM books
WHERE NOT genre = 'Fiction';
```

**Combining Logical Operators**

You can combine multiple logical operators to create complex conditions. Use parentheses to control the order of evaluation.

Example: Find all books that are either (written by "Jane Austen" and published after 1815) or have a rating greater than 4.5:

```sql
SELECT title, author, publication_year, rating
FROM books
WHERE (author = 'Jane Austen' AND publication_year > 1815) OR rating > 4.5;
```

Without parentheses, the ```AND``` operator would be evaluated before the ```OR``` operator, leading to a different result.

#### <a name="chapter2part2.4"></a>Chapter 2 - Part 2.4: Special Operators

SQL provides several special operators that simplify common filtering tasks.

**BETWEEN**

The ```BETWEEN``` operator is used to select values within a given range. The syntax is:

```sql
SELECT column1, column2, ...
FROM table_name
WHERE column_name BETWEEN value1 AND value2;
```

This is equivalent to ```column_name >= value1 AND column_name <= value2```.

Example: Find all books published between 2000 and 2010 (inclusive):

```sql
SELECT title, publication_year
FROM books
WHERE publication_year BETWEEN 2000 AND 2010;
```

**LIKE**

The ```LIKE``` operator is used for pattern matching. It's often used with wildcard characters:

- ```%```: Represents zero or more characters.

- ```_```: Represents a single character.

Example: Find all books with titles starting with "The":

```sql
SELECT title
FROM books
WHERE title LIKE 'The%';
```

Example: Find all books with an author whose last name is five characters long and starts with "S":

```sql
SELECT title, author
FROM books
WHERE author LIKE 'S____';
```

**IN**

The ```IN``` operator allows you to specify a list of values to match. The syntax is:

```sql
SELECT column1, column2, ...
FROM table_name
WHERE column_name IN (value1, value2, value3, ...);
```

This is equivalent to ```column_name = value1 OR column_name = value2 OR column_name = value3 ....```

Example: Find all books in the "Fiction", "Mystery", or "Thriller" genres:

```sql
SELECT title, genre
FROM books
WHERE genre IN ('Fiction', 'Mystery', 'Thriller');
```

**IS NULL**

The ```IS NULL``` operator is used to check for NULL values. You cannot use ```=``` to compare a column to NULL.

Example: Find all books where the rating is NULL:

```sql
SELECT title, rating
FROM books
WHERE rating IS NULL;
```

**IS NOT NULL**

The ```IS NOT NULL``` operator is used to check for non-NULL values.

Example: Find all books where the rating is not NULL:

```sql
SELECT title, rating
FROM books
WHERE rating IS NOT NULL;
```

#### <a name="chapter2part2.5"></a>Chapter 2 - Part 2.5: Operator Precedence

When combining multiple operators in a WHERE clause, it's important to understand operator precedence. SQL evaluates operators in the following order (highest to lowest):

- Parentheses ```()```

- ```NOT```

- ```AND```

- ```OR```

Use parentheses to explicitly control the order of evaluation and avoid ambiguity.

#### <a name="chapter2part2.6"></a>Chapter 2 - Part 2.6: Case Sensitivity

The case sensitivity of comparisons in the WHERE clause depends on the database system and the column's collation. Some databases are case-sensitive by default, while others are not.

- **Case-Sensitive**: In a case-sensitive database, ```'Jane Austen'``` is different from ```'jane austen'```.

- **Case-Insensitive**: In a case-insensitive database, ```'Jane Austen'``` is treated the same as ```'jane austen'```.

If you need to perform a case-insensitive comparison in a case-sensitive database, you can use functions like ```LOWER()``` or ```UPPER()``` to convert both the column value and the comparison value to the same case.

Example (for case-insensitive comparison):

```sql
SELECT title, author
FROM books
WHERE LOWER(author) = LOWER('Jane Austen');
```

#### <a name="chapter2part2.7"></a>Chapter 2 - Part 2.7: Case() Functions

The way to implement the if-then-else logic in SQL. This function sequentially checks the provided conditions in the WHEN clauses and returns the value from the corresponding THEN clause when the first condition is satisfied. If none of the conditions is satisfied, the function returns the value from the ELSE clause in case it's provided, otherwise, it returns NULL. The syntax is:

```sql
CASE
    WHEN condition_1 THEN value_1
    WHEN condition_2 THEN value_2
    WHEN condition_3 THEN value_3
    ...
    ELSE value
END;
```

#### <a name="chapter2part2.8"></a>Chapter 2 - Part 2.8: Performance Considerations

Using the ```WHERE``` clause effectively is crucial for query performance. Here are some tips:

- **Use Indexes**: Ensure that columns used in ```WHERE``` clause conditions are indexed. Indexes can significantly speed up query execution. We will cover indexes in more detail in Module 7.

- **Avoid Functions in WHERE Clause**: Using functions in the ```WHERE``` clause can prevent the database from using indexes. For example, ```WHERE YEAR(date_column) = 2023``` is less efficient than ```WHERE date_column BETWEEN '2023-01-01' AND '2023-12-31'```.

- **Optimize Complex Conditions**: Break down complex conditions into simpler ones, and use parentheses to control the order of evaluation.

- **Use the Most Selective Conditions First**: Place the most selective conditions (those that filter out the most rows) earlier in the ```WHERE``` clause.

#### <a name="chapter2part3"></a>Chapter 2 - Part 3: Sorting Data with ORDER BY: Ascending and Descending

Sorting data is a crucial aspect of database management, allowing you to present information in a meaningful and easily understandable way. The ```ORDER BY``` clause in SQL provides the functionality to sort the result set of a query based on one or more columns, either in ascending or descending order. This capability is essential for generating reports, analyzing data trends, and providing users with a customized view of the information stored in the database.

#### <a name="chapter2part3.1"></a>Chapter 2 - Part 3.1: Understanding the ORDER BY Clause

The ```ORDER BY``` clause is used to sort the rows in a result set. By default, ```ORDER BY``` sorts the data in ascending order. You can explicitly specify the sorting order using the ```ASC``` keyword for ascending or the ```DESC``` keyword for descending.

**Basic Syntax**

The basic syntax of the ```ORDER BY``` clause is as follows:

```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1 [ASC | DESC], column2 [ASC | DESC], ...;
```

- ```SELECT column1, column2, ...```: Specifies the columns you want to retrieve.

- ```FROM table_name```: Specifies the table from which you want to retrieve the data.

- ```ORDER BY column1, column2, ...```: Specifies the columns by which you want to sort the result set. You can specify multiple columns, and the sorting will be performed based on the order in which the columns are listed.

- ```ASC```: Specifies that the sorting should be in ascending order (default).

- ```DESC```: Specifies that the sorting should be in descending order.

**Sorting by a Single Column**

Let's start with a simple example using our "Online Bookstore" database. Suppose we want to retrieve all books from the ```books``` table and sort them by their ```title``` in ascending order.

```sql
SELECT book_id, title, author, price
FROM books
ORDER BY title ASC;
```

This query will return all columns (```book_id```, ```title```, ```author```, and ```price```) from the ```books``` table, sorted alphabetically by the ```title``` column. The ASC keyword is optional here because ascending order is the default.

Now, let's sort the books by their ```price``` in descending order.

```sql
SELECT book_id, title, author, price
FROM books
ORDER BY price DESC;
```

This query will return the books sorted from the most expensive to the least expensive.

**Sorting by Multiple Columns**

You can also sort the result set by multiple columns. The sorting is performed based on the order in which the columns are listed in the ```ORDER BY``` clause. For example, if you want to sort the books first by ```author``` in ascending order and then by ```price``` in descending order within each author, you can use the following query:

```sql
SELECT book_id, title, author, price
FROM books
ORDER BY author ASC, price DESC;
```

In this case, the database will first sort the books alphabetically by the ```author``` column. Then, for each author, it will sort the books by ```price``` in descending order. This is useful when you want to group data by one column and then sort it within each group by another column.

**Case Sensitivity**

The case sensitivity of the ```ORDER BY``` clause depends on the database system and its configuration. Some database systems are case-insensitive by default, while others are case-sensitive.

- **Case-Insensitive**: In a case-insensitive system (e.g., SQLite by default), sorting by ```title``` would treat "The Lord of the Rings" and "the lord of the rings" as the same.

- **Case-Sensitive**: In a case-sensitive system (e.g., some configurations of MySQL or PostgreSQL), "The Lord of the Rings" would be sorted differently from "the lord of the rings".

If you need to ensure case-insensitive sorting in a case-sensitive database, you can use functions like ```LOWER()``` or ```UPPER()``` to convert the column to a consistent case before sorting. For example:

```sql
SELECT book_id, title, author
FROM books
ORDER BY LOWER(title) ASC;
```

This query converts the ```title``` column to lowercase before sorting, ensuring that the sorting is case-insensitive.

**Sorting by Expressions**

You can also use expressions in the ```ORDER BY``` clause. For example, you might want to sort books based on a calculated value, such as the discounted price. Suppose you have a ```discount``` column in the ```books``` table. You can sort the books by their discounted price using the following query:

```sql
SELECT book_id, title, price, discount, (price * (1 - discount)) AS discounted_price
FROM books
ORDER BY (price * (1 - discount)) DESC;
```

This query calculates the discounted price for each book and then sorts the result set by the calculated ```discounted_price``` in descending order. Note that you can directly use the expression in the ```ORDER BY``` clause without needing to use the alias ```discounted_price```. However, using an alias in the ```SELECT``` statement makes the query more readable.

**NULL Values in Sorting**

When sorting data, it's important to consider how ```NULL``` values are handled. Different database systems may handle ```NULL``` values differently in the ```ORDER BY``` clause.

- In some systems, ```NULL``` values are treated as the lowest possible value, so they appear at the beginning of the sorted result set when sorting in ascending order.

- In other systems, ```NULL``` values are treated as the highest possible value, so they appear at the end of the sorted result set when sorting in ascending order.

To explicitly control the placement of ```NULL``` values, some database systems provide extensions to the ```ORDER BY``` clause, such as ```NULLS FIRST``` or ```NULLS LAST```. For example, in PostgreSQL:

```sql
SELECT book_id, title, author, price
FROM books
ORDER BY price DESC NULLS LAST;
```

This query sorts the books by ```price``` in descending order, with ```NULL``` values appearing at the end of the result set.

#### <a name="chapter2part3.2"></a>Chapter 2 - Part 3.2: Practical Examples and Demonstrations

Let's consider some more practical examples using the "Online Bookstore" database.

- **Sorting Customers by Registration Date**: Suppose you want to retrieve a list of customers from the customers table, sorted by their registration date in descending order (i.e., the most recently registered customers first).

```sql
SELECT customer_id, first_name, last_name, email, registration_date
FROM customers
ORDER BY registration_date DESC;
```

- **Sorting Orders by Total Amount**: Suppose you want to retrieve a list of orders from the orders table, sorted by their total amount in descending order. Assume you have a total_amount column in the orders table.

```sql
SELECT order_id, customer_id, order_date, total_amount
FROM orders
ORDER BY total_amount DESC;
```

- **Sorting Books by Author and Title**: Suppose you want to retrieve a list of books, sorted first by author in ascending order and then by title in ascending order within each author.

```sql
SELECT book_id, title, author, price
FROM books
ORDER BY author ASC, title ASC;
```

- **Sorting Reviews by Rating and Date**: Suppose you want to retrieve a list of reviews from a reviews table, sorted first by rating in descending order (highest rating first) and then by review date in descending order (most recent review first) within each rating.

```sql
SELECT review_id, book_id, customer_id, rating, review_date, comment
FROM reviews
ORDER BY rating DESC, review_date DESC;
```

#### <a name="chapter2part4"></a>Chapter 2 - Part 4: Limiting Results with LIMIT: Retrieving Top N Rows

The ability to limit the number of rows returned by a SQL query is a fundamental skill for database management. The ```LIMIT``` clause allows you to control the size of your result sets, which is crucial for performance, especially when dealing with large tables. It's also essential for tasks like pagination, retrieving top N records, and sampling data. Understanding how to use ```LIMIT``` effectively will enable you to write more efficient and targeted queries.

#### <a name="chapter2part4.1"></a>Chapter 2 - Part 4.1: Understanding the LIMIT Clause

The ```LIMIT``` clause in SQL is used to restrict the number of rows returned by a ```SELECT``` statement. It's typically placed at the end of the query, after any ```WHERE``` or ```ORDER BY``` clauses. The basic syntax is:

```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition
ORDER BY column1
LIMIT number_of_rows;
```

- ```SELECT column1, column2, ...```: Specifies the columns you want to retrieve.

- ```FROM table_name```: Specifies the table you want to retrieve data from.

- ```WHERE condition``` (optional): Filters the rows based on a specified condition.

- ```ORDER BY column1``` (optional): Sorts the rows based on a specified column.

- ```LIMIT number_of_rows```: Specifies the maximum number of rows to return.

**Basic Usage**

The simplest use of ```LIMIT``` is to specify the maximum number of rows you want to retrieve. For example, to retrieve the first 5 books from the ```books``` table in our online bookstore database, you would use the following query:

```sql
SELECT book_id, title, price
FROM books
LIMIT 5;
```

This query will return a maximum of 5 rows from the ```books``` table, regardless of how many rows the table actually contains. The order in which the rows are returned is not guaranteed unless you use an ```ORDER BY``` clause.

**Using LIMIT with ORDER BY**

To retrieve the "top N" records based on a specific criteria, you typically combine ```LIMIT``` with ```ORDER BY```. For example, to retrieve the 3 most expensive books from the ```books``` table, you would use the following query:

```sql
SELECT book_id, title, price
FROM books
ORDER BY price DESC
LIMIT 3;
```

In this query:

- ```ORDER BY price DESC``` sorts the books in descending order of price, so the most expensive books come first.

- ```LIMIT 3``` then restricts the result set to the first 3 rows, which are the 3 most expensive books.

**Using LIMIT with an Offset**

The ```LIMIT``` clause can also be used with an offset to retrieve a specific range of rows. The offset specifies the starting row (0-based index) from which to begin retrieving rows. The syntax is:

```sql
SELECT column1, column2, ...
FROM table_name
LIMIT number_of_rows OFFSET offset_value;
```

Alternatively, some SQL dialects support a more concise syntax:

```sql
SELECT column1, column2, ...
FROM table_name
LIMIT offset_value, number_of_rows;
```

- ```offset_value```: The number of rows to skip before starting to return rows.

- ```number_of_rows```: The maximum number of rows to return.

For example, to retrieve rows 6 through 10 from the ```books``` table (assuming the rows are ordered in some way, such as by ```book_id```), you would use the following query:

```sql
SELECT book_id, title, price
FROM books
ORDER BY book_id
LIMIT 5 OFFSET 5;
```

Or, using the alternative syntax:

```sql
SELECT book_id, title, price
FROM books
ORDER BY book_id
LIMIT 5, 5;
```

This query skips the first 5 rows and then returns the next 5 rows, effectively retrieving rows 6 through 10. This is commonly used for pagination in web applications.

**Practical Examples**

Let's consider some more practical examples using our online bookstore database.

- **Retrieve the 5 newest books**:

```sql
SELECT book_id, title, publication_date
FROM books
ORDER BY publication_date DESC
LIMIT 5;
```

This query retrieves the 5 most recently published books.

- **Retrieve the books with the lowest prices (for a promotion)**:

```sql
SELECT book_id, title, price
FROM books
ORDER BY price ASC
LIMIT 10;
```

This query retrieves the 10 cheapest books, which could be used for a promotional display on the bookstore's website.

- **Implement pagination for a search results page**:

Suppose you have a search results page that displays 20 books per page. To retrieve the books for the third page, you would use the following query:

```sql
SELECT book_id, title, price
FROM books
WHERE title LIKE '%SQL%'  -- Example search condition
ORDER BY title
LIMIT 20 OFFSET 40;
```

This query retrieves 20 books, starting from the 41st book (offset 40), which corresponds to the third page of results (assuming each page displays 20 books).

**Edge Cases and Considerations**

- **No ORDER BY**: If you use ```LIMIT``` without an ```ORDER BY``` clause, the order of the returned rows is not guaranteed. The database is free to return the rows in any order it chooses.

- **LIMIT value greater than the number of rows**: If the ```LIMIT``` value is greater than the number of rows in the table, the query will simply return all rows in the table.

- **Negative LIMIT or OFFSET values**: Most SQL databases do not allow negative values for ```LIMIT``` or ```OFFSET```. Using negative values may result in an error.

- **Performance**: Using ```LIMIT``` can significantly improve query performance, especially when dealing with large tables. By restricting the number of rows returned, you reduce the amount of data that the database needs to process and transmit. However, the performance benefit is maximized when combined with appropriate indexing and filtering. We will discuss indexes in a later module.

- **SQL Dialect Differences**: While the basic syntax of ```LIMIT``` is generally consistent across different SQL dialects (e.g., MySQL, PostgreSQL, SQLite), there might be slight variations in the syntax for specifying the offset. Always consult the documentation for your specific database system.


#### <a name="chapter2part5"></a>Chapter 2 - Part 5: Using Aliases for Columns and Tables: Improving Readability

Aliases are essential tools in SQL for making queries more readable and understandable, especially when dealing with complex table structures or lengthy column names. They allow you to assign temporary, alternative names to columns and tables within a query, without permanently changing the underlying database schema. This enhances clarity and simplifies the process of referencing these elements, leading to more maintainable and efficient SQL code.

#### <a name="chapter2part5.1"></a>Chapter 2 - Part 5.1: Understanding Aliases

An alias is a temporary name assigned to a column or a table in a SQL query. It exists only for the duration of that query. Aliases are particularly useful in the following scenarios:

- **Improving Readability**: When column names are cryptic or lengthy, aliases can provide more descriptive and concise alternatives.

- **Avoiding Ambiguity**: When joining tables with columns that have the same name, aliases help distinguish between them.

- **Simplifying Complex Queries**: Aliases can make complex queries easier to understand and maintain by providing shorter, more meaningful names for tables and calculated columns.

**Column Aliases**

A column alias renames a column in the result set of a query. This is done using the ```AS``` keyword (though it's often optional in many SQL dialects).

```sql
SELECT column_name AS alias_name
FROM table_name;
```

Let's say we have a table named ```books``` in our "Online Bookstore" database with columns like ```book_id```, ```title```, and ```publication_year```.

```sql
SELECT
    title AS BookTitle,
    publication_year AS YearPublished
FROM
    books;
```

In this example, ```title``` is aliased as ```BookTitle```, and ```publication_year``` is aliased as ```YearPublished```. The result set will display these new column names instead of the original ones.

**Without the ```AS``` keyword**:

Many SQL dialects allow you to omit the ```AS``` keyword:

```sql
SELECT
    title BookTitle,
    publication_year YearPublished
FROM
    books;
```

This achieves the same result as using the ```AS``` keyword. However, using AS is generally considered good practice for improved readability.

**Column Aliases with Calculations**:

Aliases are particularly useful when performing calculations in the ```SELECT``` statement.

```sql
SELECT
    price * (1 - discount) AS discounted_price
FROM
    books;
```

Here, the calculated column ```price * (1 - discount)``` is aliased as ```discounted_price```, making the result set much easier to understand.

**Table Aliases**:

A table alias provides a temporary name for a table within a query. This is especially useful when joining multiple tables or when a table name is long and repetitive.

```sql
SELECT column_name(s)
FROM table_name AS alias_name;
```

Consider a query that joins the ```books``` table with an ```authors``` table.

```sql
SELECT
    b.title,
    a.author_name
FROM
    books AS b
INNER JOIN
    authors AS a ON b.author_id = a.author_id;
```

In this example, ```books``` is aliased as ```b```, and ```authors``` is aliased as ```a```. This makes the query more concise and easier to read, especially when referencing columns from these tables multiple times.

**Self-Joins and Table Aliases**:

Table aliases are essential when performing self-joins, where you join a table to itself. This is often used to compare rows within the same table.

Imagine we want to find books that were published in the same year.

```sql
SELECT
    b1.title AS Book1,
    b2.title AS Book2,
    b1.publication_year
FROM
    books AS b1
INNER JOIN
    books AS b2 ON b1.publication_year = b2.publication_year AND b1.book_id <> b2.book_id;
```

Here, we alias the ```books``` table as ```b1``` and ```b2``` to distinguish between the two instances of the table in the join condition. The ```b1.book_id <> b2.book_id``` condition prevents a book from being matched with itself.

#### <a name="chapter2part5.2"></a>Chapter 2 - Part 5.2: Practical Examples and Demonstrations

Let's delve into more practical examples using our "Online Bookstore" database to illustrate the power of aliases.

- **Example 1: Calculating Total Revenue with Aliases**

Suppose we have a table called ```orders``` with columns ```order_id```, ```book_id```, ```quantity```, and ```price```. We want to calculate the total revenue generated by each book.

```sql
SELECT
    b.title AS BookTitle,
    SUM(o.quantity * o.price) AS TotalRevenue
FROM
    orders AS o
INNER JOIN
    books AS b ON o.book_id = b.book_id
GROUP BY
    b.title;
```

In this query:

- ```books``` is aliased as ```b```, and ```orders``` is aliased as ```o```.

- ```b.title AS BookTitle``` provides a more descriptive name for the book title in the result set.

- ```SUM(o.quantity * o.price) AS TotalRevenue``` calculates the total revenue for each book and aliases it as ```TotalRevenue```.

- The ```GROUP BY``` clause groups the results by book title, allowing us to calculate the total revenue for each book. We will cover ```GROUP BY``` in more detail in a later module.

- **Example 2: Finding Authors with Multiple Books**

Let's say we want to find authors who have written more than one book in our bookstore.

```sql
SELECT
    a.author_name AS AuthorName,
    COUNT(b.book_id) AS NumberOfBooks
FROM
    authors AS a
INNER JOIN
    books AS b ON a.author_id = b.author_id
GROUP BY
    a.author_name
HAVING
    COUNT(b.book_id) > 1;
```

In this query:

- ```authors``` is aliased as ```a```, and ```books``` is aliased as ```b```.

- ```a.author_name AS AuthorName``` provides a clear name for the author's name in the result set.

- ```COUNT(b.book_id) AS NumberOfBooks``` counts the number of books written by each author and aliases it as ```NumberOfBooks```.

- The ```GROUP BY``` clause groups the results by author name.

- The ```HAVING``` clause filters the results to include only authors who have written more than one book. We will cover ```HAVING``` in more detail in a later module.

- **Example 3: Using Aliases with Subqueries**

Aliases are also useful when working with subqueries. A subquery is a query nested inside another query.

Suppose we want to find all books whose price is above the average price of all books.

```sql
SELECT
    b.title AS BookTitle,
    b.price AS BookPrice
FROM
    books AS b
WHERE
    b.price > (SELECT AVG(price) FROM books);
```

While this example doesn't explicitly alias the subquery itself, it demonstrates how aliases can be used within the main query to improve readability when working with subqueries. Subqueries will be covered in more detail in a later module.

#### <a name="chapter2part6"></a>Chapter 2 - Part 6: Practical Exercise: Querying the Bookstore Database

In this lesson, we'll put everything you've learned so far about ```SELECT``` statements into practice. We'll be working with our "Online Bookstore" database, querying its tables to retrieve specific information. This exercise will solidify your understanding of ```SELECT```, ```WHERE```, ```ORDER BY```, ```LIMIT```, and aliases, and prepare you for more complex queries involving joins in the next module.

#### <a name="chapter2part6.1"></a>Chapter 2 - Part 6.1: Bookstore Database Schema

Before we dive into the exercises, let's quickly recap the schema of our "Online Bookstore" database. This will help you understand the queries and the data we're working with.

We have the following tables:

- books: Contains information about each book.
  - book_id (INTEGER, PRIMARY KEY): Unique identifier for the book.
  - title (TEXT): Title of the book.
  - author_id (INTEGER, FOREIGN KEY referencing authors): ID of the author.
  - genre (TEXT): Genre of the book.
  - price (REAL): Price of the book.
  - publication_year (INTEGER): Year the book was published.
  - quantity_in_stock (INTEGER): Number of copies currently in stock.

- authors: Contains information about the authors.
  - author_id (INTEGER, PRIMARY KEY): Unique identifier for the author.
  - first_name (TEXT): First name of the author.
  - last_name (TEXT): Last name of the author.

- customers: Contains information about the customers.
  - customer_id (INTEGER, PRIMARY KEY): Unique identifier for the customer.
  - first_name (TEXT): First name of the customer.
  - last_name (TEXT): Last name of the customer.
  - email (TEXT): Email address of the customer.
  - registration_date (TEXT): Date the customer registered.

- orders: Contains information about the orders.
  - order_id (INTEGER, PRIMARY KEY): Unique identifier for the order.
  - customer_id (INTEGER, FOREIGN KEY referencing customers): ID of the customer who placed the order.
  - order_date (TEXT): Date the order was placed.
  - total_amount (REAL): Total amount of the order.

- order_items: Contains information about the items in each order.
  - order_item_id (INTEGER, PRIMARY KEY): Unique identifier for the order item.
  - order_id (INTEGER, FOREIGN KEY referencing orders): ID of the order.
  - book_id (INTEGER, FOREIGN KEY referencing books): ID of the book.
  - quantity (INTEGER): Quantity of the book ordered.
  - unit_price (REAL): Price of the book at the time of the order.

#### <a name="chapter2part6.2"></a>Chapter 2 - Part 6.2: Practical Exercises

Now, let's work through some practical exercises to query the bookstore database. We'll start with simple queries and gradually increase the complexity.

**Exercise 1: Retrieving All Books**

Write a query to retrieve the title, author_id, genre, and price of all books in the books table.

```sql
SELECT title, author_id, genre, price
FROM books;
```

This query selects the specified columns from the books table without any filtering or sorting. It will return all rows in the table.

**Exercise 2: Filtering Books by Genre**

Write a query to retrieve the title and price of all books in the "Fiction" genre.

```sql
SELECT title, price
FROM books
WHERE genre = 'Fiction';
```

This query uses the WHERE clause to filter the results, only returning books where the genre column is equal to "Fiction".

**Exercise 3: Sorting Books by Price**

Write a query to retrieve the title, author_id, and price of all books, sorted in descending order by price.

```sql
SELECT title, author_id, price
FROM books
ORDER BY price DESC;
```

This query uses the ORDER BY clause to sort the results by the price column. The DESC keyword specifies that the sorting should be in descending order (highest price first).

**Exercise 4: Limiting the Number of Results**

Write a query to retrieve the top 5 most expensive books (title and price).

```sql
SELECT title, price
FROM books
ORDER BY price DESC
LIMIT 5;
```

This query combines the ORDER BY clause with the LIMIT clause to retrieve only the top 5 most expensive books.

**Exercise 5: Using Aliases**

Write a query to retrieve the title, author_id, and price of all books, but rename the columns to "Book Title", "Author ID", and "Book Price" respectively.

```sql
SELECT title AS "Book Title",
       author_id AS "Author ID",
       price AS "Book Price"
FROM books;
```

This query uses aliases to rename the columns in the result set. This can improve readability, especially when dealing with complex queries or column names that are not very descriptive.

**Exercise 6: Combining WHERE, ORDER BY, and LIMIT**

Write a query to retrieve the 3 most recently published "Science Fiction" books (title and publication year).

```sql
SELECT title, publication_year
FROM books
WHERE genre = 'Science Fiction'
ORDER BY publication_year DESC
LIMIT 3;
```

This query combines the WHERE, ORDER BY, and LIMIT clauses to filter, sort, and limit the results. It first filters the books to only include those in the "Science Fiction" genre, then sorts them by publication year in descending order, and finally limits the results to the top 3.

**Exercise 7: Filtering with Multiple Conditions**

Write a query to retrieve the title and price of books that are either in the "Mystery" genre or have a price greater than $15.

```sql
SELECT title, price
FROM books
WHERE genre = 'Mystery' OR price > 15;
```

This query uses the OR operator in the WHERE clause to specify multiple conditions. It will return books that satisfy either condition.

**Exercise 8: Filtering with AND Operator**

Write a query to retrieve the title and price of books that are in the "Fantasy" genre and published before the year 2010.

```sql
SELECT title, price
FROM books
WHERE genre = 'Fantasy' AND publication_year < 2010;
```

This query uses the AND operator in the WHERE clause to specify multiple conditions. It will return books that satisfy both conditions.

**Exercise 9: Using BETWEEN Operator**

Write a query to retrieve the title and publication year of books published between 2005 and 2015 (inclusive).

```sql
SELECT title, publication_year
FROM books
WHERE publication_year BETWEEN 2005 AND 2015;
```

This query uses the BETWEEN operator to specify a range of values for the publication_year column.

**Exercise 10: Using IN Operator**

Write a query to retrieve the title and genre of books that are in the "Fiction", "Mystery", or "Thriller" genres.

```sql
SELECT title, genre
FROM books
WHERE genre IN ('Fiction', 'Mystery', 'Thriller');
```

This query uses the IN operator to specify a list of values for the genre column.

## <a name="chapter3"></a>Chapter 3: Working with Multiple Tables: Join

#### <a name="chapter3part1"></a>Chapter 3 - Part 1: Understanding Primary and Foreign Keys

Primary and foreign keys are the backbone of relational database design, ensuring data integrity and enabling efficient relationships between tables. Understanding these concepts is crucial for effectively querying and manipulating data across multiple tables, which we'll explore in the upcoming lessons on JOINs. Without a solid grasp of primary and foreign keys, you'll struggle to build robust and reliable database applications.

#### <a name="chapter3part1.1"></a>Chapter 3 - Part 1.1: Understanding Primary Keys

A primary key is a column or a set of columns in a table that uniquely identifies each row in that table. It's like a social security number for a person or a license plate for a car – no two rows can have the same primary key value.

**Key Characteristics of Primary Keys**

- **Uniqueness**: Every value in the primary key column (or combination of columns) must be unique.

- **Non-Null**: Primary key columns cannot contain NULL values. A NULL value means "unknown" or "missing," and it wouldn't make sense for a unique identifier to be unknown.

- **One per Table**: A table can have only one primary key. However, the primary key can consist of multiple columns (a composite key).

- **Immutability (Ideally)**: While not strictly enforced by all database systems, it's best practice for primary key values to be immutable, meaning they should not be changed after they're assigned. Changing a primary key can lead to data integrity issues and broken relationships with other tables.

**Examples of Primary Keys**

- **Online Bookstore Database**: In our ```books``` table, the ```book_id``` column is a good candidate for a primary key. Each book has a unique ID, and this ID will never be NULL. In the ```authors``` table, ```author_id``` serves as the primary key.

- **E-commerce Website**: In a table of ```customers```, the ```customer_id``` column would likely be the primary key. In an ```orders``` table, ```order_id``` would be the primary key.

- **Hypothetical Scenario: University Database**: In a ```students``` table, the ```student_id``` would be the primary key. In a ```courses``` table, a combination of ```course_code``` and ```semester``` might form a composite primary key, ensuring that each course offering is uniquely identified.

**Composite Primary Keys**

A composite primary key is a primary key that consists of two or more columns. This is used when a single column cannot uniquely identify a row.

**Example:**

Let's say we have a table called order_items that stores the individual items within each order in our online bookstore. The table might have the following columns:

- **```order_id```**: The ID of the order.

- **```book_id```**: The ID of the book in the order.

- **```quantity```**: The quantity of the book ordered.

In this case, neither ```order_id``` nor ```book_id``` alone can uniquely identify a row. An order can contain multiple books, and a book can be present in multiple orders. However, the combination of ```order_id``` and ```book_id``` will uniquely identify each item within an order. Therefore, we can define a composite primary key consisting of these two columns.

#### <a name="chapter3part1.2"></a>Chapter 3 - Part 1.2: Understanding Foreign Keys

A foreign key is a column (or set of columns) in one table that refers to the primary key in another table. It establishes a link between the two tables. The table containing the foreign key is called the "child" table or "referencing" table, and the table containing the primary key is called the "parent" table or "referenced" table.

**Key Characteristics of Foreign Keys**

- **Referential Integrity**: The main purpose of a foreign key is to enforce referential integrity. This means that the foreign key value in the child table must either match a valid primary key value in the parent table or be NULL. This prevents orphaned records – records in the child table that refer to non-existent records in the parent table.

- **Relationship**: Foreign keys define the relationships between tables. They specify how tables are related to each other.

- **Multiple per Table**: A table can have multiple foreign keys, each referencing a different parent table.

- **Data Type Matching**: The data type of the foreign key column(s) must match the data type of the primary key column(s) it references.

**Examples of Foreign Keys**

- **Online Bookstore Database**: In our ```books``` table, we might have an ```author_id``` column. This ```author_id``` would be a foreign key referencing the ```author_id``` (primary key) in the ```authors``` table. This establishes a relationship between books and authors, indicating which author wrote each book.

- **E-commerce Website**: In the ```orders``` table, the ```customer_id``` column would be a foreign key referencing the ```customer_id``` (primary key) in the ```customers``` table. This links each order to the customer who placed it.

- **Hypothetical Scenario: University Database**: In a ```enrollments``` table (which tracks student enrollments in courses), we would have two foreign keys: ```student_id``` referencing the ```students``` table and ```course_id``` referencing the ```courses``` table. This links each enrollment record to a specific student and a specific course.

**Foreign Key Constraints**

Foreign key constraints are rules that enforce referential integrity. They ensure that relationships between tables remain consistent and valid. Common foreign key constraints include:

- **ON DELETE CASCADE**: If a row is deleted from the parent table, all related rows in the child table are automatically deleted as well. Use this with caution, as it can lead to unintended data loss.

- **ON UPDATE CASCADE**: If the primary key value in the parent table is updated, the corresponding foreign key values in the child table are automatically updated as well.

- **ON DELETE SET NULL**: If a row is deleted from the parent table, the foreign key values in the child table are set to NULL. This is only allowed if the foreign key column allows NULL values.

- **ON DELETE SET DEFAULT**: If a row is deleted from the parent table, the foreign key values in the child table are set to a default value. This requires a default value to be defined for the foreign key column.

- **RESTRICT (or NO ACTION)**: This is the default behavior in many database systems. It prevents the deletion or update of a row in the parent table if there are related rows in the child table.

**Example of Foreign Key Constraints**

Continuing with our online bookstore example, let's say we want to ensure that when an author is deleted from the ```authors``` table, all their books are also removed from the ```books``` table. We can achieve this by setting the ```ON DELETE CASCADE``` constraint on the ```author_id``` foreign key in the ```books``` table.

#### <a name="chapter3part1.3"></a>Chapter 3 - Part 1.3: Practical Examples and Demonstrations

**Primary Keys and Foreign Keys**

Let's illustrate primary and foreign keys with examples using our online bookstore database. Assume we have two tables: ```authors``` and ```books```.

Table: ```authors```

| Column       | Data Type    | Constraints     |
| :----------: | :----------: | :-------------: |
| author_id    | INTEGER      |  PRIMARY KEY    |
| author_name  | TEXT         |  NOT NULL       |

```sql
CREATE TABLE authors (
    author_id INT PRIMARY KEY AUTO_INCREMENT,  -- Unique identifier for each author
    author_name VARCHAR(50) NOT NULL          -- Author's name (required)
);
```

Table: ```books```

| Column       | Data Type    | Constraints                                      |
| :----------: | :----------: | :----------------------------------------------: |
| book_id      | INTEGER      |  PRIMARY KEY                                     |
| title        | TEXT         |  NOT NULL                                        |
| author_id    | INTEGER      |  NOT NULL, FOREIGN KEY referencing authors       |
| price        | REAL         |  NOT NULL                                        |

```sql
CREATE TABLE books (
    book_id INT PRIMARY KEY AUTO_INCREMENT,   -- Unique identifier for each book
    title VARCHAR(100) NOT NULL,           -- Book title (required)
    author_id INT,                           -- Foreign key referencing the Authors table
    price DECIMAL(10, 2),                    -- PRICE of the Book
    FOREIGN KEY (author_id) REFERENCES authors(author_id) ON DELETE CASCADE  -- Establishes the foreign key relationship
);
```

In this scenario:

- ```author_id``` in the ```authors``` table is the primary key, uniquely identifying each author.

- ```book_id``` in the ```books``` table is the primary key, uniquely identifying each book.

- ```author_id``` in the ```books``` table is a foreign key referencing the ```authors``` table. This establishes a relationship between books and authors. When you delete an author from the ```authors``` table, you need to handle the books associated with that author in the ```books``` table. This is why we are using ```ON DELETE CASCADE```.

If we not created the table with ```ON DELETE CASCADE```, we can make

- **Drop the Existing Foreign Key (if it exists)**: If you've already created the Books table without ON DELETE CASCADE, you'll need to drop the existing foreign key constraint first. The exact syntax for this can vary slightly depending on your database system (MySQL, PostgreSQL, etc.). Here's how it generally looks in MySQL:

```sql
ALTER TABLE books
DROP FOREIGN KEY books_ibfk_1;  -- Replace 'books_ibfk_1' with the actual name of your foreign key constraint
```

To find the name of the foreign key constraint, you can use a query like this in MySQL:

```sql
SHOW CREATE TABLE books;
```
The output will show the CREATE TABLE statement, and you can find the FOREIGN KEY definition and its constraint name.

- **Re-create the Foreign Key with ON DELETE CASCADE**: Now, re-add the foreign key constraint with the ON DELETE CASCADE option:

```sql
ALTER TABLE books
ADD CONSTRAINT FK_AuthorBook
FOREIGN KEY (author_id) REFERENCES authors(author_id)
ON DELETE CASCADE;
```

**Composition Keys**

Imagine we're designing a database for a university to manage student enrollments in courses. We have the following entities:

- **Students**: Each student has a unique ID, name, etc.

- **Courses**: Each course has a unique ID, title, credits, etc.

- **Enrollments**: This table represents which students are enrolled in which courses.

In this scenario, a single student can enroll in multiple courses, and a single course can have multiple students. Therefore, neither the ```StudentID``` nor the ```CourseID``` alone can uniquely identify a row in the ```Enrollments``` table. This is where a composite key comes in handy.

| StudentID    | CourseID    | 	EnrollmentDate     | Grade       |
| :----------: | :---------: | :-----------------: |  :--------: |
| 101          | 201         |  2023-09-01         |  A          |
| 101          | 202         |  2023-09-01         |  B          |
| 102          | 201         |  2023-09-01         |  C          |
| 102          | 203         |  2023-09-01         |  A          |

The composite key for the ```Enrollments``` table would be the combination of (```StudentID```, ```CourseID```). This ensures that each row in the ```Enrollments``` table is uniquely identified by the combination of the student and the course they are enrolled in. A student can only be enrolled in a specific course once.

```sql
CREATE TABLE Enrollments (
    StudentID INT,
    CourseID INT,
    EnrollmentDate DATE,
    Grade VARCHAR(2),
    PRIMARY KEY (StudentID, CourseID),
    FOREIGN KEY (StudentID) REFERENCES Students(StudentID),
    FOREIGN KEY (CourseID) REFERENCES Courses(CourseID)
);
```

Explanation:

- PRIMARY KEY (StudentID, CourseID): This line defines the composite key consisting of the StudentID and CourseID columns.
- FOREIGN KEY (StudentID) REFERENCES Students(StudentID): This creates a foreign key relationship with the Students table, ensuring that the StudentID exists in the Students table.
- FOREIGN KEY (CourseID) REFERENCES Courses(CourseID): This creates a foreign key relationship with the Courses table, ensuring that the CourseID exists in the Courses table.

#### <a name="chapter3part2"></a>Chapter 3 - Part 2: Introduction to JOINs: Combining Data from Multiple Tables

In relational databases, data is often spread across multiple tables to reduce redundancy and improve data integrity. To retrieve meaningful information, we need to combine data from these related tables. This is where JOINs come in. JOINs allow us to link rows from two or more tables based on a related column, creating a unified result set that provides a more complete view of the data. Understanding JOINs is crucial for effective data retrieval and analysis in SQL.

#### <a name="chapter3part2.1"></a>Chapter 3 - Part 2.1: Understanding Primary and Foreign Keys

Before diving into JOINs, it's essential to understand the concepts of primary and foreign keys. These keys are the foundation for establishing relationships between tables.

**Primary Key**

A primary key is a column or a set of columns in a table that uniquely identifies each row in that table. It must contain unique values and cannot contain NULL values. Think of it as the social security number for each row in your table.

**Example**:

In our "Online Bookstore" database, the books table likely has a book_id column as its primary key. Each book in the table has a unique book_id.

**Foreign Key**

A foreign key is a column or a set of columns in one table that refers to the primary key of another table. It establishes a link between the two tables. The table containing the foreign key is called the child table or referencing table, and the table containing the primary key is called the parent table or referenced table.

**Example**:

Consider an orders table in our bookstore database. It might have a customer_id column that refers to the customer_id column (the primary key) in the customers table. This customer_id in the orders table is a foreign key. It indicates which customer placed a particular order.

#### <a name="chapter3part2.2"></a>Chapter 3 - Part 2.2: Introduction to JOINs: Combining Data from Multiple Tables

JOINs are SQL clauses used to combine rows from two or more tables based on a related column between them. The related column is usually a primary key in one table and a foreign key in another. JOINs allow you to retrieve data from multiple tables in a single query, providing a more comprehensive view of your data.

**The Need for JOINs**

Without JOINs, retrieving related data from multiple tables would be cumbersome and inefficient. You would have to execute multiple queries and manually combine the results in your application code. JOINs simplify this process by allowing you to perform this combination directly within the database.

Example:

Suppose you want to retrieve the names of all customers who have placed orders and the details of those orders. Without JOINs, you would need to:

- Query the orders table to get a list of customer_id values.

- Iterate through the customer_id values and query the customers table for each customer_id to retrieve the customer's name.

With a JOIN, you can achieve this with a single query.

**Basic JOIN Syntax**

The basic syntax for a JOIN involves specifying the tables you want to join and the condition that defines how the tables are related.

```sql
SELECT column1, column2, ...
FROM table1
JOIN table2
ON table1.column_name = table2.column_name;
```

- SELECT column1, column2, ...: Specifies the columns you want to retrieve from the joined tables.

- FROM table1: Specifies the first table in the join.

- JOIN table2: Specifies the second table in the join. The JOIN keyword can be replaced with specific join types like INNER JOIN, LEFT JOIN, etc. (covered in later lessons).

- ON table1.column_name = table2.column_name: Specifies the join condition. This condition defines how the rows from the two tables are related. It typically compares the primary key column from one table with the foreign key column in the other table.

**Example**:

To retrieve the book title and author name for all books in our bookstore database, assuming we have books table with book_id and title columns, and authors table with author_id and author_name columns, and a book_authors table linking them with book_id and author_id columns:

```sql
SELECT books.title, authors.author_name
FROM books
JOIN book_authors ON books.book_id = book_authors.book_id
JOIN authors ON book_authors.author_id = authors.author_id;
```

**Table Aliases**

Using table aliases can make your JOIN queries more readable, especially when dealing with multiple tables or long table names. A table alias is a short, temporary name assigned to a table within a query.

Syntax:

```sql
SELECT alias1.column1, alias2.column2
FROM table1 AS alias1
JOIN table2 AS alias2
ON alias1.column_name = alias2.column_name;
```

Example:

Using table aliases in the previous example:

```sql
SELECT b.title, a.author_name
FROM books AS b
JOIN book_authors AS ba ON b.book_id = ba.book_id
JOIN authors AS a ON ba.author_id = a.author_id;
```

This makes the query easier to read and understand.

**Qualifying Column Names**

When selecting columns from multiple tables in a JOIN query, it's important to qualify the column names by prefixing them with the table name or alias. This is especially important when the same column name exists in multiple tables.

Example:

If both the customers and orders tables have a column named date, you need to specify which table the date column refers to:

```sql
SELECT customers.customer_name, orders.order_date
FROM customers
JOIN orders ON customers.customer_id = orders.customer_id;
```

If you don't qualify the column names, the database might return an error or produce unexpected results.

**Joining Multiple Tables**

You can join more than two tables in a single query by adding more JOIN clauses. The order in which you join the tables can sometimes affect performance, so it's good to understand your data and relationships.

Example:

To retrieve customer name, order date, and book title for all orders in our bookstore database:

```sql
SELECT c.customer_name, o.order_date, b.title
FROM customers AS c
JOIN orders AS o ON c.customer_id = o.customer_id
JOIN order_items AS oi ON o.order_id = oi.order_id
JOIN books AS b ON oi.book_id = b.book_id;
```

This query joins four tables: customers, orders, order_items, and books, to retrieve the desired information.

#### <a name="chapter3part2.3"></a>Chapter 3 - Part 2.3: Practical Examples and Demonstrations

Let's consider a simplified version of our "Online Bookstore" database with the following tables:

customers table:

| customer_id | customer_name    | 	customer_email        |
| :---------: | :--------------: | :---------------------:|
| 1           | John Smith       |  john.smith@email.com  |
| 2           | Alice Johnson    | 	alice.j@example.com   |
| 3           | Bob Williams     |  bob.williams@test.org |

orders table:

| order_id      | customer_id  |  order_date     |
| :-----------: | :----------: | :--------------:|
| 101           | 1            |  2023-01-15     |
| 102           | 2            |  2023-02-20     |
| 103           | 3            |  2023-03-10     |
| 104           | 4            |  2023-04-05     |

**Example 1: Retrieving Customer Names and Order Dates**

To retrieve the name of each customer and the date of their orders:

```sql
SELECT c.customer_name, o.order_date
FROM customers AS c
JOIN orders AS o ON c.customer_id = o.customer_id;
```

**Example 2: Retrieving Customer Email and Order ID**

To retrieve the email of each customer and their order ID:

```sql
SELECT c.customer_email, o.order_id
FROM customers AS c
JOIN orders AS o ON c.customer_id = o.customer_id;
```

**Example 3: Joining with a WHERE Clause**

You can combine JOINs with WHERE clauses to filter the results. For example, to retrieve the name and order date for orders placed in January 2023:

```sql
SELECT c.customer_name, o.order_date
FROM customers AS c
JOIN orders AS o ON c.customer_id = o.customer_id
WHERE o.order_date LIKE '2023-01%';
```

#### <a name="chapter3part3"></a>Chapter 3 - Part 3: INNER JOIN: Retrieving Matching Rows

The INNER JOIN is a fundamental operation in SQL that allows you to combine data from two or more tables based on a related column between them. It's crucial for querying relational databases where information is spread across multiple tables to maintain data integrity and reduce redundancy. Understanding INNER JOIN is essential for retrieving meaningful and coherent datasets.

#### <a name="chapter3part3.1"></a>Chapter 3 - Part 3.1: Understanding INNER JOIN

An INNER JOIN returns only the rows where there is a match in both tables based on the specified join condition. If there's no match, the row is excluded from the result set. The join condition is typically defined using the ON keyword, which specifies the columns to compare between the tables.

**Basic Syntax**

The basic syntax for an INNER JOIN is as follows:

```sql
SELECT column1, column2, ...
FROM table1
INNER JOIN table2
ON table1.column_name = table2.column_name;
```

- SELECT column1, column2, ...: Specifies the columns you want to retrieve from the tables.

- FROM table1: Specifies the first table you want to join.

- INNER JOIN table2: Specifies the second table you want to join with the first table.

- ON table1.column_name = table2.column_name: Specifies the join condition, indicating which columns from the two tables should be compared for matching rows.

**Example: Joining Customers and Orders Tables**

Let's consider two tables: Customers and Orders. The Customers table contains information about customers, and the Orders table contains information about orders placed by those customers. The tables share a common column, CustomerID, which is a foreign key in the Orders table referencing the primary key in the Customers table.

**Customers Table:**

| CustomerID  | FirstName  | LastName   | City        |
| :---------: | :--------: | :---------:| :----------:|
| 1           | John       |  Doe       | New York    |
| 2           | Jane       |  Smith     | Los Angeles |
| 3           | David      |  Johnson   | Chicago     |
| 4           | Emily      |  Brown     | Houston     |

**Orders Table:**

| OrderID  | CustomerID | OrderDate    | TotalAmount  |
| :------: | :--------: | :-----------:| :-----------:|
| 101      | 1          |  2023-01-15  | 100.00       |
| 102      | 2          |  2023-02-20  | 200.00       |
| 103      | 1          |  2023-03-10  | 150.00       |
| 104      | 3          |  2023-04-05  | 300.00       |

To retrieve the first name of each customer along with their order details, you can use an INNER JOIN:

```sql
SELECT Customers.FirstName, Orders.OrderID, Orders.OrderDate, Orders.TotalAmount
FROM Customers
INNER JOIN Orders
ON Customers.CustomerID = Orders.CustomerID;
```

Notice that Emily Brown is not included in the result because she has not placed any orders in the Orders table. This is the key characteristic of an INNER JOIN: only matching rows are returned.

**Using Aliases for Clarity**

When working with multiple tables, especially when column names are the same across tables, using aliases can make your queries more readable and less ambiguous. You can assign aliases to both tables and columns.

```sql
SELECT c.FirstName, o.OrderID, o.OrderDate, o.TotalAmount
FROM Customers AS c
INNER JOIN Orders AS o
ON c.CustomerID = o.CustomerID;
```

In this example, c is an alias for the Customers table, and o is an alias for the Orders table. This makes the query shorter and easier to understand.

**Joining Multiple Tables**

You can also join more than two tables using multiple INNER JOIN clauses. Suppose you have a third table called OrderItems that contains information about the items included in each order.

**OrderItems Table:**

| OrderItemID  | OrderID | ProductID    | Quantity  |
| :------: | :--------: | :-----------:| :-----------:|
| 1      | 101          |  1  | 2       |
| 2      | 101          |  2  | 1       |
| 3      | 102          |  3  | 3       |
| 4      | 103          |  1  | 1       |
| 5      | 104          |  2  | 2       |

To retrieve the customer's first name, order ID, and the quantity of each item in the order, you can join all three tables:

```sql
SELECT c.FirstName, o.OrderID, oi.Quantity
FROM Customers AS c
INNER JOIN Orders AS o ON c.CustomerID = o.CustomerID
INNER JOIN OrderItems AS oi ON o.OrderID = oi.OrderID;
```

**Filtering Joined Data**

You can combine INNER JOIN with WHERE clauses to filter the joined data based on specific conditions. For example, to retrieve only the orders placed by customers in New York:

```sql
SELECT c.FirstName, o.OrderID, o.OrderDate, o.TotalAmount
FROM Customers AS c
INNER JOIN Orders AS o ON c.CustomerID = o.CustomerID
WHERE c.City = 'New York';
```

**INNER JOIN with different data types**

While it's most common to join on integer-based primary and foreign keys, INNER JOIN can also be used with other data types, such as strings or dates, as long as the data types are compatible for comparison.

For example, consider a Products table and a ProductCategories table, where both have a CategoryName column of type VARCHAR.

**Products Table:**

| ProductID  | ProductName | CategoryName    | Price  |
| :------: | :--------: | :-----------:| :-----------:|
| 1      | Laptop          |  Electronics  | 1200       |
| 2      | Mouse          |  Electronics  | 25       |
| 3      | T-shirt          |  Apparel  | 30       |
| 4      | Jeans          |  Apparel  | 75       |

**ProductCategories Table:**

| CategoryID  | CategoryName | Description    |
| :------: | :--------: | :-----------:|
| 1      | Electronics          |  Electronic devices  |
| 2      | Apparel          |  Clothing items  |

You can join these tables using the CategoryName column:

```sql
SELECT p.ProductName, pc.Description
FROM Products AS p
INNER JOIN ProductCategories AS pc ON p.CategoryName = pc.CategoryName;
```

This query will return:

| ProductName  | Description |
| :------: | :--------: |
| Laptop      | Electronic devices          |
| Mouse      | Electronic devices          |
| T-shirt      | Clothing items          |
| Jeans      | Clothing items          |

#### <a name="chapter3part3.2"></a>Chapter 3 - Part 3.2: Practical Examples and Demonstrations

Let's revisit the "Online Bookstore" database introduced in Module 1 and build upon it. Assume we have the following tables: Books, Authors, and Book_Authors (a linking table to handle the many-to-many relationship between books and authors).

**Books Table:**


|BookID	|Title|ISBN	|PublicationYear|
| :--------: | :--------: | :--------: | :--------: |
|1	|The Great Gatsby|	978-0743273565|	1925|
|2|	To Kill a Mockingbird	|978-0446310789	|1960|
|3	|1984|	978-0451524935|	1949|

**Authors Table:**

|AuthorID	|FirstName|	LastName|
| :--------: | :--------: | :--------: |
|1	|F. Scott|	Fitzgerald|
|2	|Harper|	Lee|
|3	|George	|Orwell|

**Book_Authors Table:**

|BookID	|AuthorID|
| :--------: | :--------: |
|1	|1|
|2|2|
|3|	3|

**Example 1: Retrieving Book Titles and Author Names**

To retrieve a list of book titles along with their author's names, you can use an INNER JOIN to combine the Books, Authors, and Book_Authors tables:

```sql
SELECT b.Title, a.FirstName, a.LastName
FROM Books AS b
INNER JOIN Book_Authors AS ba ON b.BookID = ba.BookID
INNER JOIN Authors AS a ON ba.AuthorID = a.AuthorID;
```

This query will return the following result:


|Title|	FirstName|	LastName|
| :--------: | :--------: | :--------: |
|The Great Gatsby|	F. Scott|	Fitzgerald|
|To Kill a Mockingbird	|Harper|	Lee|
|1984|	George	|Orwell|

**Example 2: Filtering Books by Publication Year**

To retrieve only the books published after 1950 along with their author's names:

```sql
SELECT b.Title, a.FirstName, a.LastName
FROM Books AS b
INNER JOIN Book_Authors AS ba ON b.BookID = ba.BookID
INNER JOIN Authors AS a ON ba.AuthorID = a.AuthorID
WHERE b.PublicationYear > 1950;
```

This query will return:

|Title	|FirstName	|LastName|
| :--------: | :--------: | :--------: |
|To Kill a Mockingbird	|Harper	|Lee|

**Example 3: Counting Books per Author**

To find out how many books each author has in the database:

```sql
SELECT a.FirstName, a.LastName, COUNT(b.BookID) AS NumberOfBooks
FROM Authors AS a
INNER JOIN Book_Authors AS ba ON a.AuthorID = ba.AuthorID
INNER JOIN Books AS b ON ba.BookID = b.BookID
GROUP BY a.AuthorID, a.FirstName, a.LastName;
```

This query will return:


|FirstName|	LastName	|NumberOfBooks|
| :--------: | :--------: | :--------: |
|F. Scott|	Fitzgerald|	1|
|Harper|	Lee|1|
|George|	Orwell|	1|

#### <a name="chapter3part4"></a>Chapter 3 - Part 4: LEFT JOIN (LEFT OUTER JOIN): Retrieving All Rows from the Left Table

The LEFT JOIN, also known as LEFT OUTER JOIN, is a crucial tool in SQL for combining data from multiple tables while ensuring that all rows from one table (the "left" table) are included in the result, regardless of whether there are matching rows in the other table (the "right" table). This is particularly useful when you need to see all records from a primary table and any related information from another table, even if some records in the primary table don't have corresponding entries in the related table. Understanding LEFT JOINs is essential for building comprehensive queries and generating meaningful reports from relational databases.

#### <a name="chapter3part4.1"></a>Chapter 3 - Part 4.1: Understanding the LEFT JOIN

A LEFT JOIN returns all rows from the left table and the matching rows from the right table. If there is no match in the right table for a row in the left table, the result will contain NULL values for the columns from the right table. The basic syntax is as follows:

```sql
SELECT column_list
FROM left_table
LEFT JOIN right_table ON left_table.column_name = right_table.column_name;
```

- left_table: The table from which all rows will be returned.

- right_table: The table that will be joined with the left table based on the specified condition.

- ON left_table.column_name = right_table.column_name: The join condition that specifies how the tables are related. This is typically based on primary and foreign key relationships.

- column_list: Specifies the columns to be retrieved from both tables.

**Key Principles of LEFT JOIN**

- **All Rows from the Left Table**: The most important characteristic of a LEFT JOIN is that it guarantees the inclusion of every row from the left table in the result set.

- **Matching Rows from the Right Table**: If a row in the left table has a matching row in the right table (based on the ON condition), the corresponding columns from the right table will be included in the result.

- **NULL Values for Non-Matching Rows**: If a row in the left table does not have a matching row in the right table, the columns from the right table will contain NULL values for that row.

- **Order Matters**: The order of the tables in the LEFT JOIN clause is significant. The table listed first is the left table, and the table listed second is the right table. Swapping the order of the tables will change the result.

#### <a name="chapter3part4.2"></a>Chapter 3 - Part 4.2: Practical Examples Using the Bookstore Database

Let's continue using the "Online Bookstore" database introduced in Module 1. Assume we have two tables: books and authors.

- books table: Contains information about each book, including book_id (primary key), title, author_id (foreign key referencing the authors table), and price.

- authors table: Contains information about each author, including author_id (primary key) and author_name.

**Example 1: Retrieving All Books and Their Authors**

Suppose we want to retrieve a list of all books and their corresponding author names. We want to ensure that all books are listed, even if an author's information is missing (which shouldn't happen in a well-designed database, but it's a good example for illustrating LEFT JOIN).

```sql
SELECT
    books.title,
    authors.author_name
FROM
    books
LEFT JOIN
    authors ON books.author_id = authors.author_id;
```

In this query:

- books is the left table. All rows from the books table will be included in the result.

- authors is the right table. Only matching rows from the authors table (based on author_id) will be included.

- If a book has an author_id that does not exist in the authors table, the author_name column will contain NULL for that book.

**Example 2: Identifying Books Without an Author (Hypothetical)**

While it's unlikely in a properly designed bookstore database, let's imagine a scenario where some books might not have an associated author in the authors table (perhaps due to data entry errors or incomplete records). We can use a LEFT JOIN to identify these books.

```sql
SELECT
    books.title
FROM
    books
LEFT JOIN
    authors ON books.author_id = authors.author_id
WHERE
    authors.author_id IS NULL;
```

In this query:

- We use a WHERE clause to filter the results and only include rows where authors.author_id is NULL. This indicates that there was no matching author for the book in the authors table.

**Example 3: Joining with Additional Tables**

Let's add a categories table to our bookstore database, with columns category_id (primary key) and category_name. We can modify our query to include the category name as well. Assume the books table now also has a category_id column.

```sql
SELECT
    books.title,
    authors.author_name,
    categories.category_name
FROM
    books
LEFT JOIN
    authors ON books.author_id = authors.author_id
LEFT JOIN
    categories ON books.category_id = categories.category_id;
```

This query demonstrates how to chain multiple LEFT JOIN operations. It retrieves the book title, author name, and category name for all books. If a book doesn't have a matching author or category, the corresponding columns will contain NULL values.

**Example 4: Using Aliases for Readability**

Using aliases can make your queries more readable, especially when joining multiple tables.

```sql
SELECT
    b.title,
    a.author_name
FROM
    books AS b
LEFT JOIN
    authors AS a ON b.author_id = a.author_id;
```

Here, b is an alias for books, and a is an alias for authors. This makes the query shorter and easier to understand.

#### <a name="chapter3part5"></a>Chapter 3 - Part 5: RIGHT JOIN (RIGHT OUTER JOIN): Retrieving All Rows from the Right Table

The RIGHT JOIN, also known as RIGHT OUTER JOIN, is a crucial tool in SQL for retrieving data from multiple tables. Unlike the INNER JOIN, which only returns matching rows, the RIGHT JOIN ensures that all rows from the right table are included in the result set, even if there are no matching rows in the left table. This is particularly useful when you need to see a complete list of records from one table and any related information from another.

#### <a name="chapter3part5.1"></a>Chapter 3 - Part 5.1: Understanding the RIGHT JOIN

The RIGHT JOIN combines rows from two tables based on a related column. The syntax is as follows:

```sql
SELECT column_list
FROM table_name_1
RIGHT JOIN table_name_2 ON table_name_1.column_name = table_name_2.column_name;
```

- table_name_1 is the left table.

- table_name_2 is the right table.

- column_name is the column used for the join condition.

- The RIGHT JOIN keyword specifies that all rows from table_name_2 (the right table) should be included in the result.

- If there is a match between rows in table_name_1 and table_name_2 based on the ON condition, the corresponding columns from both tables are included in the result.

- If there is no match for a row in table_name_2 in table_name_1, the columns from table_name_1 will contain NULL values for that row.

**Example: Online Bookstore Database**

Let's continue using the "Online Bookstore" database introduced in Module 1. Assume we have two tables: books and authors.

books table:


|book_id	|title	|author_id|
| :--------: | :--------: | :--------: |
|1|	The Great Novel|	1|
|2|	Another Good Book|	2|
|3|	A Mystery|	1|
|4|	The Lost Manuscript|	3|


authors table:


|author_id	|author_name|
| :--------: | :--------: |
|1|	John Smith|
|2|	Jane Doe|
|3|	David Lee|
|4|	Emily White|

Now, let's use a RIGHT JOIN to retrieve all authors and their corresponding books:

```sql
SELECT
    b.title,
    a.author_name
FROM
    books b
RIGHT JOIN
    authors a ON b.author_id = a.author_id;
```

Result:


|title	|author_name|
| :--------: | :--------: |
|The Great Novel|	John Smith|
|A Mystery|	John Smith|
|Another Good Book|	Jane Doe|
|The Lost Manuscript|	David Lee|
|NULL|	Emily White|

Notice that Emily White is included in the result, even though she doesn't have any books in the books table. The title column is NULL for Emily White because there's no matching book.

**Handling NULL Values**

When using RIGHT JOIN, it's common to encounter NULL values in the columns from the left table when there's no match. You can use the COALESCE() function to replace NULL values with a default value.

For example, to replace the NULL title with "No Book":

```sql
SELECT
    COALESCE(b.title, 'No Book') AS title,
    a.author_name
FROM
    books b
RIGHT JOIN
    authors a ON b.author_id = a.author_id;
```

Result:

|title	|author_name|
| :--------: | :--------: |
|The Great Novel|	John Smith|
|A Mystery|	John Smith|
|Another Good Book|	Jane Doe|
|The Lost Manuscript|	David Lee|
|No Book|	Emily White|

#### <a name="chapter3part5.2"></a>Chapter 3 - Part 5.2: Practical Examples

**Example 1: Customer Orders**

Consider two tables: customers and orders. You want to retrieve all customers, even those who haven't placed any orders.

customers table:


|customer_id|	customer_name|
| :--------: | :--------: |
|1|	Alice|
|2|	Bob|
|3|	Charlie|

orders table:


|order_id	|customer_id	|order_date|
| :--------: | :--------: | :--------: |
|1|	1	|2023-01-01|
|2	|2|	2023-01-02|

```sql
SELECT
    c.customer_name,
    o.order_id,
    o.order_date
FROM
    customers c
RIGHT JOIN
    orders o ON c.customer_id = o.customer_id;
```

This query will not return all customers. To return all customers, you need to switch the tables and use RIGHT JOIN on the customers table.

```sql
SELECT
    c.customer_name,
    o.order_id,
    o.order_date
FROM
    orders o
RIGHT JOIN
    customers c ON o.customer_id = c.customer_id;
```

Result:

|customer_name|	order_id|	order_date|
| :--------: | :--------: | :--------: |
|Alice	|1	|2023-01-01|
|Bob	|2	|2023-01-02|
|Charlie	|NULL|	NULL|

Charlie is included, even though he hasn't placed any orders.,

**Example 2: Employee Departments**

Consider two tables: employees and departments. You want to retrieve all departments, even those with no employees.

employees table:

|employee_id	|employee_name|	department_id|
| :--------: | :--------: | :--------: |
|1|	Alice|	1|
|2|	Bob|	2|

departments table:

|department_id|	department_name|
| :--------: | :--------: |
|1	|Sales|
|2|	Marketing|
|3	|HR|

```sql
SELECT
    e.employee_name,
    d.department_name
FROM
    employees e
RIGHT JOIN
    departments d ON e.department_id = d.department_id;
```

Result:

|employee_name	|department_name|
| :--------: | :--------: |
|Alice	|Sales|
|Bob|	Marketing|
|NULL|	HR|

The HR department is included, even though there are no employees in that department.

#### <a name="chapter3part6"></a>Chapter 3 - Part 6: FULL OUTER JOIN: Retrieving All Rows from Both Tables

FULL OUTER JOINs are essential for scenarios where you need a complete picture of data across multiple tables, regardless of whether there are matching entries. Unlike INNER, LEFT, or RIGHT JOINs, a FULL OUTER JOIN ensures that every row from both tables is included in the result set. This is particularly useful when identifying discrepancies, gaps, or comprehensive relationships between datasets.

#### <a name="chapter3part6.1"></a>Chapter 3 - Part 6.1: Understanding FULL OUTER JOIN

A FULL OUTER JOIN combines the results of both LEFT and RIGHT JOINs. It returns all rows from the left table and all rows from the right table. When there is a match between the tables based on the specified join condition, the corresponding columns are populated. If there is no match, the columns from the table without a match will contain NULL values.

**Syntax**

The basic syntax for a FULL OUTER JOIN is as follows:

```sql
SELECT column_name(s)
FROM table1
FULL OUTER JOIN table2
ON table1.column_name = table2.column_name;
```

- table1: The left table in the join.

- table2: The right table in the join.

- column_name(s): The columns you want to retrieve from the tables.

- ON table1.column_name = table2.column_name: The join condition, specifying how the tables are related.

**How it Works**

- The database starts by selecting all rows from the left table (table1).
- It then selects all rows from the right table (table2).
- For each row in table1, it checks if there is a matching row in table2 based on the ON condition.
  - If a match is found, the columns from both tables are combined into a single row in the result set.
  - If no match is found, the columns from table2 are filled with NULL values.
- For each row in table2 that did not have a match in table1, the columns from table1 are filled with NULL values.
- The final result set contains all rows from both tables, with NULL values where there are no matches.

#### <a name="chapter3part6.2"></a>Chapter 3 - Part 6.2: Practical Examples

Let's consider two tables in our online bookstore database: Customers and Orders.

**Customers Table:**


|customer_id|	customer_name|	email|
| :--------: | :--------: | :--------: |
|1	|John Smith	|john.smith@email.com|
|2|	Alice Johnson|	alice.j@email.com|
|3|	Bob Williams|	bob.w@email.com|
|4	|Emily Davis|	emily.d@email.com|

**Orders Table:**

|order_id	|customer_id|	order_date|	total_amount|
| :--------: | :--------: | :--------: | :--------: |
|101|	1|	2023-01-15|	50.00
|102|	2|	2023-02-20	|120.00
|103|	1|	2023-03-10|	75.00
|104|	5|	2023-04-05	|90.00

**Example 1: Retrieving All Customers and Orders**

Suppose we want to retrieve a list of all customers and their corresponding orders. If a customer has not placed any orders, we still want to see their information. Similarly, if there are orders from a customer_id that doesn't exist in the Customers table (perhaps due to data entry errors or deleted customer records), we want to see those orders as well.

```sql
SELECT
    Customers.customer_id,
    Customers.customer_name,
    Orders.order_id,
    Orders.order_date,
    Orders.total_amount
FROM
    Customers
FULL OUTER JOIN
    Orders ON Customers.customer_id = Orders.customer_id;
```

**Result:**

|customer_id	|customer_name	|order_id	|order_date	|total_amount|
| :--------: | :--------: | :--------: | :--------: |:--------: |
|1	|John Smith|	101	|2023-01-15|	50.00|
|1|	John Smith|	103|	2023-03-10	|75.00|
|2	|Alice Johnson|	102|	2023-02-20|	120.00|
|3	|Bob Williams|	NULL|	NULL|	NULL|
|4|	Emily Davis|	NULL|	NULL|	NULL|
|5	|NULL|	104|	2023-04-05|	90.00|

In this result:

- Customers John Smith and Alice Johnson have their orders listed.

- Bob Williams and Emily Davis have NULL values for order_id, order_date, and total_amount because they have not placed any orders.

- Order 104 is associated with customer_id 5, but there is no corresponding customer in the Customers table, so customer_name is NULL.

**Example 2: Identifying Customers Without Orders**

We can use a FULL OUTER JOIN to identify customers who have not placed any orders.

```sql
SELECT
    Customers.customer_id,
    Customers.customer_name
FROM
    Customers
FULL OUTER JOIN
    Orders ON Customers.customer_id = Orders.customer_id
WHERE
    Orders.customer_id IS NULL;
```

Result:

|customer_id|	customer_name|
| :--------: | :--------: |
|3	|Bob Williams|
|4|Emily Davis|

This query returns only the customers who do not have any corresponding entries in the Orders table.

**Example 3: Identifying Orders Without Corresponding Customers**

Similarly, we can identify orders that do not have a corresponding customer in the Customers table.

```sql
SELECT
    Orders.order_id,
    Orders.order_date
FROM
    Customers
FULL OUTER JOIN
    Orders ON Customers.customer_id = Orders.customer_id
WHERE
    Customers.customer_id IS NULL;
```

Result:


|order_id	|order_date|
| :--------: | :--------: |
|104|	2023-04-05|

This query returns only the orders for which there is no matching customer in the Customers table.

#### <a name="chapter3part7"></a>Chapter 3 - Part 7: Practical Exercise: Joining Tables in the Bookstore Database

Joining tables is a fundamental operation in relational databases, allowing you to combine data from multiple tables based on related columns. This is crucial for retrieving meaningful information that spans across different parts of your database. In the context of our online bookstore, joining tables enables us to answer questions like "Which books has a particular author written?" or "Which customers have ordered a specific book?". This lesson will provide practical exercises to solidify your understanding of JOIN operations using the bookstore database.

#### <a name="chapter3part7.1"></a>Chapter 3 - Part 7.1: Setting Up the Bookstore Database (Reminder)

Before we dive into the exercises, let's quickly recap the structure of our bookstore database. We have (at least) the following tables:

- books: Contains information about each book (book_id, title, author_id, genre, price, etc.).

- authors: Contains information about each author (author_id, first_name, last_name, etc.).

- customers: Contains information about customers (customer_id, first_name, last_name, email, etc.).

- orders: Contains information about orders (order_id, customer_id, order_date, etc.).

- order_items: Contains information about the items in each order (order_id, book_id, quantity, etc.).

The relationships between these tables are defined through primary and foreign keys. For example, the author_id column in the books table is a foreign key that references the author_id column in the authors table. Similarly, customer_id in the orders table references customer_id in the customers table, and the order_id and book_id in order_items reference orders and books respectively.

#### <a name="chapter3part7.2"></a>Chapter 3 - Part 7.2: Exercise 1: Retrieving Book Titles and Author Names

Let's start with a simple exercise: Retrieve the titles of all books along with the first and last names of their authors. This requires joining the books and authors tables.

```sql
SELECT
    books.title,
    authors.first_name,
    authors.last_name
FROM
    books
INNER JOIN
    authors ON books.author_id = authors.author_id;
```

- We use an INNER JOIN because we only want to retrieve books that have a corresponding author in the authors table.

- The ON clause specifies the join condition: books.author_id = authors.author_id. This tells the database to match rows where the author_id in the books table is equal to the author_id in the authors table.

- We select the title column from the books table and the first_name and last_name columns from the authors table.

- Using table aliases (e.g., b for books, a for authors) can make the query more readable, especially when dealing with multiple joins. The query would then look like this:

```sql
SELECT
    b.title,
    a.first_name,
    a.last_name
FROM
    books AS b
INNER JOIN
    authors AS a ON b.author_id = a.author_id;
```

#### <a name="chapter3part7.3"></a>Chapter 3 - Part 7.3: Exercise 2: Finding Customers and Their Orders

Now, let's find all customers and the dates of their orders. This involves joining the customers and orders tables.

```sql
SELECT
    customers.first_name,
    customers.last_name,
    orders.order_date
FROM
    customers
INNER JOIN
    orders ON customers.customer_id = orders.customer_id;
```

- Again, we use an INNER JOIN to retrieve only customers who have placed orders.

- The join condition is customers.customer_id = orders.customer_id.

- We select the customer's first name, last name, and the order date.

#### <a name="chapter3part7.4"></a>Chapter 3 - Part 7.4: Exercise 3: Retrieving Book Titles and Order Information

Let's combine information from the books, order_items, and orders tables to retrieve the titles of books that were ordered and the corresponding order dates.

```sql
SELECT
    books.title,
    orders.order_date
FROM
    books
INNER JOIN
    order_items ON books.book_id = order_items.book_id
INNER JOIN
    orders ON order_items.order_id = orders.order_id;
```

- This query involves two INNER JOIN operations.

- First, we join books and order_items on books.book_id = order_items.book_id to link books to the items in orders.

- Then, we join order_items and orders on order_items.order_id = orders.order_id to link the order items to the order dates.

- We select the book title and the order date.

#### <a name="chapter3part7.5"></a>Chapter 3 - Part 7.5: Exercise 4: Using LEFT JOIN to Find Authors Without Books

Now, let's use a LEFT JOIN to find all authors who have not written any books in our bookstore database.

```sql
SELECT
    authors.first_name,
    authors.last_name
FROM
    authors
LEFT JOIN
    books ON authors.author_id = books.author_id
WHERE
    books.book_id IS NULL;
```

- We use a LEFT JOIN to retrieve all authors, even those who don't have any corresponding books in the books table.

- The WHERE books.book_id IS NULL clause filters the results to include only authors for whom the book_id is NULL in the joined table. This indicates that there is no matching book for that author.

#### <a name="chapter3part7.6"></a>Chapter 3 - Part 7.6: Exercise 5: Combining Different JOIN Types

Let's consider a scenario where we want to list all customers and their orders, including customers who haven't placed any orders, and also list any orders that might not be associated with a customer (although this shouldn't happen in a well-designed database). While FULL OUTER JOIN is the ideal solution, some databases like MySQL don't directly support it. We can simulate it using UNION ALL with LEFT JOIN and RIGHT JOIN.

```sql
SELECT
    customers.first_name,
    customers.last_name,
    orders.order_date
FROM
    customers
LEFT JOIN
    orders ON customers.customer_id = orders.customer_id
UNION ALL
SELECT
    customers.first_name,
    customers.last_name,
    orders.order_date
FROM
    customers
RIGHT JOIN
    orders ON customers.customer_id = orders.customer_id
WHERE customers.customer_id IS NULL;
```

- The first SELECT statement uses a LEFT JOIN to retrieve all customers and their orders. If a customer has no orders, the order_date will be NULL.

- The second SELECT statement uses a RIGHT JOIN to retrieve all orders and their customers. The WHERE customers.customer_id IS NULL clause filters the results to include only orders that don't have a corresponding customer.

- The UNION ALL operator combines the results of the two SELECT statements. UNION ALL includes all rows from both result sets, including duplicates. If you want to remove duplicates, you can use UNION instead, but it's generally slower.

## <a name="chapter4"></a>Chapter 4: Data Manipulation: INSERT; UPDATE, and DELETE

#### <a name="chapter4part1"></a>Chapter 4 - Part 1: Inserting New Data with INSERT INTO

Inserting data into a database is a fundamental operation. The ```INSERT INTO``` statement is the primary way to add new rows of data into a table. Understanding how to use this statement effectively is crucial for building and maintaining any database-driven application. This lesson will cover the syntax of the ```INSERT INTO``` statement, different ways to insert data, and best practices for ensuring data integrity.

#### <a name="chapter4part1.1"></a>Chapter 4 - Part 1.1: Basic INSERT INTO Syntax

The INSERT INTO statement has two primary forms. The first form explicitly lists the columns you are inserting data into:

```sql
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```

- INSERT INTO: Specifies that you are inserting data into a table.

- table_name: The name of the table you are inserting data into.

- (column1, column2, column3, ...): An optional list of the columns you are inserting data into. If omitted, you must provide values for all columns in the table.

- VALUES (value1, value2, value3, ...): The values you want to insert into the corresponding columns. The order of the values must match the order of the columns specified (or the order of columns in the table if no columns are specified).

The second form omits the column list, but requires you to provide values for every column in the table, in the order they are defined:

```sql
INSERT INTO table_name
VALUES (value1, value2, value3, ...);
```

Example: Let's say we have a table named books in our "Online Bookstore" database with the following structure:

|Column	|Data Type|
| :--------: | :--------: |
|book_id|	INTEGER|
|title|	TEXT|
|author|	TEXT|
|price|	REAL|
|publication_year|	INTEGER|

To insert a new book into the books table, we can use either form of the INSERT INTO statement.

**Example 1 (Specifying Columns):**

```sql
INSERT INTO books (title, author, price, publication_year)
VALUES ('The Hitchhiker''s Guide to the Galaxy', 'Douglas Adams', 9.99, 1979);
```

In this example, we are only inserting data into the title, author, price, and publication_year columns. The book_id column (presumably an auto-incrementing primary key) will be automatically assigned a value by the database.

**Example 2 (Omitting Columns):**

```sql
INSERT INTO books
VALUES (5, 'Pride and Prejudice', 'Jane Austen', 7.50, 1813);
```

In this example, we are providing values for all columns in the books table, including book_id. It's crucial to know the order of the columns in the table definition when using this form.

#### <a name="chapter4part1.2"></a>Chapter 4 - Part 1.2: Inserting Data into Specific Columns

Specifying the columns you are inserting data into offers several advantages:

- **Flexibility**: You can insert data into only the columns you have values for.

- **Clarity**: It makes the statement more readable and easier to understand.

- **Maintainability**: If the table structure changes (e.g., a new column is added), your INSERT statements are less likely to break if you explicitly specify the columns.

**Example**: Suppose we want to add a new book to the books table, but we don't know the publication year yet. We can still insert the book with the available information:

```sql
INSERT INTO books (title, author, price)
VALUES ('To Kill a Mockingbird', 'Harper Lee', 12.00);
```

In this case, the publication_year column will be assigned a NULL value (if the column allows nulls) or a default value (if one is defined for the column).

#### <a name="chapter4part1.3"></a>Chapter 4 - Part 1.3: Inserting Multiple Rows

You can insert multiple rows into a table with a single INSERT INTO statement using the following syntax:

```sql
INSERT INTO table_name (column1, column2, column3, ...)
VALUES
    (value1_1, value1_2, value1_3, ...),
    (value2_1, value2_2, value2_3, ...),
    (value3_1, value3_2, value3_3, ...),
    ...;
```

**Example**: Let's add three new books to the books table at once:

```sql
INSERT INTO books (title, author, price, publication_year)
VALUES
    ('1984', 'George Orwell', 10.00, 1949),
    ('Brave New World', 'Aldous Huxley', 11.50, 1932),
    ('Fahrenheit 451', 'Ray Bradbury', 9.75, 1953);
```

This is more efficient than executing three separate INSERT INTO statements.

#### <a name="chapter4part1.4"></a>Chapter 4 - Part 1.4: Inserting Data from Another Table

You can also insert data into a table by selecting data from another table using the INSERT INTO ... SELECT statement:

```sql
INSERT INTO table_name (column1, column2, column3, ...)
SELECT columnA, columnB, columnC, ...
FROM another_table
WHERE condition;
```

- table_name: The table you are inserting data into.

- (column1, column2, column3, ...): The columns in the target table.

- SELECT columnA, columnB, columnC, ...: The columns you are selecting from the source table. The order and data types of these columns must match the order and data types of the columns in the target table.

- FROM another_table: The table you are selecting data from.

- WHERE condition: An optional WHERE clause to filter the data being inserted.

**Example**: Suppose we have a table called archived_books with the same structure as books. We can insert all books published before 1950 from archived_books into the books table:

```sql
INSERT INTO books (title, author, price, publication_year)
SELECT title, author, price, publication_year
FROM archived_books
WHERE publication_year < 1950;
```

#### <a name="chapter4part1.5"></a>Chapter 4 - Part 1.5: Data Type Considerations

When inserting data, it's crucial to ensure that the data types of the values you are inserting match the data types of the corresponding columns in the table. If the data types don't match, the database may attempt to implicitly convert the data, which can lead to unexpected results or errors.

- **Strings**: Enclose string values in single quotes (e.g., 'The Lord of the Rings'). If the string itself contains a single quote, escape it by doubling it (e.g., 'The Hitchhiker''s Guide to the Galaxy').

- **Numbers**: Do not enclose numeric values in quotes (e.g., 9.99, 1979).

- **Dates**: Date formats vary depending on the database system. Consult your database documentation for the correct date format (e.g., 'YYYY-MM-DD', 'MM/DD/YYYY').

- **NULL Values**: Use the keyword NULL to insert a null value into a column that allows nulls.

```sql
INSERT INTO books (title, author, price, publication_year)
VALUES ('The Shining', 'Stephen King', 15.00, NULL);
```

In this example, the publication_year column will be assigned a NULL value.

#### <a name="chapter4part1.6"></a>Chapter 4 - Part 1.6: Handling Errors and Constraints

When inserting data, you may encounter errors due to constraint violations. Constraints are rules that enforce data integrity, such as:

- **NOT NULL**: A column cannot contain a null value.

- **UNIQUE**: A column (or set of columns) must contain unique values.

- **PRIMARY KEY**: A column (or set of columns) that uniquely identifies each row in the table. Primary keys are typically also NOT NULL.

- **FOREIGN KEY**: A column that references the primary key of another table. Foreign keys enforce referential integrity, ensuring that relationships between tables are maintained.

- **CHECK**: A condition that must be true for all values in a column.

If you attempt to insert data that violates a constraint, the database will return an error and the INSERT statement will fail.

**Example**: Suppose the book_id column in the books table is a primary key with an auto-incrementing constraint. If you try to insert a row with a book_id that already exists, you will get a primary key violation error.

**Example**: Suppose the price column has a CHECK constraint that ensures the price is greater than 0. If you try to insert a row with a negative price, you will get a check constraint violation error.

#### <a name="chapter4part1.7"></a>Chapter 4 - Part 1.7: Best Practices for INSERT INTO Statements

- **Always specify columns**: Explicitly listing the columns you are inserting data into makes your code more readable, maintainable, and less prone to errors.

- **Validate data**: Before inserting data, validate it to ensure that it is in the correct format and meets any constraints. This can help prevent errors and ensure data integrity.

- **Use parameterized queries**: To prevent SQL injection vulnerabilities, use parameterized queries or prepared statements when inserting data from user input. This will be covered in a later module.

- **Handle errors gracefully**: Implement error handling to catch any exceptions that may occur during the insertion process. Log the errors and provide informative messages to the user.

- **Use transactions**: When inserting multiple rows or performing multiple data manipulation operations, use transactions to ensure that all operations are completed successfully or none are. This will be covered in the next lesson.

#### <a name="chapter4part2"></a>Chapter 4 - Part 2: Updating Existing Data with UPDATE

Updating data is a crucial aspect of database management, allowing us to correct errors, reflect changes in information, and maintain data accuracy. The UPDATE statement in SQL is the tool we use to modify existing records within a table. Understanding how to use UPDATE effectively, including specifying which rows to update and how to handle potential errors, is essential for anyone working with databases.

#### <a name="chapter4part2.1"></a>Chapter 4 - Part 2.1: The Basic Syntax of UPDATE

The fundamental syntax of the UPDATE statement is as follows:

```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```

Let's break down each part:

- UPDATE table_name: Specifies the table you want to modify.

- SET column1 = value1, column2 = value2, ...: Indicates which columns you want to update and the new values you want to assign to them. You can update one or more columns in a single UPDATE statement.

- WHERE condition: This is the most critical part. It specifies which rows should be updated. If you omit the WHERE clause, all rows in the table will be updated, which is rarely what you intend.

#### <a name="chapter4part2.2"></a>Chapter 4 - Part 2.2: Understanding the WHERE Clause

The WHERE clause is essential for targeting specific rows for modification. It uses the same conditional operators and logic as the WHERE clause in SELECT statements (covered in Module 2).

**Example 1: Updating a Single Row**

Let's say we have an authors table in our online bookstore database with the following structure and data:

|author_id|	first_name|	last_name|	email|
| :--------: | :--------: | :--------: | :--------: |
|1|	Jane|	Austen|	jane.austen@example.com|
|2|	Charles|	Dickens|	charles.dickens@example.com|
|3|	Leo|	Tolstoy|	leo.tolstoy@example.com|

If Jane Austen changed her email address, we would use the following UPDATE statement:

```sql
UPDATE authors
SET email = 'jane.austen.new@example.com'
WHERE author_id = 1;
```

This statement updates the email column for the row where author_id is 1.

**Example 2: Updating Multiple Columns**

Suppose Charles Dickens moved and we want to update both his email and a new address column (assuming we've added this column to the authors table).

```sql
UPDATE authors
SET email = 'charles.dickens.new@example.com', address = '123 New Address, London'
WHERE author_id = 2;
```

This statement updates both the email and address columns for the author with author_id 2.

**Example 3: Using Comparison Operators**

We can use other comparison operators in the WHERE clause. For example, if we wanted to give a bonus to all authors whose last name starts with 'T', we could (hypothetically) update a bonus column:

```sql
UPDATE authors
SET bonus = 100  -- Assuming a bonus column exists
WHERE last_name LIKE 'T%';
```

This uses the LIKE operator with a wildcard to match any last name starting with 'T'.

**Example 4: Updating Based on a Range**

Let's say we have a books table with a publication_year column. We want to mark all books published before 1900 as "classic". We would first need to add a genre column to the books table if it doesn't already exist.

```sql
UPDATE books
SET genre = 'Classic'
WHERE publication_year < 1900;
```

This updates the genre column to 'Classic' for all books published before 1900.

#### <a name="chapter4part2.3"></a>Chapter 4 - Part 2.3: Updating with Values from Another Table (Advanced)

In some cases, you might want to update values in one table based on data in another table. This often involves using a JOIN within the UPDATE statement.

**Example: Updating Book Prices Based on Author Popularity**

Let's imagine we have an authors table with a popularity_score column and a books table with a price column and an author_id column. We want to increase the price of books written by popular authors (those with a popularity_score above a certain threshold).

```sql
UPDATE books
SET price = price * 1.10 -- Increase price by 10%
WHERE author_id IN (SELECT author_id FROM authors WHERE popularity_score > 75);
```

This example uses a subquery (which will be covered in more detail in Module 6) to select the author_id of popular authors and then updates the price of books written by those authors. A more explicit JOIN syntax might also be supported by your specific database system:

```sql
UPDATE books
SET price = books.price * 1.10
FROM books
INNER JOIN authors ON books.author_id = authors.author_id
WHERE authors.popularity_score > 75;
```

#### <a name="chapter4part2.4"></a>Chapter 4 - Part 2.4: Important Considerations and Best Practices

- **Always Use a WHERE Clause**: As mentioned earlier, forgetting the WHERE clause can have disastrous consequences, updating all rows in your table unintentionally.

- **Test Your UPDATE Statements**: Before running an UPDATE statement on a production database, test it on a development or staging environment to ensure it behaves as expected.

- **Backup Your Data**: It's always a good practice to back up your data before performing any major data manipulation operations, including UPDATE statements. This allows you to restore your database to its previous state if something goes wrong. We will discuss the importance of backups and data recovery later in this module.

- **Understand Transactions**: For critical updates, use transactions to ensure data integrity. Transactions allow you to group multiple SQL statements into a single unit of work. If any statement within the transaction fails, the entire transaction is rolled back, preventing partial updates. We will cover transactions in detail later in this module.

- **Data Types**: Ensure that the values you are assigning to columns are compatible with the column's data type. Attempting to insert a string into an integer column, for example, will result in an error.

- **Null Values**: Be mindful of NULL values. You can update a column to NULL using SET column_name = NULL. Also, remember that comparing a column to NULL in the WHERE clause requires using IS NULL or IS NOT NULL.

- **Performance**: Updating large numbers of rows can be slow. Consider using indexes on the columns used in the WHERE clause to improve performance. We will discuss indexes in Module 7.

#### <a name="chapter4part3"></a>Chapter 4 - Part 3: Deleting Data with DELETE FROM

Deleting data from a database is a critical operation that requires careful consideration. The DELETE FROM statement in SQL allows you to remove specific rows from a table. Understanding how to use this statement effectively, along with its potential consequences, is essential for maintaining data integrity and ensuring the accuracy of your database. This lesson will cover the syntax of the DELETE FROM statement, how to use WHERE clauses to target specific rows, and the importance of understanding the impact of your deletions.

#### <a name="chapter4part3.1"></a>Chapter 4 - Part 3.1: The DELETE FROM Statement: Basic Syntax

The fundamental syntax for deleting data in SQL is as follows:

```sql
DELETE FROM table_name
WHERE condition;
```

- DELETE FROM: This clause specifies that you want to delete rows from a table.

- table_name: This is the name of the table from which you want to delete data.

- WHERE condition: This clause is crucial. It specifies the condition that determines which rows will be deleted. If you omit the WHERE clause, all rows in the table will be deleted.

Let's say we have an authors table in our "Online Bookstore" database with the following structure and data:


|author_id|	first_name|	last_name|
| :--------: | :--------: | :--------: |
|1|	Jane|	Austen|
|2|	Charles|	Dickens|
|3|	William|	Shakespeare|
|4|	Agatha|	Christie|

To delete the author with author_id = 3, you would use the following SQL statement:

```sql
DELETE FROM authors
WHERE author_id = 3;
```

After executing this statement, the authors table would look like this:

|author_id|	first_name|	last_name|
| :--------: | :--------: | :--------: |
|1|	Jane|	Austen|
|2|	Charles|	Dickens|
|4|	Agatha|	Christie|

#### <a name="chapter4part3.2"></a>Chapter 4 - Part 3.2: Using the WHERE Clause Effectively

The WHERE clause is the most important part of the DELETE FROM statement. It allows you to specify exactly which rows you want to remove. You can use various operators and conditions in the WHERE clause, just as you would in a SELECT statement (as covered in Module 2).

**Common Operators in WHERE Clauses**

- ```=```: Equal to
- ```>```: Greater than
- ```<```: Less than
- ```>=```: Greater than or equal to
- ```<=```: Less than or equal to
- ```<> or !=```: Not equal to
- ```LIKE```: Pattern matching (e.g., WHERE last_name LIKE 'A%')
- ```IN```: Checks if a value is in a list (e.g., WHERE author_id IN (1, 2))
- ```BETWEEN```: Checks if a value is within a range (e.g., WHERE author_id BETWEEN 1 AND 3)
- ```IS NULL```: Checks if a value is NULL
- ```IS NOT NULL```: Checks if a value is not NULL

**Combining Conditions with AND and OR**

You can combine multiple conditions in the WHERE clause using the AND and OR operators.

- ```AND```: Both conditions must be true for a row to be deleted.
- ```OR```: At least one of the conditions must be true for a row to be deleted.

Suppose we want to delete all authors whose first name is 'Jane' and last name is 'Austen'.

```sql
DELETE FROM authors
WHERE first_name = 'Jane' AND last_name = 'Austen';
```

Alternatively, if we want to delete all authors whose first name is 'Jane' or whose last name is 'Dickens', we would use:

```sql
DELETE FROM authors
WHERE first_name = 'Jane' OR last_name = 'Dickens';
```

**Subqueries in WHERE Clauses**

You can also use subqueries within the WHERE clause of a DELETE FROM statement. This allows you to delete rows based on the results of another query. We will cover subqueries in detail in Module 6, but here's a basic example:

Let's say we have a books table with a author_id column, and we want to delete all authors who have no books in the books table.

```sql
DELETE FROM authors
WHERE author_id NOT IN (SELECT DISTINCT author_id FROM books);
```

This statement first selects all distinct author_id values from the books table. Then, it deletes all rows from the authors table where the author_id is not in the list of author_id values returned by the subquery.

#### <a name="chapter4part3.3"></a>Chapter 4 - Part 3.3: The Importance of WHERE and the Dangers of Accidental Deletion

As mentioned earlier, omitting the WHERE clause in a DELETE FROM statement will delete all rows from the table. This is a destructive operation, and it's crucial to be extremely careful when using the DELETE FROM statement.

**Example of Accidental Deletion:**

```sql
DELETE FROM authors; -- This will delete all rows from the authors table!
```

To prevent accidental deletions, it's a good practice to:

- **Always start with a SELECT statement**: Before running a DELETE FROM statement, first write a SELECT statement with the same WHERE clause to verify that you are targeting the correct rows. For example:

```sql
SELECT * FROM authors WHERE author_id = 3; -- Verify the row to be deleted
DELETE FROM authors WHERE author_id = 3; -- Then, execute the DELETE statement
```

- **Use transactions**: Transactions allow you to group multiple SQL statements into a single unit of work. If any statement fails, you can roll back the entire transaction, undoing any changes made. We will cover transactions in more detail in the next lesson.

- **Backups**: Regularly back up your database so that you can restore it if you accidentally delete data. The importance of backups and data recovery will be discussed later in this module.

#### <a name="chapter4part4"></a>Chapter 4 - Part 4: Understanding Transactions: Ensuring Data Integrity

Transactions are a cornerstone of reliable database management, ensuring that data remains consistent and accurate even when multiple operations occur simultaneously or when unexpected errors arise. They provide a way to group a series of SQL statements into a single logical unit of work. This unit either completely succeeds, with all changes being permanently applied to the database, or completely fails, with all changes being rolled back, leaving the database in its original state. This "all or nothing" approach is crucial for maintaining data integrity, especially in complex applications where multiple tables and records are affected by a single user action. Without transactions, a failure in the middle of a series of operations could leave the database in an inconsistent state, leading to data corruption or incorrect results.

#### <a name="chapter4part4.1"></a>Chapter 4 - Part 4.1: Understanding the ACID Properties

Transactions are governed by a set of four key properties, often referred to as ACID:

- **Atomicity**: This property ensures that a transaction is treated as a single, indivisible unit of work. Either all the operations within the transaction are completed successfully, or none of them are. If any part of the transaction fails, the entire transaction is rolled back, and the database is left in its original state.

- **Consistency**: This property ensures that a transaction brings the database from one valid state to another. It enforces all defined rules, constraints, and integrity checks to maintain the correctness of the data. If a transaction violates any of these rules, it is rolled back, preventing the database from entering an invalid state.

- **Isolation**: This property ensures that concurrent transactions do not interfere with each other. Each transaction operates as if it were the only transaction running on the database, even though multiple transactions may be executing simultaneously. This prevents issues such as lost updates, dirty reads, and non-repeatable reads.

- **Durability**: This property ensures that once a transaction is committed, its changes are permanent and will survive even system failures such as power outages or crashes. The database system guarantees that the changes will be written to persistent storage and will be available even after a restart.

Let's illustrate these properties with examples:

**Atomicity**: Imagine transferring money between two accounts in our online bookstore database. The transaction involves two operations: debiting the amount from the sender's account and crediting the amount to the receiver's account. If the debit operation succeeds but the credit operation fails (e.g., due to insufficient funds in the receiver's account), the atomicity property ensures that the debit operation is also rolled back, preventing the sender from losing money without the receiver receiving it.

**Consistency**: Suppose we have a constraint in our Books table that the price column must always be a positive value. If a transaction attempts to update the price of a book to a negative value, the consistency property will cause the transaction to be rolled back, preventing the database from entering an inconsistent state where a book has a negative price.

**Isolation**: Consider two users simultaneously trying to update the quantity of a particular book in the Books table. Without proper isolation, one user's update might overwrite the other user's update, leading to a lost update. The isolation property ensures that each user's transaction operates as if it were the only one modifying the book's quantity, preventing this issue.

**Durability**: After a customer successfully places an order in our online bookstore, the transaction is committed, and the order details are written to the database. The durability property ensures that even if the server crashes immediately after the commit, the order details will still be available when the server restarts, preventing the loss of the customer's order.

#### <a name="chapter4part4.2"></a>Chapter 4 - Part 4.2: Managing Transactions in SQL

SQL provides a set of commands to manage transactions:

- ```START TRANSACTION (or BEGIN TRANSACTION)```: This command initiates a new transaction. All subsequent SQL statements will be considered part of this transaction until it is either committed or rolled back.

- ```COMMIT```: This command permanently saves all changes made during the transaction to the database. After a COMMIT command is executed, the changes are visible to other users and will survive system failures.

- ```ROLLBACK```: This command undoes all changes made during the transaction, reverting the database to its state before the transaction began. This is used to handle errors or to cancel a transaction that cannot be completed successfully.

Here's an example of how to use these commands in our online bookstore database to transfer money between two customer accounts:

```sql
START TRANSACTION;

-- Debit $50 from customer with ID 1
UPDATE Customers
SET balance = balance - 50
WHERE customer_id = 1;

-- Credit $50 to customer with ID 2
UPDATE Customers
SET balance = balance + 50
WHERE customer_id = 2;

-- Check if both updates were successful (e.g., by checking the number of affected rows)
-- If any error occurred, execute ROLLBACK; otherwise, execute COMMIT
COMMIT;
```

In this example, if either the debit or credit operation fails (e.g., due to insufficient funds in customer 1's account), we would execute a ROLLBACK command to undo the debit operation and prevent the transaction from completing.

#### <a name="chapter4part4.3"></a>Chapter 4 - Part 4.3: Implicit vs. Explicit Transactions

Most database systems support two modes of transaction management: implicit and explicit.

- **Explicit Transactions**: These are transactions that are explicitly started and ended using the START TRANSACTION, COMMIT, and ROLLBACK commands, as shown in the previous example. This gives the developer full control over the transaction boundaries.

- **Implicit Transactions**: In this mode, each SQL statement is treated as a separate transaction. The database system automatically starts a new transaction before each statement and either commits it if the statement succeeds or rolls it back if the statement fails. This mode is simpler to use but provides less control over transaction management.

The default transaction mode depends on the database system being used. Some systems default to implicit transactions, while others default to explicit transactions. It's important to understand the default mode of your database system and to use explicit transactions when you need to group multiple statements into a single logical unit of work.

#### <a name="chapter4part4.4"></a>Chapter 4 - Part 4.4: Savepoints: Rolling Back to a Specific Point

In some cases, you might want to roll back only a portion of a transaction, rather than the entire transaction. This can be achieved using savepoints. A savepoint is a marker within a transaction that allows you to roll back to a specific point in the transaction without undoing all the changes made so far.

The following commands are used to manage savepoints:

- ```SAVEPOINT savepoint_name```: This command creates a new savepoint with the specified name.

- ```ROLLBACK TO SAVEPOINT savepoint_name```: This command rolls back the transaction to the specified savepoint, undoing all changes made after the savepoint was created.

- ```RELEASE SAVEPOINT savepoint_name```: This command removes the specified savepoint. Once a savepoint is released, it can no longer be used to roll back the transaction.

Here's an example of how to use savepoints in our online bookstore database:

```sql
START TRANSACTION;

-- Update the quantity of a book
UPDATE Books
SET quantity = quantity - 1
WHERE book_id = 1;

-- Create a savepoint
SAVEPOINT quantity_updated;

-- Add a new order
INSERT INTO Orders (customer_id, book_id, quantity)
VALUES (1, 1, 1);

-- If any error occurs during the order insertion, roll back to the savepoint
-- This will undo the order insertion but keep the book quantity update
ROLLBACK TO SAVEPOINT quantity_updated;

-- Commit the transaction
COMMIT;
```

In this example, if the order insertion fails (e.g., due to an invalid customer ID), we roll back to the quantity_updated savepoint, which undoes the order insertion but keeps the book quantity update. This allows us to handle errors gracefully without losing all the changes made during the transaction.

#### <a name="chapter4part4.5"></a>Chapter 4 - Part 4.5: Concurrency Control and Isolation Levels

As mentioned earlier, the isolation property of transactions ensures that concurrent transactions do not interfere with each other. However, achieving perfect isolation can be expensive in terms of performance. Therefore, database systems provide different isolation levels that allow you to trade off isolation for performance.

The SQL standard defines four isolation levels:

- **Read Uncommitted**: This is the lowest isolation level. Transactions can read uncommitted changes made by other transactions. This level provides the best performance but offers the least isolation, as it is susceptible to dirty reads (reading uncommitted data that may later be rolled back).

- **Read Committed**: This level prevents dirty reads. Transactions can only read committed changes made by other transactions. However, it is still susceptible to non-repeatable reads (reading the same row multiple times within a transaction and getting different results due to changes made by other transactions) and phantom reads (reading a set of rows that satisfy a certain condition multiple times within a transaction and getting different results due to insertions or deletions made by other transactions).

- **Repeatable Read**: This level prevents dirty reads and non-repeatable reads. Transactions can read the same row multiple times within a transaction and get the same result. However, it is still susceptible to phantom reads.

- **Serializable**: This is the highest isolation level. It provides the strongest isolation, preventing dirty reads, non-repeatable reads, and phantom reads. Transactions operate as if they were the only transaction running on the database. However, this level provides the worst performance due to the increased overhead of maintaining strict isolation.

You can set the isolation level for a transaction using the ```SET TRANSACTION ISOLATION LEVEL``` command. For example:

```sql
SET TRANSACTION ISOLATION LEVEL SERIALIZABLE;
START TRANSACTION;

-- Perform database operations
...

COMMIT;
```

The default isolation level depends on the database system being used. It's important to understand the different isolation levels and to choose the appropriate level for your application based on its requirements for data integrity and performance.

#### <a name="chapter4part4.6"></a>Chapter 4 - Part 4.6: Practical Exercise: Implementing a Book Purchase Transaction

Let's create a practical exercise that simulates a book purchase transaction in our online bookstore database. This exercise will reinforce your understanding of transactions and the ACID properties.

**Scenario**: A customer wants to purchase a book from our online bookstore. The transaction involves the following steps:

- Check if the book is in stock (i.e., the quantity in the Books table is greater than 0).

- If the book is in stock, decrement the quantity in the Books table.

- Create a new order in the Orders table.

- Update the customer's order history.

**Instructions**:

- Write a SQL script that implements the book purchase transaction using explicit transactions.

- Include error handling to handle cases where the book is not in stock or the customer ID is invalid.

- Use savepoints to allow for partial rollbacks in case of errors.

- Test your script with different scenarios, such as:
  - A successful purchase
  - An attempt to purchase a book that is out of stock
  - An attempt to purchase with an invalid customer ID
 
Here's a possible solution:

```sql
START TRANSACTION;

-- Set the customer ID and book ID
SET @customer_id = 1;
SET @book_id = 1;
SET @quantity = 1;

-- Check if the book is in stock
SELECT @stock := quantity FROM Books WHERE book_id = @book_id;

IF @stock >= @quantity THEN
    -- Decrement the quantity in the Books table
    UPDATE Books
    SET quantity = quantity - @quantity
    WHERE book_id = @book_id;

    -- Create a savepoint
    SAVEPOINT book_quantity_updated;

    -- Add a new order in the Orders table
    INSERT INTO Orders (customer_id, book_id, quantity)
    VALUES (@customer_id, @book_id, @quantity);

    -- Update the customer's order history (assuming you have a CustomerOrderHistory table)
    -- INSERT INTO CustomerOrderHistory (customer_id, order_id) VALUES (@customer_id, LAST_INSERT_ID());

    -- Commit the transaction
    COMMIT;
    SELECT 'Purchase successful' AS message;
ELSE
    -- Rollback the transaction
    ROLLBACK;
    SELECT 'Book is out of stock' AS message;
END IF;
```

This exercise demonstrates how transactions can be used to ensure data integrity in a complex scenario involving multiple tables and operations. By using explicit transactions, error handling, and savepoints, you can create robust and reliable database applications.

#### <a name="chapter4part4.7"></a>Chapter 4 - Part 4.7: Real-World Applications

Transactions are used extensively in various real-world applications to ensure data integrity and consistency. Here are a few examples:

- **E-commerce Platforms**: When a customer places an order on an e-commerce platform, a transaction is used to ensure that the order is processed correctly. The transaction involves multiple steps, such as updating the inventory, creating an order record, processing the payment, and sending a confirmation email. If any of these steps fail, the entire transaction is rolled back, preventing inconsistencies in the data.

- **Banking Systems**: Transactions are crucial in banking systems to ensure the accuracy of financial transactions. When transferring money between accounts, a transaction is used to ensure that the money is debited from one account and credited to another account. If any error occurs during the transfer, the transaction is rolled back, preventing the loss of funds.

- **Airline Reservation Systems**: When booking a flight, a transaction is used to ensure that the seat is reserved correctly. The transaction involves multiple steps, such as checking the availability of seats, reserving the seat, processing the payment, and issuing the ticket. If any of these steps fail, the entire transaction is rolled back, preventing overbooking or incorrect reservations.

Transactions are a fundamental concept in database management, providing a mechanism to ensure data integrity and consistency in complex applications. By understanding the ACID properties and the SQL commands for managing transactions, you can build robust and reliable database applications that can handle concurrent operations and unexpected errors gracefully.

#### <a name="chapter4part5"></a>Chapter 4 - Part 5: Importance of Backups and Data Recovery

Backups and data recovery are critical aspects of database management. Data loss can occur due to various reasons, including hardware failures, software bugs, human errors, or even malicious attacks. Without a proper backup and recovery strategy, organizations risk losing valuable data, which can lead to significant financial losses, reputational damage, and legal liabilities. This lesson will cover the importance of backups, different backup strategies, and the process of data recovery, ensuring that you understand how to protect your data and restore it in case of a disaster.

#### <a name="chapter4part5.1"></a>Chapter 4 - Part 5.1: Why Backups are Essential

Backups are copies of your database that are stored separately from the original data. They serve as a safety net, allowing you to restore your database to a previous state in case of data loss or corruption. Here's why backups are essential:

- **Protection against Data Loss**: Hardware failures, such as hard drive crashes, can lead to irreversible data loss. Backups ensure that you can recover your data even if the physical storage is damaged.

- **Recovery from Human Errors**: Accidental deletion of tables or incorrect updates can corrupt your data. Backups allow you to revert to a clean state before the error occurred.

- **Mitigation of Software Bugs**: Software bugs in the database management system or related applications can cause data corruption. Backups provide a way to restore your database to a stable state.

- **Defense against Malicious Attacks**: Hackers may attempt to delete or corrupt your data. Backups enable you to recover from such attacks and minimize the impact on your business.

- **Compliance with Regulations**: Many industries are subject to regulations that require them to maintain backups of their data for a certain period. Backups help you comply with these regulations and avoid penalties.

**Example**:

Imagine our "Online Bookstore" database. A critical table containing customer order information is accidentally dropped by a developer during a maintenance operation. Without a recent backup, all order history would be permanently lost, impacting order fulfillment, customer service, and financial reporting. With a backup, the database administrator can restore the database to the point before the table was dropped, minimizing the disruption.

#### <a name="chapter4part5.2"></a>Chapter 4 - Part 5.2: Types of Backups

There are several types of backups, each with its own advantages and disadvantages. The choice of backup strategy depends on factors such as the size of your database, the frequency of data changes, and the recovery time objective (RTO) and recovery point objective (RPO) of your organization.

**Full Backups**

A full backup copies the entire database, including all tables, indexes, and other database objects.

- **Advantages**: Simple to implement and provides a complete copy of the database.
- **Disadvantages**: Can be time-consuming and requires a large amount of storage space.

**Example**:

A full backup of the "Online Bookstore" database would include all tables (e.g., books, customers, orders), indexes, stored procedures, and other database objects. This ensures that you have a complete snapshot of the database at a specific point in time.

**Differential Backups**

A differential backup copies only the data that has changed since the last full backup.

- **Advantages**: Faster than full backups and requires less storage space.
- **Disadvantages**: Recovery requires both the last full backup and the last differential backup. The size of the differential backup grows over time until the next full backup.

**Example**:

After performing a full backup of the "Online Bookstore" database on Sunday, a differential backup on Monday would only copy the changes made since Sunday. On Tuesday, the differential backup would include all changes made since Sunday, including those from Monday.

**Incremental Backups**

An incremental backup copies only the data that has changed since the last backup, whether it was a full backup or an incremental backup.

- **Advantages**: Fastest backup method and requires the least storage space.
- **Disadvantages**: Recovery requires the last full backup and all subsequent incremental backups. This can make the recovery process more complex and time-consuming.

**Example**:

After performing a full backup of the "Online Bookstore" database on Sunday, an incremental backup on Monday would only copy the changes made since Sunday. An incremental backup on Tuesday would only copy the changes made since Monday. To restore the database to Tuesday's state, you would need the full backup from Sunday and both incremental backups from Monday and Tuesday.


|Backup Type | Backup Time |Storage Space|	Recovery Time|	Complexity|
| :--------: | :--------: | :--------: |  :--------: |  :--------: |
|Full|	High|	High|	Low|	Low|
|Differential|	Medium|	Medium|	Medium|	Medium|
|Incremental|	Low|	Low|	High|	High|

**Transaction Log Backups**

Transaction log backups are specific to database systems that use transaction logs (most do). These logs record every transaction or change made to the database. Backing up the transaction log allows you to restore the database to a specific point in time.

- **Advantages**: Enables point-in-time recovery, minimizing data loss.
- **Disadvantages**: Requires a database system that supports transaction logging. Recovery process can be complex.

**Example**:

In the "Online Bookstore" database, every order placed, every customer record updated, and every book added to the inventory is recorded in the transaction log. By backing up the transaction log regularly (e.g., every 15 minutes), you can restore the database to a point just before a data corruption event, potentially saving hours of work.

#### <a name="chapter4part5.3"></a>Chapter 4 - Part 5.3: Backup Strategies

A backup strategy defines how often you perform backups and what type of backups you use. A well-designed backup strategy should balance the need for data protection with the cost of storage and the impact on database performance.

**Full Backup Strategy**

The simplest backup strategy is to perform a full backup of the database on a regular basis, such as daily or weekly.

- **Advantages**: Easy to implement and provides a complete copy of the database.
- **Disadvantages**: Can be time-consuming and requires a large amount of storage space.

**When to Use**: Suitable for small databases with infrequent data changes.

**Incremental Backup Strategy**

An incremental backup strategy involves performing a full backup on a less frequent basis (e.g., weekly) and then performing incremental backups on a more frequent basis (e.g., daily).

- **Advantages**: Faster backups and requires less storage space than full backups.
- **Disadvantages**: Recovery can be more complex and time-consuming.

**When to Use**: Suitable for medium-sized databases with moderate data changes.

**Differential Backup Strategy**

A differential backup strategy involves performing a full backup on a less frequent basis (e.g., weekly) and then performing differential backups on a more frequent basis (e.g., daily).

- **Advantages**: Faster backups and simpler recovery than incremental backups.
- **Disadvantages**: Differential backups grow over time, requiring more storage space.

**When to Use**: Suitable for medium-sized databases with moderate data changes.

**Combination Strategy**

A combination strategy involves using a combination of full, differential, and incremental backups to optimize backup and recovery performance.

- **Advantages**: Provides the best balance between backup speed, storage space, and recovery time.
- **Disadvantages**: More complex to implement and manage.

**Example**:

A common combination strategy is to perform a full backup weekly, differential backups daily, and transaction log backups every hour. This strategy provides a good balance between data protection and performance.

**When to Use**: Suitable for large databases with frequent data changes.

#### <a name="chapter4part5.4"></a>Chapter 4 - Part 5.4: Data Recovery Process

Data recovery is the process of restoring your database from a backup. The recovery process depends on the type of backup you are using and the nature of the data loss event.

**Recovery from a Full Backup**

To recover from a full backup, simply restore the backup to a new database or overwrite the existing database.

**Steps**:

- Identify the latest full backup.
- Restore the backup to a new or existing database.
- Verify that the data is consistent and complete.

**Example**:

If the "Online Bookstore" database is corrupted due to a hardware failure, you can restore the latest full backup to a new server. This will bring the database back to the state it was in when the backup was created.

**Recovery from a Differential Backup**

To recover from a differential backup, first restore the last full backup, and then restore the last differential backup.

**Steps**:

- Identify the latest full backup and the latest differential backup.
- Restore the full backup to a new or existing database.
- Restore the differential backup on top of the full backup.
- Verify that the data is consistent and complete.

**Example**:

If the "Online Bookstore" database is corrupted on Wednesday, and you have a full backup from Sunday and a differential backup from Tuesday, you would first restore the full backup from Sunday, and then restore the differential backup from Tuesday.

**Recovery from an Incremental Backup**

To recover from an incremental backup, first restore the last full backup, and then restore all subsequent incremental backups in the order they were created.

**Steps**:

- Identify the latest full backup and all subsequent incremental backups.
- Restore the full backup to a new or existing database.
- Restore each incremental backup in the order they were created, on top of the previous backup.
- Verify that the data is consistent and complete.

**Example**:

If the "Online Bookstore" database is corrupted on Thursday, and you have a full backup from Sunday and incremental backups from Monday, Tuesday, and Wednesday, you would first restore the full backup from Sunday, and then restore the incremental backups from Monday, Tuesday, and Wednesday in that order.

**Point-in-Time Recovery**

Point-in-time recovery allows you to restore the database to a specific point in time using transaction log backups. This is useful for recovering from human errors or application bugs that corrupt data at a specific point in time.

**Steps**:

- Restore the latest full backup.
- Restore the subsequent differential or incremental backups, if any.
- Apply the transaction log backups up to the desired point in time.

**Example**:

Suppose a developer accidentally deletes a large number of customer records from the "Online Bookstore" database at 2:00 PM. If you have transaction log backups, you can restore the database to the state it was in at 1:59 PM, just before the deletion occurred.

#### <a name="chapter4part5.5"></a>Chapter 4 - Part 5.5: Testing Your Backups

It's crucial to regularly test your backups to ensure that they are working correctly and that you can recover your data in a timely manner. Testing should include:

- **Verifying Backup Integrity**: Check that the backup files are not corrupted and can be read successfully.

- **Performing Test Restores**: Restore the backups to a test environment and verify that the data is consistent and complete.

- **Measuring Recovery Time**: Track the time it takes to restore the backups and identify any bottlenecks in the recovery process.

**Example**:

Every month, the IT team at the "Online Bookstore" performs a test restore of the database to a separate test server. They then run a series of queries to verify that the data is consistent and that all critical functions are working correctly. This helps them identify and resolve any issues with the backup and recovery process before a real disaster occurs.

#### <a name="chapter4part5.6"></a>Chapter 4 - Part 5.6: Real-World Application

Consider a large e-commerce company that relies on its database to store customer information, order details, and product inventory. The company implements a comprehensive backup strategy that includes weekly full backups, daily differential backups, and hourly transaction log backups. They also regularly test their backups to ensure that they can recover their data in case of a disaster.

One day, a critical server fails, causing the database to become unavailable. The IT team quickly restores the latest full backup, followed by the latest differential backup, and then applies the transaction log backups up to the point of failure. Within a few hours, the database is back online, and the company is able to resume normal operations with minimal data loss.

Without a proper backup and recovery strategy, the company could have lost valuable data, resulting in significant financial losses and reputational damage. The investment in backups and testing proved to be invaluable in protecting the company's assets and ensuring business continuity.

In another scenario, a hospital maintains patient records in a database. Due to regulatory requirements (like HIPAA), they must ensure data availability and integrity. They employ a combination of full weekly backups, daily incremental backups, and continuous transaction log backups. They also have a disaster recovery plan that includes failover to a secondary data center. This comprehensive approach ensures they can quickly recover from any data loss event and maintain compliance.

Backups and data recovery are essential components of database management. By understanding the different types of backups, designing an appropriate backup strategy, and regularly testing your backups, you can protect your data and ensure business continuity in the face of unexpected events. Remember to consider your organization's specific needs and requirements when developing your backup and recovery plan.

## <a name="chapter5"></a>Chapter 5: Aggregate Functions and Grouping

#### <a name="chapter5part1"></a>Chapter 5 - Part 1: Introduction to Aggregate Functions: COUNT, SUM, AVG, MIN, MAX

Aggregate functions are essential tools in SQL for summarizing and analyzing data. They allow you to perform calculations on multiple rows of a table and return a single aggregated value. This lesson will introduce you to five fundamental aggregate functions: COUNT, SUM, AVG, MIN, and MAX. Understanding these functions is crucial for extracting meaningful insights from your data and forms the foundation for more advanced data analysis techniques in SQL.

#### <a name="chapter5part1.1"></a>Chapter 5 - Part 1.1: Understanding Aggregate Functions

Aggregate functions operate on a set of rows and return a single value. They are commonly used with the GROUP BY clause (which we'll cover in the next lesson) to calculate aggregates for different groups within your data. However, they can also be used without GROUP BY to calculate aggregates for the entire table.

Here's a breakdown of the five key aggregate functions:

- **COUNT()**: Counts the number of rows or non-null values in a specified column.
- **SUM()**: Calculates the sum of numeric values in a specified column.
- **AVG()**: Calculates the average of numeric values in a specified column.
- **MIN()**: Finds the minimum value in a specified column.
- **MAX()**: Finds the maximum value in a specified column.

#### <a name="chapter5part1.2"></a>Chapter 5 - Part 1.2: COUNT() Function

The COUNT() function is used to count the number of rows in a table or the number of non-null values in a specific column. It has two main forms:

- **COUNT(*)**: Counts all rows in a table, regardless of whether they contain null values.
- **COUNT(column_name)**: Counts the number of rows where the specified column has a non-null value.

**Examples of COUNT()**

Let's use our "Online Bookstore" database to illustrate the COUNT() function. Suppose we want to know the total number of books in the books table.

```sql
SELECT COUNT(*) AS total_books
FROM books;
```

This query will return a single row with a column named total_books containing the total number of books in the table.

Now, let's say we want to count the number of books that have a listed price (i.e., the price column is not null).

```sql
SELECT COUNT(price) AS books_with_price
FROM books;
```

This query will return the number of books where the price column is not null. If some books have a missing price, this number will be different from the total number of books.

**COUNT(DISTINCT column_name)**

The COUNT() function can also be used with the DISTINCT keyword to count the number of unique values in a column. For example, if we want to know the number of unique authors in our books table, we can use the following query:

```sql
SELECT COUNT(DISTINCT author) AS unique_authors
FROM books;
```

This query will return the number of distinct authors in the books table, ignoring any duplicate author names.

#### <a name="chapter5part1.3"></a>Chapter 5 - Part 1.3: SUM() Function

The SUM() function calculates the sum of numeric values in a specified column. It ignores null values.

**Examples of SUM()**

Suppose we want to calculate the total price of all books in our books table.

```sql
SELECT SUM(price) AS total_price
FROM books;
```

This query will return the sum of all values in the price column, representing the total value of our inventory.

If we want to calculate the total revenue from all orders in the orders table (assuming we have a total_amount column), we can use the following query:

```sql
SELECT SUM(total_amount) AS total_revenue
FROM orders;
```

This query will return the total revenue generated from all orders.

**Handling NULL Values in SUM()**

It's important to remember that SUM() ignores null values. If a column contains null values, they will not be included in the sum. If all values in the column are NULL, SUM() will return NULL.

#### <a name="chapter5part1.4"></a>Chapter 5 - Part 1.4: AVG() Function

The AVG() function calculates the average of numeric values in a specified column. Like SUM(), it ignores null values.

**Examples of AVG()**

To calculate the average price of books in our books table:

```sql
SELECT AVG(price) AS average_price
FROM books;
```

This query will return the average price of all books in the table.

If we want to calculate the average rating of books (assuming we have a rating column), we can use the following query:

```sql
SELECT AVG(rating) AS average_rating
FROM books;
```

This query will return the average rating of all books.

**Handling NULL Values in AVG()**

AVG() also ignores null values. The average is calculated based on the non-null values in the column. If all values in the column are NULL, AVG() will return NULL.

#### <a name="chapter5part1.5"></a>Chapter 5 - Part 1.5: MIN() and MAX() Functions

The MIN() and MAX() functions find the minimum and maximum values, respectively, in a specified column. These functions can be used with numeric, string, and date/time data types.

**Examples of MIN() and MAX()**

To find the lowest price of a book in our books table:

```sql
SELECT MIN(price) AS lowest_price
FROM books;
```

This query will return the minimum value in the price column.

To find the highest price of a book:

```sql
SELECT MAX(price) AS highest_price
FROM books;
```

This query will return the maximum value in the price column.

We can also use MIN() and MAX() with string data types. For example, to find the alphabetically first and last author names:

```sql
SELECT MIN(author) AS first_author, MAX(author) AS last_author
FROM books;
```

This query will return the author name that comes first alphabetically (first_author) and the author name that comes last alphabetically (last_author).

#### <a name="chapter5part1.6"></a>Chapter 5 - Part 1.6: Combining Aggregate Functions

You can combine multiple aggregate functions in a single query to get a more comprehensive overview of your data. For example, to get the total number of books, the average price, the lowest price, and the highest price in a single query:

```sql
SELECT
    COUNT(*) AS total_books,
    AVG(price) AS average_price,
    MIN(price) AS lowest_price,
    MAX(price) AS highest_price
FROM books;
```

This query will return a single row with four columns, each representing a different aggregate value.

#### <a name="chapter5part1.7"></a>Chapter 5 - Part 1.7: Real-World Application

Consider an e-commerce company that wants to analyze its sales data. They can use aggregate functions to answer questions like:

- What is the total revenue generated in the last month? (SUM())
- What is the average order value? (AVG())
- What is the most popular product? (COUNT(), combined with GROUP BY which we will learn in the next lesson)
- What is the highest and lowest order value? (MIN() and MAX())

These insights can help the company make informed decisions about pricing, marketing, and inventory management.

Another example is a social media platform. They can use aggregate functions to:

- Count the total number of users. (COUNT())
- Calculate the average number of posts per user. (AVG(), combined with GROUP BY)
- Find the user with the most followers. (MAX(), combined with GROUP BY)
- Find the user with the least followers. (MIN(), combined with GROUP BY)

These metrics can help the platform understand user engagement and identify areas for improvement.

#### <a name="chapter5part2"></a>Chapter 5 - Part 2: Grouping Data with GROUP BY: Analyzing Data Subsets

Grouping data is a crucial step in data analysis, allowing you to summarize and understand trends within specific subsets of your data. The GROUP BY clause in SQL enables you to categorize rows based on one or more columns, paving the way for applying aggregate functions to each group. This lesson will delve into the mechanics of GROUP BY, demonstrating how to effectively analyze data subsets and extract meaningful insights.

#### <a name="chapter5part2.1"></a>Chapter 5 - Part 2.1: Understanding the GROUP BY Clause

The GROUP BY clause is used in conjunction with aggregate functions (like COUNT, SUM, AVG, MIN, and MAX) to group rows that have the same values in one or more columns into a summary row. The basic syntax is as follows:

```sql
SELECT column1, column2, aggregate_function(column3)
FROM table_name
WHERE condition
GROUP BY column1, column2
ORDER BY column1, column2;
```

- column1, column2: These are the columns by which you want to group the data.

- aggregate_function(column3): This is the aggregate function you want to apply to the grouped data.

- table_name: The name of the table you are querying.

- WHERE condition: An optional clause to filter rows before grouping.

- ORDER BY column1, column2: An optional clause to sort the results after grouping.

**Key Principles:**

- Grouping Logic: GROUP BY combines rows with identical values in the specified columns into groups.

- Aggregate Functions: Aggregate functions operate on these groups, producing a single value for each group.

- Non-Aggregated Columns: Any column in the SELECT list that is not an aggregate function must be included in the GROUP BY clause.

- WHERE vs. GROUP BY: The WHERE clause filters rows before grouping, while the HAVING clause (covered in the next lesson) filters groups after aggregation.

#### <a name="chapter5part2.2"></a>Chapter 5 - Part 2.2: Practical Examples Using the Bookstore Database

Let's continue using the "Online Bookstore" database to illustrate the GROUP BY clause. Assume we have a table called Orders with the following structure:

|OrderID|	CustomerID|	BookID|	OrderDate|	Quantity|	Price|
| :--------: | :--------: | :--------: |  :--------: |  :--------: | :--------: |
|1|	101|	201|	2023-01-15|	2|	25.00|
|2|	102|	202|	2023-01-20|	1|	15.00|
|3|	101|	203|	2023-01-25|	3|	30.00|
|4|	103|	201|	2023-02-01|	1|	25.00|
|5|	102|	202|	2023-02-10|	2|	15.00|
|6|	101|	201|	2023-02-15|	1|	25.00|
|7|	103|	203|	2023-02-20|	2|	30.00|

**Example 1: Counting Orders per Customer**

To find the number of orders placed by each customer, we can use the following query:

```sql
SELECT CustomerID, COUNT(OrderID) AS NumberOfOrders
FROM Orders
GROUP BY CustomerID;
```

This query groups the rows in the Orders table by CustomerID. For each unique CustomerID, the COUNT(OrderID) function counts the number of orders associated with that customer. The result will be a table showing each customer's ID and the corresponding number of orders they placed.

**Example 2: Calculating Total Quantity Sold per Book**

To determine the total quantity of each book sold, we can use the following query:

```sql
SELECT BookID, SUM(Quantity) AS TotalQuantitySold
FROM Orders
GROUP BY BookID;
```

This query groups the rows by BookID. For each unique BookID, the SUM(Quantity) function calculates the total quantity sold for that book. The result will show each book's ID and the total quantity sold.

**Example 3: Finding the Average Order Price per Customer**

To calculate the average order price for each customer, we can use the following query:

```sql
SELECT CustomerID, AVG(Price) AS AverageOrderPrice
FROM Orders
GROUP BY CustomerID;
```

This query groups the rows by CustomerID. For each unique CustomerID, the AVG(Price) function calculates the average price of orders placed by that customer.

**Example 4: Combining WHERE and GROUP BY**

Suppose we want to find the number of orders placed by each customer only for orders placed in January 2023. We can combine the WHERE clause with the GROUP BY clause:

```sql
SELECT CustomerID, COUNT(OrderID) AS NumberOfOrders
FROM Orders
WHERE OrderDate BETWEEN '2023-01-01' AND '2023-01-31'
GROUP BY CustomerID;
```

The WHERE clause filters the rows to include only orders placed in January 2023 before the grouping occurs. Then, the GROUP BY clause groups the filtered rows by CustomerID, and the COUNT(OrderID) function counts the number of orders for each customer in that month.

**Example 5: Grouping by Multiple Columns**

You can group by multiple columns to create more granular groupings. For example, to find the number of orders for each book placed by each customer, you can use the following query:

```sql
SELECT CustomerID, BookID, COUNT(OrderID) AS NumberOfOrders
FROM Orders
GROUP BY CustomerID, BookID
ORDER BY CustomerID, BookID;
```

This query groups the rows by both CustomerID and BookID. The result will show each unique combination of customer and book, along with the number of orders for that combination. The ORDER BY clause sorts the results first by CustomerID and then by BookID for better readability.

#### <a name="chapter5part3"></a>Chapter 5 - Part 3: Filtering Groups with HAVING: Applying Conditions to Aggregated Data

Filtering groups with aggregated data is a crucial step in SQL analysis, allowing you to focus on subsets of your data that meet specific criteria after aggregation. The HAVING clause is the key to achieving this, acting as a WHERE clause for groups. Understanding how to use HAVING effectively unlocks more sophisticated data insights and reporting capabilities.

#### <a name="chapter5part3.1"></a>Chapter 5 - Part 3.1: Understanding the HAVING Clause

The HAVING clause is used in SQL to filter the results of a GROUP BY query. It allows you to specify conditions that aggregated group must meet to be included in the final result set. Think of it as a WHERE clause that operates on groups rather than individual rows.

**Syntax**

The basic syntax of the HAVING clause is as follows:

```sql
SELECT column1, column2, aggregate_function(column3)
FROM table_name
WHERE condition -- Optional: Filters rows *before* grouping
GROUP BY column1, column2
HAVING condition_on_aggregate; -- Filters groups *after* grouping
```

- SELECT: Specifies the columns to retrieve, including aggregated values.
- FROM: Specifies the table to retrieve data from.
- WHERE: (Optional) Filters rows before the grouping occurs. This is important for performance, as it reduces the amount of data that needs to be grouped.
- GROUP BY: Specifies the columns to group the rows by.
- HAVING: Specifies the condition that groups must satisfy to be included in the result. This condition typically involves aggregate functions.

**Key Differences Between WHERE and HAVING**

It's essential to understand the difference between the WHERE and HAVING clauses:

|Feature|	WHERE Clause|	HAVING Clause|
| :--------: | :--------: | :--------: |
|Filtering|	Filters individual rows.|	Filters groups of rows (after aggregation).|
|Usage|	Used before the GROUP BY clause.|	Used after the GROUP BY clause.|
|Conditions|	Can use any column in the table.|	Typically uses aggregate functions.|
|Performance|	Filters data early, improving performance.|	Filters data later, after aggregation.|

**Example:**

Imagine you want to find all departments in a company that have an average salary greater than $60,000.

- WHERE would be used to filter individual employees based on their salary before grouping them into departments.
- HAVING would be used to filter the grouped departments based on the average salary calculated for each department.

**When to Use HAVING**

Use the HAVING clause when you need to filter based on the result of an aggregate function. If you can filter rows before grouping using a WHERE clause, that's generally more efficient.

#### <a name="chapter5part3.2"></a>Chapter 5 - Part 3.2: Practical Examples Using the Bookstore Database

Let's apply the HAVING clause to our "Online Bookstore" database. Assume we have the following tables:

- Books: book_id, title, author_id, genre, price
- Authors: author_id, author_name
- Orders: order_id, book_id, quantity, order_date

**Example 1: Finding Genres with Average Price Above a Threshold**

Suppose we want to find all book genres where the average price of books in that genre is greater than $25.

```sql
SELECT genre, AVG(price) AS average_price
FROM Books
GROUP BY genre
HAVING AVG(price) > 25;
```

**Explanation:**

- SELECT genre, AVG(price) AS average_price: Selects the genre and calculates the average price, aliasing it as average_price.
- FROM Books: Specifies the Books table.
- GROUP BY genre: Groups the books by genre.
- HAVING AVG(price) > 25: Filters the groups, including only those where the average price is greater than $25.

**Example 2: Finding Authors with More Than Two Books**

Let's find all authors who have written more than two books in our bookstore.

```sql
SELECT Authors.author_name, COUNT(Books.book_id) AS book_count
FROM Authors
JOIN Books ON Authors.author_id = Books.author_id
GROUP BY Authors.author_name
HAVING COUNT(Books.book_id) > 2;
```

**Explanation:**

- SELECT Authors.author_name, COUNT(Books.book_id) AS book_count: Selects the author's name and counts the number of books written by each author, aliasing it as book_count.
- FROM Authors JOIN Books ON Authors.author_id = Books.author_id: Joins the Authors and Books tables on the author_id column.
- GROUP BY Authors.author_name: Groups the results by author name.
- HAVING COUNT(Books.book_id) > 2: Filters the groups, including only those authors who have written more than two books.

**Example 3: Combining WHERE and HAVING**

Now, let's combine WHERE and HAVING. Suppose we want to find genres (excluding 'Fiction') where the average book price is greater than $20.

```sql
SELECT genre, AVG(price) AS average_price
FROM Books
WHERE genre <> 'Fiction'
GROUP BY genre
HAVING AVG(price) > 20;
```

**Explanation:**

- SELECT genre, AVG(price) AS average_price: Selects the genre and calculates the average price.
- FROM Books: Specifies the Books table.
- WHERE genre <> 'Fiction': Filters the rows before grouping, excluding books in the 'Fiction' genre.
- GROUP BY genre: Groups the books by genre.
- HAVING AVG(price) > 20: Filters the groups, including only those where the average price is greater than $20.

**Example 4: Using Multiple Conditions in HAVING**

You can also use multiple conditions in the HAVING clause using AND and OR operators. For example, let's find genres where the average price is greater than $20 and the number of books is greater than 5.

```sql
SELECT genre, AVG(price) AS average_price, COUNT(*) AS book_count
FROM Books
GROUP BY genre
HAVING AVG(price) > 20 AND COUNT(*) > 5;
```

**Explanation:**

- SELECT genre, AVG(price) AS average_price, COUNT(*) AS book_count: Selects the genre, calculates the average price, and counts the number of books in each genre.
- FROM Books: Specifies the Books table.
- GROUP BY genre: Groups the books by genre.
- HAVING AVG(price) > 20 AND COUNT(*) > 5: Filters the groups, including only those where the average price is greater than $20 and the number of books is greater than 5.

#### <a name="chapter5part4"></a>Chapter 5 - Part 4: Combining Aggregate Functions and Joins

Combining aggregate functions with joins allows you to perform complex data analysis by summarizing information from multiple related tables. This is a powerful technique for gaining insights into your data and answering business questions that would be difficult or impossible to answer using only single-table queries. By combining these two concepts, you can calculate aggregates across related data, providing a more comprehensive view of your information.

#### <a name="chapter5part4.1"></a>Chapter 5 - Part 4.1: Understanding the Synergy of Aggregate Functions and Joins

Aggregate functions (like COUNT, SUM, AVG, MIN, and MAX) operate on a set of values to return a single summary value. Joins, on the other hand, combine rows from two or more tables based on a related column. When used together, you can group data from multiple tables based on a common attribute and then apply aggregate functions to those groups.

**How Joins Prepare Data for Aggregation**

Joins are crucial for bringing together related data that resides in different tables. Before you can aggregate data across multiple tables, you need to use a join to combine the relevant rows into a single result set. This combined result set then becomes the input for your aggregate functions.

For example, in our online bookstore database, we might want to find the total sales for each author. The books table contains information about each book, including the author's ID, and the sales table contains information about each sale, including the book's ID and the sale amount. To calculate the total sales for each author, we need to join these two tables on their respective ID columns.

**The Role of GROUP BY in Combined Queries**

The GROUP BY clause is essential when using aggregate functions with joins. It allows you to group the joined data based on one or more columns, and then apply the aggregate function to each group. Without GROUP BY, the aggregate function would operate on the entire joined result set, returning a single summary value for all rows.

Continuing with the bookstore example, after joining the books and sales tables, we would use GROUP BY to group the results by author ID. This would create separate groups for each author, and then we could use the SUM function to calculate the total sales for each author group.

#### <a name="chapter5part4.2"></a>Chapter 5 - Part 4.2: Practical Examples in the Bookstore Database

Let's explore some practical examples of combining aggregate functions and joins using our online bookstore database.

**Example 1: Total Sales per Author**

This query calculates the total sales for each author by joining the books and sales tables and grouping the results by author ID.

```sql
SELECT
    b.author_id,
    a.author_name,
    SUM(s.sale_amount) AS total_sales
FROM
    sales s
JOIN
    books b ON s.book_id = b.book_id
JOIN
    authors a ON b.author_id = a.author_id
GROUP BY
    b.author_id, a.author_name
ORDER BY
    total_sales DESC;
```

**Explanation:**

- SELECT b.author_id, a.author_name, SUM(s.sale_amount) AS total_sales: This selects the author ID, author name, and the sum of the sale amounts (aliased as total_sales).

- FROM sales s JOIN books b ON s.book_id = b.book_id JOIN authors a ON b.author_id = a.author_id: This joins the sales, books, and authors tables based on the book_id and author_id columns. This ensures that we're combining sales data with the corresponding book and author information.

- GROUP BY b.author_id, a.author_name: This groups the results by author ID and author name, so the SUM function calculates the total sales for each author.

- ORDER BY total_sales DESC: This sorts the results in descending order of total sales, so the author with the highest sales appears first.

**Example 2: Average Rating of Books by Genre**

This query calculates the average rating of books for each genre by joining the books and genres tables and grouping the results by genre ID.

```sql
SELECT
    g.genre_name,
    AVG(b.rating) AS average_rating
FROM
    books b
JOIN
    genres g ON b.genre_id = g.genre_id
GROUP BY
    g.genre_name
ORDER BY
    average_rating DESC;
```

**Explanation:**

- SELECT g.genre_name, AVG(b.rating) AS average_rating: This selects the genre name and the average rating of books in that genre (aliased as average_rating).

- FROM books b JOIN genres g ON b.genre_id = g.genre_id: This joins the books and genres tables based on the genre_id column.

- GROUP BY g.genre_name: This groups the results by genre name, so the AVG function calculates the average rating for each genre.

- ORDER BY average_rating DESC: This sorts the results in descending order of average rating.

**Example 3: Number of Books Sold per Publisher**

This query calculates the number of books sold for each publisher by joining the books, sales, and publishers tables and grouping the results by publisher ID.

```sql
SELECT
    p.publisher_name,
    COUNT(s.book_id) AS books_sold
FROM
    sales s
JOIN
    books b ON s.book_id = b.book_id
JOIN
    publishers p ON b.publisher_id = p.publisher_id
GROUP BY
    p.publisher_name
ORDER BY
    books_sold DESC;
```

**Explanation:**

- SELECT p.publisher_name, COUNT(s.book_id) AS books_sold: This selects the publisher name and the count of book IDs (aliased as books_sold). COUNT(s.book_id) counts the number of sales records, which corresponds to the number of books sold.

- FROM sales s JOIN books b ON s.book_id = b.book_id JOIN publishers p ON b.publisher_id = p.publisher_id: This joins the sales, books, and publishers tables based on the book_id and publisher_id columns.

- GROUP BY p.publisher_name: This groups the results by publisher name, so the COUNT function counts the number of books sold for each publisher.

- ORDER BY books_sold DESC: This sorts the results in descending order of books sold.

#### <a name="chapter5part4.3"></a>Chapter 5 - Part 4.3: Filtering Groups with HAVING

Just as the WHERE clause filters individual rows, the HAVING clause filters groups created by the GROUP BY clause. HAVING is used to filter based on aggregate function results.

**Example: Authors with Total Sales Above a Threshold**

Let's say we want to find all authors whose total sales exceed $10,000. We can use the HAVING clause to filter the results of our "Total Sales per Author" query.

```sql
SELECT
    b.author_id,
    a.author_name,
    SUM(s.sale_amount) AS total_sales
FROM
    sales s
JOIN
    books b ON s.book_id = b.book_id
JOIN
    authors a ON b.author_id = a.author_id
GROUP BY
    b.author_id, a.author_name
HAVING
    SUM(s.sale_amount) > 10000
ORDER BY
    total_sales DESC;
```

**Explanation:**

The query is the same as the "Total Sales per Author" query, but with the addition of the HAVING clause:

- HAVING SUM(s.sale_amount) > 10000: This filters the groups, only including those where the sum of the sale amounts is greater than 10000.

Only authors whose total sales are greater than $10,000 will be included in the final result.

#### <a name="chapter5part5"></a>Chapter 5 - Part 5: Practical Exercise: Analyzing Sales Data in the Bookstore Database

Aggregate functions are essential tools in SQL for summarizing and analyzing data. They allow you to perform calculations on multiple rows and return a single aggregated value. This lesson will focus on using aggregate functions in conjunction with the GROUP BY and HAVING clauses to gain deeper insights from the "Online Bookstore" database. We'll explore how to calculate totals, averages, minimums, maximums, and counts for different groups of data, enabling you to answer complex business questions about sales performance, customer behavior, and inventory management.

#### <a name="chapter5part5.1"></a>Chapter 5 - Part 5.1: Introduction to Aggregate Functions

Aggregate functions perform calculations on a set of values and return a single summary value. Common aggregate functions in SQL include:

- COUNT(): Counts the number of rows.
- SUM(): Calculates the sum of values.
- AVG(): Calculates the average of values.
- MIN(): Finds the minimum value.
- MAX(): Finds the maximum value.

**COUNT()**

The COUNT() function is used to count the number of rows in a table or the number of non-null values in a specific column.

**Example:**

To find the total number of books in the books table:

```sql
SELECT COUNT(*) AS total_books
FROM books;
```

This query counts all rows in the books table and returns the total number of books. The AS total_books part gives the resulting count a more descriptive name.

**Example with a specific column:**

To count the number of books with a listed price:

```sql
SELECT COUNT(price) AS books_with_price
FROM books;
```

This query counts the number of rows where the price column is not null. If a book doesn't have a price listed (i.e., the price column is NULL), it won't be included in the count.

**SUM()**

The SUM() function calculates the sum of numeric values in a column.

**Example:**

To calculate the total revenue from all sales in the orders table (assuming the table has a total_amount column):

```sql
SELECT SUM(total_amount) AS total_revenue
FROM orders;
```

This query sums all the values in the total_amount column of the orders table, giving you the total revenue.

**Example with filtering:**

To calculate the total revenue from sales made in the last month:

```sql
SELECT SUM(total_amount) AS monthly_revenue
FROM orders
WHERE order_date >= DATE('now', '-1 month');
```

This query adds a WHERE clause to filter the orders to only include those placed within the last month before calculating the sum of total_amount. The DATE('now', '-1 month') function is specific to SQLite and calculates the date one month ago from the current date. Other SQL dialects may have different functions for date manipulation.

**AVG()**

The AVG() function calculates the average of numeric values in a column.

**Example:**

To calculate the average price of all books in the books table:

```sql
SELECT AVG(price) AS average_price
FROM books;
```

This query calculates the average of all values in the price column.

**Example with handling NULL values:**

If some books have a NULL value for the price, AVG() will ignore those NULL values in the calculation. If you want to treat NULL values as zero, you can use the COALESCE() function:

```sql
SELECT AVG(COALESCE(price, 0)) AS average_price_with_zeros
FROM books;
```

The COALESCE(price, 0) function replaces any NULL values in the price column with 0 before the average is calculated.

**MIN() and MAX()**

The MIN() and MAX() functions find the minimum and maximum values in a column, respectively.

**Example:**

To find the lowest and highest prices of books in the books table:

```sql
SELECT
    MIN(price) AS lowest_price,
    MAX(price) AS highest_price
FROM books;
```

This query returns two values: the minimum value in the price column (lowest price) and the maximum value (highest price).

**Example with dates:**

To find the date of the earliest and latest orders in the orders table:

```sql
SELECT
    MIN(order_date) AS earliest_order,
    MAX(order_date) AS latest_order
FROM orders;
```

This query finds the earliest and latest dates in the order_date column.

#### <a name="chapter5part5.2"></a>Chapter 5 - Part 5.2: Grouping Data with GROUP BY

The GROUP BY clause is used to group rows that have the same value in one or more columns into summary rows. It is often used in conjunction with aggregate functions to calculate summary statistics for each group.

**Example:**

To find the number of books in each category in the books table (assuming there's a category column):

```sql
SELECT
    category,
    COUNT(*) AS number_of_books
FROM books
GROUP BY category;
```

This query groups the rows in the books table by the category column. For each unique category, it counts the number of books in that category.

**Example with multiple columns:**

To find the average price of books in each category and by each publisher:

```sql
SELECT
    category,
    publisher,
    AVG(price) AS average_price
FROM books
GROUP BY category, publisher;
```

This query groups the rows by both category and publisher. It then calculates the average price for each unique combination of category and publisher.

#### <a name="chapter5part5.3"></a>Chapter 5 - Part 5.3: Filtering Groups with HAVING

The HAVING clause is used to filter the results of a GROUP BY query. It's similar to the WHERE clause, but it operates on groups rather than individual rows. The HAVING clause is applied after the GROUP BY clause, so you can use aggregate functions in the HAVING condition.

**Example:**

To find the categories that have more than 10 books:

```sql
SELECT
    category,
    COUNT(*) AS number_of_books
FROM books
GROUP BY category
HAVING COUNT(*) > 10;
```

This query first groups the books by category and counts the number of books in each category. Then, the HAVING clause filters the results to only include categories where the count is greater than 10.

**Example with multiple conditions:**

To find the categories with an average price greater than $20 and more than 5 books:

```sql
SELECT
    category,
    AVG(price) AS average_price,
    COUNT(*) AS number_of_books
FROM books
GROUP BY category
HAVING AVG(price) > 20 AND COUNT(*) > 5;
```

This query groups the books by category, calculates the average price and the number of books for each category. The HAVING clause then filters the results to only include categories where the average price is greater than 20 and the number of books is greater than 5.

#### <a name="chapter5part5.4"></a>Chapter 5 - Part 5.4: Combining Aggregate Functions and Joins

Aggregate functions and GROUP BY can be combined with JOIN operations to analyze data from multiple tables.

**Example:**

Assuming you have an orders table with customer_id and total_amount columns, and a customers table with customer_id and city columns, to find the total revenue generated by customers in each city:

```sql
SELECT
    c.city,
    SUM(o.total_amount) AS total_revenue
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id
GROUP BY c.city;
```

This query joins the orders and customers tables on the customer_id column. It then groups the results by city and calculates the sum of the total_amount for each city.

**Example with HAVING:**

To find the cities where the total revenue is greater than $1000:

```sql
SELECT
    c.city,
    SUM(o.total_amount) AS total_revenue
FROM orders o
JOIN customers c ON o.customer_id = c.customer_id
GROUP BY c.city
HAVING SUM(o.total_amount) > 1000;
```

This query is similar to the previous one, but it adds a HAVING clause to filter the results to only include cities where the total revenue is greater than $1000.

#### <a name="chapter5part6"></a>Chapter 5 - Part 6: aggregate function with ANY_VALUE()

The primary purpose of ANY_VALUE() is to suppress the ONLY_FULL_GROUP_BY SQL mode error that can occur in MySQL (and similar databases) when you have columns in your SELECT statement that are not part of the GROUP BY clause and are not functionally dependent on the grouped columns.

In simpler terms, ANY_VALUE() tells the database server that you don't care which value from the group is returned for a specific column. It essentially picks any value from the group for that column.

**Example**

Let's say you have a table called Orders with columns like OrderID, CustomerID, and OrderDate. You want to find the latest order date for each customer.

```sql
SELECT CustomerID, ANY_VALUE(OrderID), MAX(OrderDate) AS LatestOrderDate
FROM Orders
GROUP BY CustomerID;
```

In this example:

- We're grouping the data by CustomerID.
- MAX(OrderDate) gives us the latest order date for each customer.
- ANY_VALUE(OrderID) tells the database that we don't care which OrderID is returned for each customer. Without ANY_VALUE(), you might get an error if ONLY_FULL_GROUP_BY is enabled because OrderID is not functionally dependent on CustomerID.

**Important Considerations**

- **Non-Deterministic:** The value returned by ANY_VALUE() is non-deterministic, meaning you can't predict which value will be returned from the group.
- **SQL Mode Dependent:** The need for ANY_VALUE() often depends on the SQL mode settings of your database server.
- **Alternatives:** In some cases, you might be able to rewrite your query to avoid the need for ANY_VALUE() by using subqueries or joins.

#### <a name="chapter5part7"></a>Chapter 5 - Part 7: Common SQL Errors and Troubleshooting

SQL errors are an inevitable part of working with databases, especially when using aggregate functions and grouping. Understanding common error types and how to troubleshoot them is crucial for efficient data analysis and manipulation. This lesson will equip you with the knowledge to identify, understand, and resolve common SQL errors encountered when using aggregate functions and GROUP BY clauses. By learning to interpret error messages and apply systematic troubleshooting techniques, you'll be able to write more robust and error-free SQL queries.

#### <a name="chapter5part7.1"></a>Chapter 5 - Part 7.1: Common SQL Error Types

SQL errors can be broadly categorized into several types, each indicating a different kind of problem with your query. Recognizing these categories is the first step in effective troubleshooting.

**Syntax Errors**

Syntax errors are the most common type of SQL error and occur when the SQL code violates the language's grammatical rules. These errors are usually easy to identify because the database system provides a specific error message indicating the location and type of syntax error.

**Examples:**

- **Misspelled keywords**: Using SELEKT instead of SELECT.
- **Missing commas or semicolons**: Forgetting a comma between column names in a SELECT statement or omitting the semicolon at the end of a statement (depending on the database system).
- **Unbalanced parentheses**: Having an opening parenthesis without a corresponding closing parenthesis.
- **Incorrect use of operators**: Using an invalid operator or using an operator in the wrong context.

Example in the context of aggregate functions:

```sql
SELECT COUNT(customer_id) AS num_customers
FROM customers
WHERE order_total > AVG(order_total); -- Syntax error: aggregate function not allowed in WHERE clause
```

This example attempts to use the AVG() aggregate function within the WHERE clause, which is syntactically incorrect. Aggregate functions are typically used with GROUP BY and HAVING clauses.

**Semantic Errors**

Semantic errors occur when the SQL code is syntactically correct but doesn't make logical sense or violates the database's rules. These errors can be harder to detect than syntax errors because the database system may not always provide a clear error message.

- **Using a column that doesn't exist**: Referencing a column name that is not present in the table.
- **Incorrect data types**: Comparing a string value to a numeric column without proper conversion.
- **Ambiguous column names**: Using a column name that exists in multiple tables in a query without specifying which table it belongs to.
- **Using aggregate functions without a GROUP BY clause (or vice versa, when required)**: Selecting non-aggregated columns without a GROUP BY clause when using aggregate functions.

```sql
SELECT customer_id, AVG(order_total) AS average_order
FROM orders; -- Semantic error: customer_id is not aggregated
```

This query attempts to select customer_id along with the average order total, but it doesn't specify how to group the data. Since customer_id is not an aggregate, a GROUP BY clause is required to specify which customers' orders should be averaged.

**Runtime Errors**

Runtime errors occur during the execution of the SQL query. These errors can be caused by various factors, such as data issues, resource limitations, or concurrency problems.

- **Division by zero**: Attempting to divide a number by zero.
- **Data type overflow**: Trying to store a value that exceeds the maximum capacity of the data type.
- **Constraint violations**: Violating a primary key, foreign key, or unique constraint.
- **Deadlocks**: Occurring when two or more transactions are blocked indefinitely, waiting for each other to release resources.

```sql
SELECT product_category, COUNT(*) AS num_products
FROM products
GROUP BY product_category
HAVING COUNT(*) > (SELECT MAX(num_products) FROM (SELECT product_category, COUNT(*) AS num_products FROM products GROUP BY product_category) AS subquery);
```

While syntactically correct, this query could potentially lead to a runtime error if the subquery returns an empty result set, causing the MAX() function to return NULL. Comparing COUNT(*) to NULL might produce unexpected results or errors depending on the database system's handling of NULL values.

**Logical Errors**

Logical errors are the most difficult to detect because the SQL code executes without any errors, but the results are incorrect or unexpected. These errors are usually caused by flaws in the query's logic or misunderstanding of the data.

- **Incorrect join conditions**: Joining tables using the wrong columns, resulting in incorrect data combinations.
- **Incorrect filtering criteria**: Using the wrong conditions in a WHERE clause, leading to inaccurate results.
- **Misunderstanding aggregate function behavior**: Incorrectly interpreting the results of aggregate functions.
- **Applying the wrong aggregate function**: Using SUM when AVG is required.

```sql
SELECT product_category, AVG(price) AS average_price
FROM products
WHERE in_stock = TRUE
GROUP BY product_category;
```

If the intention is to calculate the average price of all products within each category, but the WHERE in_stock = TRUE clause is unintentionally included, the result will only reflect the average price of in-stock items, potentially skewing the overall average price for each category. This is a logical error because the query runs without errors but produces an incorrect result based on the intended logic.

#### <a name="chapter5part7.2"></a>Chapter 5 - Part 7.2: Troubleshooting Techniques

When you encounter an SQL error, it's important to follow a systematic approach to identify and resolve the problem. Here are some effective troubleshooting techniques:

**Read the Error Message Carefully**

The error message provided by the database system is your first clue to understanding the problem. Pay close attention to the following:

- **Error code**: The error code can provide more specific information about the type of error.
- **Error message text**: The error message usually describes the nature of the error and may provide hints about the cause.
- **Line number**: The line number indicates the location in the SQL code where the error occurred.

If you receive an error message like "ERROR 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'GROUP BY order_date' at line 3", it indicates a syntax error near the GROUP BY clause on line 3.

**Simplify the Query**

Complex SQL queries can be difficult to debug. Try simplifying the query by removing parts of it until the error disappears. This can help you isolate the source of the problem.

- **Comment out parts of the query**: Start by commenting out the WHERE, GROUP BY, HAVING, and ORDER BY clauses.
- **Run the simplified query**: See if the error is resolved. If so, the error lies in one of the commented-out clauses.
- **Uncomment clauses one by one**: Uncomment each clause and run the query until the error reappears. This will pinpoint the exact clause causing the error.
- **Further simplify the problematic clause**: If the error is in a complex WHERE or HAVING clause, try breaking it down into smaller, simpler conditions.

Example

Original query:

```sql
SELECT category, AVG(price) AS avg_price
FROM products
WHERE price > 10 AND in_stock = TRUE
GROUP BY category
HAVING COUNT(*) > 5
ORDER BY avg_price DESC;
```

Simplified query (commenting out clauses):

```sql
SELECT category, AVG(price) AS avg_price
FROM products;
-- WHERE price > 10 AND in_stock = TRUE
-- GROUP BY category
-- HAVING COUNT(*) > 5
-- ORDER BY avg_price DESC;
```

If the simplified query runs without errors, you know the error is in one of the commented-out clauses.

**Check Data Types**

Incorrect data types are a common cause of SQL errors. Make sure that you are comparing and manipulating data using compatible data types.

Things to check:

- **Column data types**: Verify the data types of the columns involved in the query using DESCRIBE table_name (in MySQL) or equivalent commands in other database systems.
- **Comparison operators**: Ensure that you are using the correct comparison operators for the data types you are comparing (e.g., using = for equality, > for greater than).
- **Type conversion**: Use explicit type conversion functions (e.g., CAST, CONVERT) to convert data types when necessary.

```sql
SELECT order_id, total_amount
FROM orders
WHERE order_date = '2024-01-15';
```

If order_date is a DATETIME column, comparing it directly to a string might cause issues. It's better to use a proper date/time function or cast the string to a DATETIME value:

```sql
SELECT order_id, total_amount
FROM orders
WHERE order_date = CAST('2024-01-15' AS DATE);
```

**Validate Table and Column Names**

Typos in table and column names are a frequent source of errors. Double-check that you have spelled all table and column names correctly and that they exist in the database.

- **Use auto-completion**: Most SQL editors provide auto-completion features that can help you avoid typos.
- **Check the database schema**: Use the database system's tools to view the table schemas and verify the names of tables and columns.
- **Pay attention to case sensitivity**: Some database systems are case-sensitive, so make sure you are using the correct case for table and column names.

Example:

If you accidentally type custmer_id instead of customer_id, the database system will return an error indicating that the column does not exist.

**Verify Aggregate Function Usage**

Aggregate functions have specific rules about how they can be used in SQL queries. Make sure you are following these rules:

- GROUP BY clause: If you are using aggregate functions in a SELECT statement, you must include a GROUP BY clause that specifies the columns to group the data by, unless you are aggregating all rows into a single result.
- HAVING clause: You can only use aggregate functions in the HAVING clause, not in the WHERE clause. The HAVING clause is used to filter groups based on aggregate function results.
- Nested aggregate functions: Most database systems do not allow nested aggregate functions (e.g., AVG(MAX(column))).

Example:

Incorrect usage:

```sql
SELECT AVG(order_total)
FROM orders
WHERE AVG(order_total) > 100; -- Error: aggregate function not allowed in WHERE clause
```

Correct usage:

```sql
SELECT AVG(order_total)
FROM orders
GROUP BY customer_id
HAVING AVG(order_total) > 100;
```

**Check for NULL Values**

NULL values can cause unexpected results when using aggregate functions. Understand how aggregate functions handle NULL values and use appropriate techniques to handle them.

Behavior of aggregate functions with NULL values:

- COUNT(*): Counts all rows, including those with NULL values.
- COUNT(column): Counts only non-NULL values in the specified column.
- SUM, AVG, MIN, MAX: Ignore NULL values.

Techniques for handling NULL values:

- COALESCE function: Use the COALESCE function to replace NULL values with a default value.
- WHERE clause: Use a WHERE clause to filter out NULL values.

Example:

```sql
SELECT AVG(COALESCE(price, 0)) AS average_price
FROM products;
```

This query replaces NULL values in the price column with 0 before calculating the average.

**Test with Sample Data**

If you are working with a large dataset, it can be helpful to test your query with a smaller sample of data. This can make it easier to identify errors and debug the query.

Steps:

- **Create a sample table**: Create a new table with a small subset of the data from the original table.
- **Run the query on the sample table**: Test the query on the sample table and see if you can reproduce the error.
- **Debug the query**: Once you have identified the error, fix it and test the query again on the sample table.
- **Run the query on the original table**: After you have fixed the error, run the query on the original table to make sure it works correctly.

**Consult Documentation and Online Resources**

The SQL documentation for your specific database system is an invaluable resource for understanding error messages, syntax rules, and function behavior. Online forums, such as Stack Overflow, can also provide helpful solutions to common SQL errors.

Tips:

- **Search for the error code**: Search the SQL documentation or online forums for the specific error code you are receiving.
- **Provide context**: When asking for help online, provide as much context as possible, including the SQL code, the error message, the database system you are using, and the table schemas.

#### <a name="chapter5part7.3"></a>Chapter 5 - Part 7.3: Practical Examples and Demonstrations

Let's illustrate these troubleshooting techniques with examples based on our "Online Bookstore" database. Assume we have books, authors, and orders tables.

**Example 1: Incorrect GROUP BY Clause**

Suppose we want to find the average price of books for each author. We write the following query:

```sql
SELECT author_id, AVG(price) AS average_price
FROM books;
```

This query results in the following error (in MySQL): "Error Code: 1140. In aggregated query without GROUP BY, expression #1 of SELECT list contains nonaggregated column 'bookstore.books.author_id'; this is incompatible with sql_mode=only_full_group_by".

Troubleshooting:

- Read the error message: The error message indicates that we are using a non-aggregated column (author_id) in the SELECT list without a GROUP BY clause.
- Fix the query: To fix the error, we need to add a GROUP BY clause that groups the data by author_id:

```sql
SELECT author_id, AVG(price) AS average_price
FROM books
GROUP BY author_id;
```

**Example 2: Using WHERE with Aggregate Functions**

We want to find all authors whose books have an average price greater than $20. We write the following query:

```sql
SELECT author_id, AVG(price) AS average_price
FROM books
WHERE AVG(price) > 20
GROUP BY author_id;
```

This query results in an error: "Invalid use of group function".

Troubleshooting:

- Read the error message: The error message indicates that we cannot use aggregate functions in the WHERE clause.
- Fix the query: To fix the error, we need to use the HAVING clause to filter the results based on the average price:

```sql
SELECT author_id, AVG(price) AS average_price
FROM books
GROUP BY author_id
HAVING AVG(price) > 20;
```

**Example 3: Division by Zero**

We want to calculate the percentage of books in each category that are bestsellers. We write the following query:

```sql
SELECT
    category,
    (SUM(CASE WHEN is_bestseller = TRUE THEN 1 ELSE 0 END) / COUNT(*)) * 100 AS bestseller_percentage
FROM
    books
GROUP BY
    category;
```

If a category has no books, COUNT(*) will be zero, leading to a division by zero error.

Troubleshooting:

- Anticipate the error: Before running the query, consider the possibility of division by zero.
- Add a check: Use a CASE statement to prevent division by zero:

```sql
SELECT
    category,
    CASE
        WHEN COUNT(*) = 0 THEN 0  -- Avoid division by zero
        ELSE (SUM(CASE WHEN is_bestseller = TRUE THEN 1 ELSE 0 END) / COUNT(*)) * 100
    END AS bestseller_percentage
FROM
    books
GROUP BY
    category;
```

This revised query checks if COUNT(*) is zero. If it is, the query returns 0 for the bestseller percentage, avoiding the division by zero error.

**Example 4: Incorrect Join Condition with Aggregation**

Let's say we want to find the average order total for each author, but we incorrectly join the orders table to the authors table directly instead of going through the books table.

```sql
SELECT a.author_name, AVG(o.total_amount) AS average_order_total
FROM authors a
JOIN orders o ON a.author_id = o.customer_id  -- Incorrect join condition
GROUP BY a.author_name;
```

This query will likely run without errors, but the results will be meaningless because the join condition is incorrect. It's joining authors to orders based on customer_id instead of linking orders to books and then books to authors.

Troubleshooting:

- Examine the results: Notice that the average order totals seem unusually high or low, or the results don't align with expectations.
- Review the join conditions: Carefully analyze the relationships between the tables. The correct join should involve the books table:

```sql
SELECT a.author_name, AVG(o.total_amount) AS average_order_total
FROM authors a
JOIN books b ON a.author_id = b.author_id
JOIN orders o ON b.book_id = o.book_id -- Correct join condition
GROUP BY a.author_name;
```

This corrected query joins authors to books using author_id and then books to orders using book_id, providing the correct average order total for each author.

## <a name="chapter6"></a>Chapter 6: Scalar Functions

- LEN() (in other SQL flavors – LENGTH()) – returns the length of a string, including the blank spaces

- UCASE() (in other SQL flavors – UPPER()) – returns a string converted to the upper case

- LCASE() (in other SQL flavors – LOWER()) – returns a string converted to the lower case

- INITCAP() – returns a string converted to the title case (i.e., each word of the string starts from a capital letter)

- MID() (in other SQL flavors – SUBSTR()) – extracts a substring from a string

- ROUND() – returns the numerical value rounded to a specified number of decimals

- NOW() – returns the current date and time

```sql
-- Length of the product name
SELECT ProductName, LENGTH(ProductName) AS NameLength FROM Products;

-- Product name in uppercase
SELECT ProductName, UPPER(ProductName) AS UppercaseName FROM Products;

-- Product name in lowercase
SELECT ProductName, LOWER(ProductName) AS LowercaseName FROM Products;

-- Round the price to the nearest whole number
SELECT ProductName, ROUND(Price) AS RoundedPrice FROM Products;

-- Current date and time
SELECT NOW();
```

## <a name="chapter7"></a>Chapter 7: Case manipulation Functions

Case manipulation functions represent a subset of character functions, and they're used to change the case of the text data. With these functions, we can convert the data into the upper, lower, or title case.

- UCASE() (in other SQL flavors – UPPER()) – returns a string converted to the upper case

- LCASE() (in other SQL flavors – LOWER()) – returns a string converted to the lower case

- INITCAP() – returns a string converted to the title case (i.e., each word of the string starts from a capital letter)

```sql
-- Product name in uppercase
SELECT ProductName, UCASE(ProductName) AS UppercaseName FROM Products;

-- Product name in lowercase
SELECT ProductName, LCASE(ProductName) AS LowercaseName FROM Products;

-- (Hypothetical) Product name in title case (not supported in all SQL dialects)
-- SELECT ProductName, INITCAP(ProductName) AS TitleCaseName FROM Products;
```

## <a name="chapter8"></a>Chapter 8: Character manipulation Functions

Character manipulation functions represent a subset of character functions, and they're used to modify the text data.

- CONCAT() – joins two or more string values appending the second string to the end of the first one

- SUBSTR() – returns a part of a string satisfying the provided start and end points

- LENGTH() (in other SQL flavors – LEN()) – returns the length of a string, including the blank spaces

- REPLACE() – replaces all occurrences of a defined substring in a provided string with another substring

- INSTR() – returns the numeric position of a defined substring in a provided string

- LPAD() and RPAD() – return the padding of the left-side/right-side character for right-justified/left-justified value

- TRIM() – removes all the defined characters, as well as white spaces, from the left, right, or both ends of a provided string

```sql
-- Concatenate product name and category
SELECT CONCAT(ProductName, ' (', Category, ')') AS ProductInfo FROM Products;

-- Extract the first 5 characters of the product name
SELECT ProductName, SUBSTR(ProductName, 1, 5) AS ShortName FROM Products;

-- Find the position of 'laptop' in the description
SELECT Description, INSTR(Description, 'laptop') AS LaptopPosition FROM Products;

-- Replace 'leather' with 'genuine leather' in the description
SELECT Description, REPLACE(Description, 'leather', 'genuine leather') AS UpdatedDescription FROM Products;

-- Pad the product name with spaces on the left to a length of 20
SELECT ProductName, LPAD(ProductName, 20, ' ') AS PaddedProductName FROM Products;

-- Remove leading and trailing spaces from the description (if any)
SELECT Description, TRIM(Description) AS TrimmedDescription FROM Products;
```

## <a name="chapter9"></a>Chapter 9: Case() Functions

The way to implement the if-then-else logic in SQL. This function sequentially checks the provided conditions in the WHEN clauses and returns the value from the corresponding THEN clause when the first condition is satisfied. If none of the conditions is satisfied, the function returns the value from the ELSE clause in case it's provided, otherwise, it returns NULL. The syntax is:

```sql
CASE
    WHEN condition_1 THEN value_1
    WHEN condition_2 THEN value_2
    WHEN condition_3 THEN value_3
    ...
    ELSE value
END;
```

## <a name="chapter10"></a>Chapter 10: Set Operators

Set operators are used to combine the results of two or more ```SELECT``` statements into a single result set. These operators treat the result of each SELECT statement as a set and perform operations on these sets.

**Key Requirements:**

- The ```SELECT``` statements must have the same number of columns in the result sets.
  
- The corresponding columns in the ```SELECT``` statements must have compatible data types.
  
- The order and names of the columns do not need to be the same, but the data types must be compatible.

**Common Set Operators:**

- UNION: Combines the result sets of two or more SELECT statements, removing duplicate rows.

- UNION ALL: Combines the result sets of two or more SELECT statements, including all rows (duplicates are not removed).

- INTERSECT: Returns the rows that are common to the result sets of two SELECT statements.

- MINUS (or EXCEPT): Returns the rows from the first SELECT statement that are not present in the result set of the second SELECT statement.

Table 1: Customers

| CustomerID  | CustomerName | City          |
| :---------: | :-----------:|:-------------:|
| 1           | Alice        | New York      |
| 2           | Bob          | Los Angeles   |
| 3           | Charlie      | Chicago       |
| 4           | David        | Houston       |

Table 1: Orders

| OrderID  | CustomerID | City          |
| :------: | :---------:|:-------------:|
| 101      | 1          | New York      |
| 102      | 2          | Los Angeles   |
| 103      | 5          | Miami         |
| 104      | 6          | Dallas        |

- 1. UNION:

Let's combine the cities from the Customers and Orders tables, removing duplicates.

```sql
SELECT City FROM Customers
UNION
SELECT City FROM Orders;
```

| City          |
|:-------------:|
| New York      |
| Los Angeles   |
| Chicago       |
| Houstoun      |
| Miami         |
| Dallas        |

- 2. UNION ALL:

Let's combine the cities from the Customers and Orders tables, including duplicates.

| City          |
|:-------------:|
| New York      |
| Los Angeles   |
| Chicago       |
| Houstoun      |
| New York      |
| Los Angeles   |
| Miami         |
| Dallas        |

- 3. INTERSECT:
 
Let's find the cities that are present in both the Customers and Orders tables.

```sql
SELECT City FROM Customers
INTERSECT
SELECT City FROM Orders;
```

| City          |
|:-------------:|
| New York      |
| Los Angeles   |

- 4. MINUS (or EXCEPT):

Let's find the cities that are present in the Customers table but not in the Orders table.

```sql
SELECT City FROM Customers
EXCEPT -- or MINUS, depending on the database system
SELECT City FROM Orders;
```

| City          |
|:-------------:|
| Chicago       |
| Houston       |

## <a name="chapter11"></a>Chapter 11: Subqueries and Views

#### <a name="chapter11part1"></a>Chapter 11 - Part 1: Introduction to Subqueries: Queries Within Queries

Subqueries are a powerful tool in SQL that allow you to embed one query inside another. This enables you to solve complex data retrieval problems by breaking them down into smaller, more manageable steps. They are essential for tasks like filtering data based on the results of another query, calculating aggregate values for use in comparisons, and creating dynamic datasets. This lesson will provide a comprehensive introduction to subqueries, covering their syntax, different types, and practical applications, particularly within the context of the "Online Bookstore" database we've been using.

#### <a name="chapter11part1.1"></a>Chapter 11 - Part 1.1: Understanding Subqueries

A subquery, also known as an inner query or nested query, is a SQL query embedded inside another SQL query. The outer query is often referred to as the main query. Subqueries are used to perform a query within a query, allowing you to use the result of the inner query to filter or manipulate data in the outer query.

**Subquery Syntax**

The basic syntax of a subquery involves placing a SELECT statement inside parentheses () within another SQL statement. The subquery is executed first, and its result is then used by the outer query.

```sql
SELECT column1, column2
FROM table_name
WHERE column_name IN (SELECT column_name FROM another_table WHERE condition);
```

In this example:

- The SELECT column1, column2 FROM table_name is the outer query.
- The (SELECT column_name FROM another_table WHERE condition) is the subquery.
- The subquery is executed first, returning a set of values.
- The outer query then uses the IN operator to filter rows from table_name based on the values returned by the subquery.

**Types of Subqueries**

Subqueries can be classified based on their return type and usage:

- **Scalar Subqueries**: These return a single value. They can be used anywhere a single value is expected, such as in WHERE clauses, SELECT lists, or HAVING clauses.

- **Column Subqueries**: These return a single column of multiple rows. They are often used with operators like IN, NOT IN, ANY, or ALL in the WHERE clause.

- **Table Subqueries**: These return a table (one or more columns and one or more rows). They can be used in the FROM clause as if they were a regular table (often requiring an alias).

- **Correlated Subqueries**: These depend on the outer query for their values. The outer query iterates through each row, and the subquery is executed for each row.

#### <a name="chapter11part1.2"></a>Chapter 11 - Part 1.2: Using Subqueries in WHERE Clauses

Subqueries are frequently used in WHERE clauses to filter rows based on a condition that depends on the result of another query.

**Scalar Subqueries in WHERE Clauses**

A scalar subquery returns a single value. This value can then be used in a comparison within the WHERE clause.

**Example**: Find all books in the "Online Bookstore" database that have a price higher than the average price of all books.

First, let's assume we have a books table with columns like book_id, title, and price.

```sql
SELECT title, price
FROM books
WHERE price > (SELECT AVG(price) FROM books);
```

In this example:

- The subquery (SELECT AVG(price) FROM books) calculates the average price of all books in the books table.
- The outer query then selects the title and price of all books where the price is greater than the average price returned by the subquery.

**Explanation**:

- The subquery SELECT AVG(price) FROM books is executed first. Let's say it returns a value of 25.00 (the average book price).

- The outer query becomes SELECT title, price FROM books WHERE price > 25.00.

- The outer query then retrieves all books from the books table where the price is greater than 25.00.

**Another Example**: Find all authors whose total book sales exceed a certain threshold. Assume we have an authors table with author_id and name, and a sales table with book_id, author_id, and quantity_sold.

```sql
SELECT a.name
FROM authors a
WHERE a.author_id IN (SELECT s.author_id FROM sales s GROUP BY s.author_id HAVING SUM(s.quantity_sold) > 1000);
```

Here, the subquery identifies author_id values where the sum of quantity_sold exceeds 1000. The outer query then retrieves the names of those authors.

**Column Subqueries with IN, NOT IN, ANY, and ALL**

Column subqueries return a single column of multiple rows. These are often used with operators like IN, NOT IN, ANY, and ALL.

**Example**: Find all books that belong to genres that have at least one book with a price greater than $30.

```sql
SELECT title, price, genre_id
FROM books
WHERE genre_id IN (SELECT genre_id FROM books WHERE price > 30);
```

In this example:

- The subquery (SELECT genre_id FROM books WHERE price > 30) returns a list of genre_id values for genres that have at least one book with a price greater than 30.

- The outer query then selects the title, price, and genre_id of all books where the genre_id is in the list returned by the subquery.

**Explanation**:

- The subquery SELECT genre_id FROM books WHERE price > 30 is executed first. Let's say it returns the values (1, 3).

- The outer query becomes SELECT title, price, genre_id FROM books WHERE genre_id IN (1, 3).

- The outer query then retrieves all books from the books table where the genre_id is either 1 or 3.

**Using NOT IN**: To find all books that do not belong to genres that have at least one book with a price greater than $30, you would use NOT IN:

```sql
SELECT title, price, genre_id
FROM books
WHERE genre_id NOT IN (SELECT genre_id FROM books WHERE price > 30);
```

**Using ANY (or SOME)**: The ANY operator returns true if any of the subquery values meet the condition.

**Example**: Find books with a price greater than at least one book in the 'Fiction' genre.

```sql
SELECT title, price
FROM books
WHERE price > ANY (SELECT price FROM books WHERE genre_id = (SELECT genre_id FROM genres WHERE genre_name = 'Fiction'));
```

**Using ALL**: The ALL operator returns true if all of the subquery values meet the condition.

**Example**: Find books with a price greater than all books in the 'Fiction' genre.

```sql
SELECT title, price
FROM books
WHERE price > ALL (SELECT price FROM books WHERE genre_id = (SELECT genre_id FROM genres WHERE genre_name = 'Fiction'));
```

**Correlated Subqueries in WHERE Clauses**

A correlated subquery is a subquery that references a column from the outer query. This means that the subquery is executed once for each row in the outer query. Correlated subqueries can be less efficient than non-correlated subqueries, but they are necessary for certain types of queries.

**Example**: Find all authors who have written at least one book in the same genre as another author.

```sql
SELECT a1.name
FROM authors a1
WHERE EXISTS (SELECT 1 FROM books b1 JOIN books b2 ON b1.genre_id = b2.genre_id WHERE b1.author_id = a1.author_id AND b2.author_id <> a1.author_id);
```

In this example:

- The outer query selects the name from the authors table (aliased as a1).
- The correlated subquery checks if there exists any book (b1) written by the current author (a1) that shares the same genre_id with another book (b2) written by a different author.
- The EXISTS operator returns true if the subquery returns at least one row, indicating that the author has written a book in the same genre as another author.

**Explanation**:

- The outer query starts by selecting the first author from the authors table.
- The correlated subquery is executed for that author. It checks if there exists any book written by that author that shares the same genre_id with another book written by a different author.
- If the subquery returns at least one row (i.e., the EXISTS operator returns true), the author's name is included in the result set.
- The process is repeated for each author in the authors table.

#### <a name="chapter11part1.3"></a>Chapter 11 - Part 1.3: Using Subqueries in SELECT Clauses

Subqueries can also be used in the SELECT clause to return a value for each row in the outer query. These are typically scalar subqueries, as they must return a single value.

**Example**: For each book, display its title and the average price of all books in the same genre.

```sql
SELECT
    b.title,
    (SELECT AVG(price) FROM books WHERE genre_id = b.genre_id) AS avg_genre_price
FROM
    books b;
```

In this example:

- The outer query selects the title from the books table (aliased as b).
- The subquery (SELECT AVG(price) FROM books WHERE genre_id = b.genre_id) calculates the average price of all books in the same genre as the current book.
- The result of the subquery is aliased as avg_genre_price and included in the result set for each book.

**Explanation**:

- The outer query starts by selecting the first book from the books table.
- The subquery is executed for that book. It calculates the average price of all books in the same genre as the current book.
- The result of the subquery (the average genre price) is included in the result set for that book.
- The process is repeated for each book in the books table.

**Another Example**: Display each author's name along with the total number of books they have written.

```sql
SELECT
    a.name,
    (SELECT COUNT(*) FROM books WHERE author_id = a.author_id) AS total_books
FROM
    authors a;
```

Here, the subquery counts the number of books for each author, and the outer query displays the author's name along with this count.

#### <a name="chapter11part1.4"></a>Chapter 11 - Part 1.4: Table Subqueries in the FROM Clause

Table subqueries, also known as derived tables, are subqueries used in the FROM clause. They allow you to treat the result of a subquery as if it were a table. Derived tables must be given an alias.

**Example**: Find the genres with an average book price greater than $28.

```sql
SELECT genre_name, avg_price
FROM (SELECT genre_id, AVG(price) AS avg_price FROM books GROUP BY genre_id) AS genre_avg
JOIN genres ON genre_avg.genre_id = genres.genre_id
WHERE avg_price > 28;
```

In this example:

- The subquery (SELECT genre_id, AVG(price) AS avg_price FROM books GROUP BY genre_id) calculates the average price for each genre and returns a table with genre_id and avg_price columns.
- This subquery is aliased as genre_avg.
- The outer query joins the genre_avg derived table with the genres table on the genre_id column.
- The WHERE clause filters the results to include only genres where the avg_price is greater than 28.

**Explanation**:

- The subquery SELECT genre_id, AVG(price) AS avg_price FROM books GROUP BY genre_id is executed first. It returns a table with the average price for each genre.
- The outer query treats this table as if it were a regular table named genre_avg.
- The outer query joins genre_avg with the genres table to retrieve the genre_name for each genre.
- The WHERE clause filters the results to include only genres where the avg_price is greater than 28.

**Another Example**: Find the top 3 most popular books (based on sales quantity). Assume we have a sales table with book_id and quantity_sold.

```sql
SELECT b.title, sub.total_sold
FROM (SELECT book_id, SUM(quantity_sold) AS total_sold FROM sales GROUP BY book_id ORDER BY total_sold DESC LIMIT 3) AS sub
JOIN books b ON sub.book_id = b.book_id;
```

Here, the subquery calculates the total quantity sold for each book, orders the results in descending order, and limits the result to the top 3. The outer query then joins this derived table with the books table to retrieve the titles of these top 3 books.

#### <a name="chapter11part1.5"></a>Chapter 11 - Part 1.5: Table Subqueries in the HAVING Clause

The HAVING clause is used to filter groups created by the GROUP BY clause. When you use a subquery in the HAVING clause, you're essentially saying, "Only include those groups where some condition, evaluated by this subquery, is true."

**Syntax**

```sql
SELECT column1, column2, aggregate_function(column3)
FROM table_name
WHERE condition -- Optional WHERE clause to filter rows *before* grouping
GROUP BY column1, column2
HAVING condition_involving_subquery;
```

**Explanation**

- SELECT column1, column2, aggregate_function(column3): This selects the columns you want to display and calculates aggregate functions (like COUNT, SUM, AVG, MIN, MAX) for each group.
- FROM table_name: Specifies the table you're querying.
- WHERE condition: Optional. Filters the rows before they are grouped. This is important for performance; filter as early as possible.
- GROUP BY column1, column2: Groups the rows based on the specified columns. All rows with the same values for column1 and column2 will be in the same group.
- HAVING condition_involving_subquery: This is where the magic happens. The HAVING clause filters the groups created by the GROUP BY clause. The condition_involving_subquery is a boolean expression that must be true for a group to be included in the final result. The subquery is evaluated for each group.

**Example Scenario: Bookstore Database**

Let's say we want to find all book categories in our bookstore database where the average price of books in that category is higher than the average price of all books in the database.

```sql
SELECT category, AVG(price) AS avg_price
FROM books
GROUP BY category
HAVING AVG(price) > (SELECT AVG(price) FROM books);
```

**Breakdown**

- SELECT category, AVG(price) AS avg_price: Selects the book category and calculates the average price for each category, aliasing it as avg_price.
- FROM books: Specifies the books table.
- GROUP BY category: Groups the books by their category.
- HAVING AVG(price) > (SELECT AVG(price) FROM books): This is the key part.
  - AVG(price): Calculates the average price for the current category being considered by the HAVING clause.
  - (SELECT AVG(price) FROM books): This is the subquery. It calculates the average price of all books in the books table. This subquery is executed once for the entire query.
  - >: The HAVING clause only includes those categories where the average price for that category is greater than the overall average price.
    
**Important Considerations**

- Subquery Type: The subquery in the HAVING clause often returns a single value (like in the example above). This is a scalar subquery. It can also be a correlated subquery (explained below).
- Correlated Subqueries: A correlated subquery refers to a column from the outer query. This means the subquery is evaluated for each group processed by the HAVING clause. Correlated subqueries can be less efficient than non-correlated subqueries.
- Performance: Using subqueries in the HAVING clause can sometimes impact performance, especially with large datasets. Make sure you have appropriate indexes on the tables involved. Consider alternative approaches (like using temporary tables or common table expressions - CTEs) if performance becomes an issue.
- Readability: While powerful, complex subqueries can make your SQL harder to read. Use clear aliases and formatting to improve readability. Consider breaking down complex logic into smaller, more manageable subqueries or CTEs.

**Example of Correlated Subquery (Less Common, but Illustrative)**

Let's say you want to find categories where the average book price is higher than the average price of books published in the last year within that same category.

```sql
SELECT category, AVG(price) AS avg_price
FROM books
GROUP BY category
HAVING AVG(price) > (
    SELECT AVG(price)
    FROM books AS b2
    WHERE b2.category = books.category  -- Correlated subquery!
      AND b2.publication_date >= DATE('now', '-1 year')
);
```

In this case, the subquery is correlated because b2.category = books.category refers to the category column from the outer query. The subquery is evaluated separately for each category to determine the average price of books published in the last year within that category.

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

A CTE (Common Table Expression) is a temporary named result set that you can define within a single SELECT, INSERT, UPDATE, or DELETE statement. It's essentially a named subquery that exists only for the duration of the query execution. CTEs are not stored as database objects; they are temporary and exist only in memory while the query is running.

- Temporary: CTEs exist only for the duration of a single query.

- Named Result Set: They provide a name for a subquery, making the query more readable and maintainable.

- Recursive: CTEs can be recursive, allowing you to work with hierarchical data.

- Multiple CTEs: You can define multiple CTEs within a single query.

- Readability: CTEs improve the readability and structure of complex queries.

- Reusability: They allow you to reuse the result set within the main query, avoiding redundant calculations or subqueries.

```sql
WITH CTE_Name AS (
    -- Subquery definition
    SELECT column1, column2
    FROM TableName
    WHERE condition
)
-- Main query that uses the CTE
SELECT column1, column2
FROM CTE_Name
WHERE condition;
```

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

## <a name="appendixa"></a>Appendix A: Useful DuckDB Code Snippet

#### <a name="appendixapart1"></a>Appendix A - Part 1: Remove characters from VARCHARS using REGEXP_REPLACE

```
CREATE TABLE test AS SELECT CONCAT(chr(13),chr(10),'Hello World') AS example;

SELECT * FROM test;

┌─────────────────┐
│     example     │
│     varchar     │
├─────────────────┤
│ \r\nHello World │
└─────────────────┘

SELECT REGEXP_REPLACE(example, '[\n\r]+'::text, ' '::text, 'g'::text) AS transformed_example FROM test;

┌─────────────────────┐
│ transformed_example │
│       varchar       │
├─────────────────────┤
│  Hello World        │
└─────────────────────┘
```

#### <a name="appendixapart2"></a>Appendix A - Part 2: Check if a column have different values in other column

```
CREATE TABLE products (sku VARCHAR(10),price DECIMAL(10,2));

INSERT INTO products (sku, price) VALUES
('AA', 20),
('AA', 30),
('BB', 40),
('CC', 50),
('CC', 50),
('DD', 60),
('DD', 70);

SELECT * FROM products;
┌─────────┬───────────────┐
│   sku   │     price     │
│ varchar │ decimal(10,2) │
├─────────┼───────────────┤
│ AA      │         20.00 │
│ AA      │         30.00 │
│ BB      │         40.00 │
│ CC      │         50.00 │
│ CC      │         50.00 │
│ DD      │         60.00 │
│ DD      │         70.00 │
└─────────┴───────────────┘

SELECT sku FROM products GROUP BY sku HAVING COUNT(DISTINCT price) > 1;

┌─────────┐
│   sku   │
│ varchar │
├─────────┤
│ AA      │
│ DD      │
└─────────┘
```

#### <a name="appendixapart3"></a>Appendix A - Part 3: Check for duplicate lines

```
CREATE TABLE products (sku VARCHAR(10),price DECIMAL(10,2));

INSERT INTO products (sku, price) VALUES
('AA', 20),
('AA', 30),
('BB', 40),
('CC', 50),
('CC', 50),
('DD', 60),
('DD', 70);

SELECT * FROM products;
┌─────────┬───────────────┐
│   sku   │     price     │
│ varchar │ decimal(10,2) │
├─────────┼───────────────┤
│ AA      │         20.00 │
│ AA      │         30.00 │
│ BB      │         40.00 │
│ CC      │         50.00 │
│ CC      │         50.00 │
│ DD      │         60.00 │
│ DD      │         70.00 │
└─────────┴───────────────┘

SELECT sku, price, COUNT(*) FROM products GROUP BY sku, price HAVING COUNT(*) > 1 ORDER BY sku ASC;

┌─────────┬───────────────┬──────────────┐
│   sku   │     price     │ count_star() │
│ varchar │ decimal(10,2) │    int64     │
├─────────┼───────────────┼──────────────┤
│ CC      │         50.00 │            2 │
└─────────┴───────────────┴──────────────┘
```

#### <a name="appendixapart4"></a>Appendix A - Part 4: Find a character in a VARCHAR field

```
CREATE TABLE products (sku VARCHAR(10),price DECIMAL(10,2));

INSERT INTO products (sku, price) VALUES
('AA', 20),
('AA', 30),
('B|B', 40),
('CC', 50),
('CC', 50),
('DD', 60),
('DD', 70);

SELECT * FROM products;

┌─────────┬───────────────┐
│   sku   │     price     │
│ varchar │ decimal(10,2) │
├─────────┼───────────────┤
│ AA      │         20.00 │
│ AA      │         30.00 │
│ B|B     │         40.00 │
│ CC      │         50.00 │
│ CC      │         50.00 │
│ DD      │         60.00 │
│ DD      │         70.00 │
└─────────┴───────────────┘

SELECT * FROM products WHERE sku LIKE '%|%';

┌─────────┬───────────────┐
│   sku   │     price     │
│ varchar │ decimal(10,2) │
├─────────┼───────────────┤
│ B|B     │         40.00 │
└─────────┴───────────────┘
```

#### <a name="appendixapart5"></a>Appendix A - Part 5: Split a field and create new columns

```
CREATE TABLE products (line_number INT, sku VARCHAR(10), price DECIMAL(10,2), metafields VARCHAR);

INSERT INTO products (line_number, sku, price, metafields) VALUES
  (1, 'AA', 20.0, 'name|maria#lastname|joao#gender|femea'),
  (2, 'BB', 30.0, 'name|carlos#gender|male'),
  (3, 'CC', 40.0, 'name|joana');
  
SELECT * FROM products;

┌─────────────┬─────────┬───────────────┬───────────────────────────────────────┐
│ line_number │   sku   │     price     │              metafields               │
│    int32    │ varchar │ decimal(10,2) │                varchar                │
├─────────────┼─────────┼───────────────┼───────────────────────────────────────┤
│           1 │ AA      │         20.00 │ name|maria#lastname|joao#gender|femea │
│           2 │ BB      │         30.00 │ name|carlos#gender|male               │
│           3 │ CC      │         40.00 │ name|joana                            │
└─────────────┴─────────┴───────────────┴───────────────────────────────────────┘

WITH pairs AS (
  SELECT
 line_number AS LineNumber,
 sku AS SKU,
 price AS PRICE,
 regexp_split_to_table(metafields, '#') AS metafields
 FROM products
 ),
 key_value AS (
 SELECT
  LineNumber AS LineNumber,
  SKU AS SKU,
  PRICE AS PRICE,
  split_part(metafields, '|', 1) AS key,
 split_part(metafields, '|', 2) AS pair
 FROM pairs
 ),
 firstNameQuery AS (
 SELECT
   LineNumber AS LineNumber,
   SKU AS SKU,
   PRICE AS PRICE,
   CASE 
      WHEN key = 'name' 
      THEN pair 
      ELSE NULL 
  END AS FirstName
 FROM key_value
 )
 
 SELECT
   LineNumber AS LineNumber,
   SKU AS SKU,
   PRICE AS PRICE,
   FirstName AS FIRSTNAME
 FROM firstNameQuery
 WHERE(CASE WHEN FirstName IS NOT NULL AND FirstName != '' THEN 1 ELSE 0 END) >= 1;
 
┌────────────┬─────────┬───────────────┬───────────┐
│ LineNumber │   SKU   │     PRICE     │ FIRSTNAME │
│   int32    │ varchar │ decimal(10,2) │  varchar  │
├────────────┼─────────┼───────────────┼───────────┤
│          1 │ AA      │         20.00 │ maria     │
│          2 │ BB      │         30.00 │ carlos    │
│          3 │ CC      │         40.00 │ joana     │
└────────────┴─────────┴───────────────┴───────────┘
```

 #### <a name="appendixapart6"></a>Appendix A - Part 6: Split a field and aggregate values

 ```
CREATE TABLE products (sku VARCHAR(10),price DECIMAL(10,2), size VARCHAR(10));

INSERT INTO products (sku, price, size) VALUES
  ('AA', 20, 'S'),
  ('AA', 20, 'M'),
  ('AA', 20, 'L'),
  ('BB', 30, '38'),
  ('BB', 30, '39');

SELECT * FROM products;

┌─────────┬───────────────┬─────────┐
│   sku   │     price     │  size   │
│ varchar │ decimal(10,2) │ varchar │
├─────────┼───────────────┼─────────┤
│ AA      │         20.00 │ S       │
│ AA      │         20.00 │ M       │
│ AA      │         20.00 │ L       │
│ BB      │         30.00 │ 38      │
│ BB      │         30.00 │ 39      │
└─────────┴───────────────┴─────────┘

SELECT
    price AS PRICE,
    CONCAT(sku,'|',string_agg(TRIM(size), '_' ORDER BY size)) AS ConcatSize
FROM
    products
GROUP BY
    sku, price;

┌───────────────┬────────────┐
│     PRICE     │ ConcatSize │
│ decimal(10,2) │  varchar   │
├───────────────┼────────────┤
│         30.00 │ BB|38_39   │
│         20.00 │ AA|L_M_S   │
└───────────────┴────────────┘
```

 #### <a name="appendixapart7"></a>Appendix A - Part 7: Select just even numbers

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
  (1, 'AA', 'IT', 'ABC', 100000),
  (2, 'BB', 'DE', 'DEF', 99999),
  (3, 'CC', 'FR', 'GHI', 100001);

SELECT * FROM EXAMPLE;

┌───────┬─────────┬─────────────┬──────────┬────────────┐
│  ID   │  NAME   │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │ varchar │   varchar   │ varchar  │   int32    │
├───────┼─────────┼─────────────┼──────────┼────────────┤
│     1 │ AA      │ IT          │ ABC      │     100000 │
│     2 │ BB      │ DE          │ DEF      │      99999 │
│     3 │ CC      │ FR          │ GHI      │     100001 │
└───────┴─────────┴─────────────┴──────────┴────────────┘

SELECT DISTINCT
      *
      FROM EXAMPLE
      WHERE
      CASE
          WHEN MOD(ID,2) = 0
          THEN 1
          ELSE 0
      END;

┌───────┬─────────┬─────────────┬──────────┬────────────┐
│  ID   │  NAME   │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │ varchar │   varchar   │ varchar  │   int32    │
├───────┼─────────┼─────────────┼──────────┼────────────┤
│   2   │ BB      │ DE          │ DEF      │   99999    │
└───────┴─────────┴─────────────┴──────────┴────────────┘
```

 #### <a name="appendixapart8"></a>Appendix A - Part 8: Find the difference of Duplicate Values

 Find the difference between the total number of COUNTRYCODE entries in the table and the number of distinct COUNTRYCODE entries in the table

 ```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'AA', 'IT', 'ABC', 100000),
(2, 'BB', 'IT', 'DEF', 99999),
(3, 'CC', 'FR', 'GHI', 100001);

SELECT COUNT(COUNTRYCODE) - COUNT(DISTINCT COUNTRYCODE) AS Difference FROM EXAMPLE;

┌────────────┐
│ Difference │
│   int64    │
├────────────┤
│     1      │
└────────────┘

```

 #### <a name="appendixapart9"></a>Appendix A - Part 9: Find the Min and Max Length of a String and ordered alphabetically

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'Abruzzo', 'IT', 'ABC', 100000),
(2, 'Roma', 'IT', 'DEF', 99999),
(3, 'Paris', 'FR', 'GHI', 100001),
(4, 'Lima', 'PE', 'JKL', 101001);

SELECT * FROM EXAMPLE;

┌───────┬─────────┬─────────────┬──────────┬────────────┐
│  ID   │  NAME   │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │ varchar │   varchar   │ varchar  │   int32    │
├───────┼─────────┼─────────────┼──────────┼────────────┤
│     1 │ Abruzzo │ IT          │ ABC      │     100000 │
│     2 │ Roma    │ IT          │ DEF      │      99999 │
│     3 │ Paris   │ FR          │ GHI      │     100001 │
│     4 │ Lima    │ PE          │ JKL      │     101001 │
└───────┴─────────┴─────────────┴──────────┴────────────┘

WITH name_lengths AS (
SELECT NAME, LENGTH(NAME) nameLength FROM EXAMPLE ORDER BY NAME
),
min_length AS (
SELECT NAME, nameLength FROM name_lengths WHERE nameLength = (SELECT MIN(nameLength) FROM name_lengths) LIMIT 1
),
max_length AS (
SELECT NAME, nameLength FROM name_lengths WHERE nameLength = (SELECT MAX(nameLength) FROM name_lengths) LIMIT 1
),
final_query AS (
SELECT * FROM min_length
UNION
SELECT * FROM max_length
)

SELECT * FROM final_query ORDER BY NAME;

┌─────────┬────────────┐
│  NAME   │ nameLength │
│ varchar │   int64    │
├─────────┼────────────┤
│ Abruzzo │          7 │
│ Lima    │          4 │
└─────────┴────────────┘
```

With inner Joins

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'Abruzzo', 'IT', 'ABC', 100000),
(2, 'Roma', 'IT', 'DEF', 99999),
(3, 'Paris', 'FR', 'GHI', 100001),
(4, 'Lima', 'PE', 'JKL', 101001);

SELECT * FROM EXAMPLE;

┌───────┬─────────┬─────────────┬──────────┬────────────┐
│  ID   │  NAME   │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │ varchar │   varchar   │ varchar  │   int32    │
├───────┼─────────┼─────────────┼──────────┼────────────┤
│     1 │ Abruzzo │ IT          │ ABC      │     100000 │
│     2 │ Roma    │ IT          │ DEF      │      99999 │
│     3 │ Paris   │ FR          │ GHI      │     100001 │
│     4 │ Lima    │ PE          │ JKL      │     101001 │
└───────┴─────────┴─────────────┴──────────┴────────────┘

WITH name_lengths AS (
SELECT NAME, LENGTH(NAME) nameLength FROM EXAMPLE ORDER BY NAME
),
min_length AS (
SELECT NAME, nameLength FROM name_lengths WHERE nameLength = (SELECT MIN(nameLength) FROM name_lengths) LIMIT 1
),
max_length AS (
SELECT NAME, nameLength FROM name_lengths WHERE nameLength = (SELECT MAX(nameLength) FROM name_lengths) LIMIT 1
)

SELECT nl.NAME, nl.nameLength
FROM name_lengths nl
INNER JOIN min_length minl
ON minl.NAME = nl.NAME
UNION
SELECT nl.NAME, nl.nameLength
FROM name_lengths nl
INNER JOIN max_length maxl
ON maxl.NAME = nl.NAME;
```

 #### <a name="appendixapart10"></a>Appendix A - Part 10: Find Cities that starts with a,e,i,o or u

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'Abruzzo', 'IT', 'ABC', 100000),
(2, 'Roma', 'IT', 'DEF', 99999),
(3, 'Paris', 'FR', 'GHI', 100001),
(4, 'Lima', 'PE', 'JKL', 101001),
(5, 'Abruzzo', 'IT', 'ABC', 100000),
(6, 'Edinburgh', 'GB', 'MNO', 100000);

SELECT * FROM EXAMPLE;

┌───────┬───────────┬─────────────┬──────────┬────────────┐
│  ID   │   NAME    │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │  varchar  │   varchar   │ varchar  │   int32    │
├───────┼───────────┼─────────────┼──────────┼────────────┤
│     1 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     2 │ Roma      │ IT          │ DEF      │      99999 │
│     3 │ Paris     │ FR          │ GHI      │     100001 │
│     4 │ Lima      │ PE          │ JKL      │     101001 │
│     5 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     6 │ Edinburgh │ GB          │ MNO      │     100000 │
└───────┴───────────┴─────────────┴──────────┴────────────┘

SELECT DISTINCT NAME FROM EXAMPLE WHERE 
LOWER(NAME) LIKE 'a%' OR 
LOWER(NAME) LIKE 'e%' OR 
LOWER(NAME) LIKE 'i%' OR
LOWER(NAME) LIKE 'o%' OR
LOWER(NAME) LIKE 'u%';

┌───────────┐
│   NAME    │
│  varchar  │
├───────────┤
│ Abruzzo   │
│ Edinburgh │
└───────────┘

```

 #### <a name="appendixapart11"></a>Appendix A - Part 11: Find Cities that starts and ends with a,e,i,o or u with regex

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'Abruzzo', 'IT', 'ABC', 100000),
(2, 'Roma', 'IT', 'DEF', 99999),
(3, 'Paris', 'FR', 'GHI', 100001),
(4, 'Lima', 'PE', 'JKL', 101001),
(5, 'Abruzzo', 'IT', 'ABC', 100000),
(6, 'Edinburgh', 'GB', 'MNO', 100000);

SELECT * FROM EXAMPLE;

┌───────┬───────────┬─────────────┬──────────┬────────────┐
│  ID   │   NAME    │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │  varchar  │   varchar   │ varchar  │   int32    │
├───────┼───────────┼─────────────┼──────────┼────────────┤
│     1 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     2 │ Roma      │ IT          │ DEF      │      99999 │
│     3 │ Paris     │ FR          │ GHI      │     100001 │
│     4 │ Lima      │ PE          │ JKL      │     101001 │
│     5 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     6 │ Edinburgh │ GB          │ MNO      │     100000 │
└───────┴───────────┴─────────────┴──────────┴────────────┘

SELECT DISTINCT NAME FROM EXAMPLE WHERE regexp_matches(NAME, '^(?:[aeiouAEIOU]|[aeiouAEIOU].*[aeiouAEIOU])$');

┌─────────┐
│  NAME   │
│ varchar │
├─────────┤
│ Abruzzo │
└─────────┘
```

 #### <a name="appendixapart12"></a>Appendix A - Part 12: Find Cities that not starts and ends with a,e,i,o or u

```
CREATE TABLE EXAMPLE (ID INTEGER,NAME VARCHAR(17),COUNTRYCODE VARCHAR(3), DISTRICT VARCHAR(20), POPULATION INTEGER);

INSERT INTO EXAMPLE (ID, NAME, COUNTRYCODE, DISTRICT, POPULATION) VALUES
(1, 'Abruzzo', 'IT', 'ABC', 100000),
(2, 'Roma', 'IT', 'DEF', 99999),
(3, 'Paris', 'FR', 'GHI', 100001),
(4, 'Lima', 'PE', 'JKL', 101001),
(5, 'Abruzzo', 'IT', 'ABC', 100000),
(6, 'Edinburgh', 'GB', 'MNO', 100000);

SELECT * FROM EXAMPLE;

┌───────┬───────────┬─────────────┬──────────┬────────────┐
│  ID   │   NAME    │ COUNTRYCODE │ DISTRICT │ POPULATION │
│ int32 │  varchar  │   varchar   │ varchar  │   int32    │
├───────┼───────────┼─────────────┼──────────┼────────────┤
│     1 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     2 │ Roma      │ IT          │ DEF      │      99999 │
│     3 │ Paris     │ FR          │ GHI      │     100001 │
│     4 │ Lima      │ PE          │ JKL      │     101001 │
│     5 │ Abruzzo   │ IT          │ ABC      │     100000 │
│     6 │ Edinburgh │ GB          │ MNO      │     100000 │
└───────┴───────────┴─────────────┴──────────┴────────────┘

SELECT DISTINCT NAME FROM EXAMPLE WHERE (LOWER(NAME) NOT LIKE 'a%' AND LOWER(NAME) NOT LIKE 'e%' AND LOWER(NAME) NOT LIKE 'i%' AND LOWER(NAME) NOT LIKE 'o%' AND LOWER(NAME) NOT LIKE 'u%') AND (LOWER(NAME) NOT LIKE '%a' AND LOWER(NAME) NOT LIKE '%e' AND LOWER(NAME) NOT LIKE '%i' AND LOWER(NAME) NOT LIKE '%o' AND LOWER(NAME) NOT LIKE '%u');

┌─────────┐
│  NAME   │
│ varchar │
├─────────┤
│ Paris   │
└─────────┘

```

COuld be

```
SELECT DISTINCT NAME FROM EXAMPLE WHERE (
CASE WHEN LOWER(NAME) LIKE 'a%' OR LOWER(NAME) LIKE 'e%' OR LOWER(NAME) LIKE 'i%' OR LOWER(NAME) LIKE 'o%' OR LOWER(NAME) LIKE 'u%' THEN 1 ELSE 0 END +
CASE WHEN LOWER(NAME) LIKE '%a' OR LOWER(NAME) LIKE '%e' OR LOWER(NAME) LIKE '%i' OR LOWER(NAME) LIKE '%o' OR LOWER(NAME) LIKE '%u' THEN 1 ELSE 0 END) = 0;

┌─────────┐
│  NAME   │
│ varchar │
├─────────┤
│ Paris   │
└─────────┘
```

 #### <a name="appendixapart13"></a>Appendix A - Part 13: Using more than One order By

```
CREATE TABLE STUDENTS (ID INTEGER,Name VARCHAR(17),Marks INTEGER);

INSERT INTO STUDENTS (ID, Name, Marks) VALUES
(1, 'Ashley',81),
(2, 'Samantha', 75),
(3, 'Julia', 76),
(4, 'Belvet', 74),
(5, 'Bobby', 88),
(6, 'Robby', 90);

SELECT * FROM STUDENTS;

┌───────┬──────────┬───────┐
│  ID   │   Name   │ Marks │
│ int32 │ varchar  │ int32 │
├───────┼──────────┼───────┤
│     1 │ Ashley   │    81 │
│     2 │ Samantha │    75 │
│     3 │ Julia    │    76 │
│     4 │ Belvet   │    74 │
│     5 │ Bobby    │    88 │
│     6 │ Robby    │    90 │
└───────┴──────────┴───────┘

SELECT Name
FROM STUDENTS
WHERE Marks > 75
ORDER BY RIGHT(Name, 3) ASC, ID ASC;

┌─────────┐
│  Name   │
│ varchar │
├─────────┤
│ Bobby   │
│ Robby   │
│ Ashley  │
│ Julia   │
└─────────┘

```
