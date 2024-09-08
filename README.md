# SQL_Practice_01- Computer Manufacturers and Products Database
This SQL script provides a comprehensive set of queries and operations for managing and interacting with a database containing manufacturers and products. Here is a breakdown of what each query or operation achieves:

Creation of Manufacturers and Products Tables:

Manufacturers table holds information about manufacturers with a unique code and name.

Products table holds product details (name, price, and manufacturer). It includes a foreign key that references the Manufacturers table to link each product with its manufacturer.
Inserting Data:

Sample data is inserted into both Manufacturers and Products tables. These inserts define various manufacturers and products with associated prices and manufacturers.
Exercises with Queries:

Exercise 1-2: Fetch product names and prices from the Products table.

Exercise 3-4: Filter products by price criteria (<= 200, between 60 and 120).

Exercise 5: Display product names with prices in cents.

Exercise 6-7: Compute the average price of all products and products by a specific manufacturer.

Exercise 8-9: Count products with a price above a threshold and order the results by price and name.

Exercise 10-11: Join Products and Manufacturers tables to combine data about products and their manufacturers.

Exercise 12-14: Compute the average price for each manufacturer and filter by average price greater than or equal to 150.

Exercise 15: Find the cheapest product in the store.

Exercise 16: Find the most expensive product of each manufacturer.

Exercise 17: Find manufacturers with average product prices above $145 and at least two different products.
Data Modification:

Exercise 18: Insert a new product (Loudspeakers) into the Products table.

Exercise 19: Update the name of a product (Laser Printer).

Exercise 20-21: Apply a 10% discount to all products and to products above a specific price.

These queries cover a broad range of SQL operations, including basic selection, filtering, aggregation, updates, and joins.

# SQL_Practice_02 - Employee Management Database
This project provides a set of SQL queries for managing an employee and department database. The script includes SQL statements for creating tables, inserting sample data, and performing various operations like data retrieval, updating, and deletion. The database schema is designed to store and manage employees' information and their associated departments, budgets, and other details.

Database Structure

Tables

Departments:

Code: Unique identifier for each department.

Name: Name of the department.

Budget: Budget allocated to the department.

Employees:

SSN: Unique identifier (Social Security Number) for each employee.

Name: First name of the employee.

LastName: Last name of the employee.

Department: The department code the employee belongs to (foreign key referencing the Departments table).

Relationships
Each employee belongs to a department, represented by the foreign key Department that references the Code column in the Departments table.

SQL Operations
The script supports a variety of SQL operations, including:

Data Retrieval:

Select the last names of employees.

Select unique last names of employees.

Retrieve employee data based on specific conditions (e.g., last name, department).

Perform JOIN operations to fetch related data from multiple tables (e.g., employee details with department information).

Aggregate Functions:

Calculate the sum of the budgets of all departments.

Count the number of employees in each department.

Subqueries:

Select departments with a budget greater than the average.

Select employees working in departments with specific criteria (e.g., second-lowest budget).

Inserts:

Add new departments and employees.
Updates:

Modify department budgets (e.g., reduce by 10%).

Reassign employees to different departments.

Deletions:

Delete employees based on department or budget conditions.
