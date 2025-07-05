## Description
Created an Expense tracker system by integrating Python with MySQL. Designed and created SQL table using SQL Shell, and implemented database connectivity to perform CRUD operations through Python in Jupyter Notebook. Ensured smooth data handling and real-time updates for tracking expenses.

## 🧾 Expense Tracker System
A simple and efficient Expense Tracker built using Python and MySQL, designed to record, manage, and analyze daily expenses directly from a Jupyter Notebook.

## 🚀 Features
📌 MySQL Integration: Seamless connection between Python and MySQL using mysql-connector-python.

🧮 CRUD Operations: Perform Create, Read, Update, and Delete operations on expense records.

🗂️ Structured Database: Two normalized tables (expense, user) with foreign key relationships.

🔄 Real-Time Updates: Changes made in Python reflect instantly in the MySQL database.

## 🛠️ Technologies Used
•	Python (Jupyter Notebook)

•	MySQL 8.0

•	SQL Shell (MySQL CLI)

•	mysql-connector-python library


## 🧱 Database Schema
### •	Database: expense_tracker

#### 1.	Table: expense

| Field       | Type          | Key         |
|-------------|---------------|-------------|
| id          | INT           | Primary Key, Auto Increment |
| Date        | DATE          |             |
| amount      | DECIMAL(10,2) |             |
| category    | VARCHAR(100)  |             |
| description | VARCHAR(255)  |             |

#### 2.	Table: user

| Field           | Type           | Key                |
|-----------------|----------------|--------------------|
| userid          | INT            | Foreign Key → expense(id) |
| Name            | VARCHAR(50)    |                    |
| Bank_acount_no  | VARCHAR(100)   | Primary Key        |
| Bank_name       | VARCHAR(50)    |                    |
| email           | VARCHAR(100)   |                    |

## 📦 How to Use
•	Open the expense tracker project.txt file and run the SQL commands manually in MySQL Shell to set up the database and tables.

•	Open the Expense Tracker project.ipynb notebook in Jupyter.

•	Execute the Python cells to interact with the MySQL database (perform insert, read, update, and delete operations).


## 📁 Project Files
•	Expense Tracker project.ipynb – Jupyter Notebook with Python code to manage expenses.                                                                                                                               
  (https://github.com/sonali2002-ui/python-sql-connectivity-ExpenseTrackerProject/blob/main/Expense%20Tracker%20project.ipynb)

•	expense tracker project.txt – SQL queries for creating the database and tables.                                                                                                                                      
  (https://github.com/sonali2002-ui/python-sql-connectivity-ExpenseTrackerProject/blob/main/expense%20tracker%20project.txt)
