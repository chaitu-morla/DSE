DSE
Introduction to SQL
Overview
This module introduces the fundamentals of Structured Query Language (SQL) and relational databases. It covers the basic concepts required to interact with Oracle databases and forms the foundation for writing SQL queries.

Topics Covered
Introduction to Databases
Relational Database Concepts
SQL Basics
Oracle Database Architecture
SQL Command Categories (DDL, DML, DCL, TCL)
SQL*Plus Environment
Skills Practiced
Understanding database concepts
Writing basic SQL statements
Working with Oracle SQL*Plus
Database
Oracle Database

Language
SQL

Retrieving Data Using the SQL SELECT Statement
Overview
This module focuses on retrieving data from Oracle database tables using the SELECT statement and related clauses.

Topics Covered
SELECT Statement
Selecting Specific Columns
Selecting All Columns
DISTINCT Keyword
Column Aliases
Arithmetic Expressions
DESCRIBE Command
Skills Practiced
Retrieving data from tables
Selecting required columns
Formatting query output
Database
Oracle Database

Language
SQL

Restricting and Sorting Data
Overview
This module demonstrates how to filter records using conditions and sort query results efficiently.

Topics Covered
WHERE Clause
Comparison Operators
Logical Operators
BETWEEN
IN
LIKE
IS NULL
ORDER BY
ASC and DESC
Skills Practiced
Filtering records
Pattern matching
Sorting query results
Database
Oracle Database

Language
SQL

Using Single-Row Functions to Customize the Output
Overview
This module explains Oracle single-row functions used to manipulate character, numeric and date values.

Topics Covered
Character Functions
Number Functions
Date Functions
Conversion Functions
NVL Function
CASE Expression
Skills Practiced
Data formatting
Handling NULL values
Date calculations
Database
Oracle Database

Language
SQL

Reporting Aggregated Data Using the Group Functions
Overview
This module covers aggregate functions used to summarize and analyze database records.

Topics Covered
COUNT()
SUM()
AVG()
MIN()
MAX()
GROUP BY
HAVING
Skills Practiced
Data summarization
Group-wise analysis
Aggregate reporting
Database
Oracle Database

Language
SQL

Using the Set Operators
Overview
This module demonstrates how to combine the results of multiple SQL queries using Oracle set operators.

Topics Covered
UNION
UNION ALL
INTERSECT
MINUS
Skills Practiced
Combining query results
Comparing datasets
Eliminating duplicates
Database
Oracle Database

Language
SQL

Displaying Data from Multiple Tables Using Joins
Overview
This module focuses on retrieving related data from multiple tables using different types of joins.

Topics Covered
Inner Join
Left Outer Join
Right Outer Join
Full Outer Join
Self Join
Cross Join
Skills Practiced
Writing multi-table queries
Understanding table relationships
Data integration using joins
Database
Oracle Database

Language
SQL

Using Sub Queries to Solve Queries
Overview
This module focuses on solving complex SQL problems using Oracle Subqueries. It covers different types of subqueries and operators used for advanced data retrieval.

Topics Covered
Nested Subqueries
Correlated Subqueries
Scalar Subqueries
EXISTS Operator
ANY Operator
ALL Operator
Inline Views
WITH Clause (Common Table Expression)
Hands-on Exercises
Employees working in the same department
Employees earning above average salary
Employees reporting to a specific manager
Employees working in a particular location
Top and least N salary queries
Department-wise salary analysis
Advanced query building using subqueries
Skills Practiced
Advanced SQL Query Building
Complex Data Retrieval
Query Optimization
Oracle Subqueries
Database
Oracle Database

Language
SQL

Using DDL Statements to Create and Manage Tables
Overview
This module demonstrates Data Definition Language (DDL) commands used to create, modify, and manage database objects in Oracle SQL.

Topics Covered
CREATE TABLE
CREATE TABLE AS SELECT (CTAS)
ALTER TABLE
ADD COLUMN
MODIFY COLUMN
RENAME COLUMN
DROP COLUMN
RENAME TABLE
DROP TABLE
TRUNCATE TABLE
COMMENTS
FLASHBACK TABLE
SQL*Plus Commands
Hands-on Exercises
Creating department and employee tables
Applying Primary Key and Foreign Key constraints
Altering table structures
Renaming tables and columns
Truncating and dropping tables
Flashback table operations
Managing comments on tables and columns
Skills Practiced
Database Schema Design
Table Management
Constraint Management
Oracle DDL Operations
Database
Oracle Database

Language
SQL

Manipulating Data
Overview
This module focuses on Data Manipulation Language (DML) operations in Oracle SQL. It demonstrates how to insert, update, delete, merge, commit, and rollback data while maintaining database consistency and integrity.

Topics Covered
INSERT Statement
UPDATE Statement
DELETE Statement
MERGE Statement
COMMIT
ROLLBACK
SAVEPOINT
Transaction Control
Multitable INSERT
Data Verification using SELECT
Hands-on Exercises
Creating tables using CTAS (Create Table As Select)
Inserting single and multiple rows
Updating employee salary based on conditions
Updating data using subqueries
Deleting records using conditions
Deleting records using subqueries
Using Multitable INSERT
Using MERGE for Insert and Update operations
Verifying data changes
Performing COMMIT and ROLLBACK operations
Understanding transaction management
User privilege and permission exercises
Skills Practiced
Data Manipulation
Transaction Management
MERGE Operations
Conditional Updates
Data Integrity
Oracle SQL DML Commands
Database
Oracle Database

Language
SQL

Stock Management System using PL/SQL
Description
This project demonstrates a simple Stock Management System using Oracle PL/SQL. It updates the stock quantity based on the transaction type and handles exceptions using User Defined Exception Handlers.

Features
Create STOCK table
Insert sample records
Accept Product Number, Transaction Type, and Transaction Quantity
Update stock for Receipt (R) transactions
Update stock for Issue (I) transactions
Handle invalid Product Number
Handle invalid Transaction Type
Table Structure
Column	Data Type
PNO	NUMBER
PNAME	VARCHAR2(30)
RATE	NUMBER
TR_QTY	NUMBER
Transaction Logic
R → Add transaction quantity to stock
I → Subtract transaction quantity from stock
Exception Handling
Product Number Not Found
Invalid Transaction Type
Technologies Used
Oracle SQL
PL/SQL
SQL*Plus
Output
Updates stock quantity successfully.
Displays appropriate messages for invalid inputs.
