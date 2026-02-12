# Employee-Salary-Management-System-PostgreSQL


## Project Description
This mini project is a simple Employee Salary Management System created using PostgreSQL.

It creates an `employees` table that stores:
- Employee ID  
- Name  
- Base Salary  
- Bonus  
- Total Salary  

A trigger function automatically calculates the `total_salary` by adding `base_salary` and `bonus` whenever a record is inserted or updated.

The trigger runs **before INSERT or UPDATE** operations to ensure salary data is always accurate.

The project inserts records of 10 employees and displays their salary details using a SELECT query.

---

## Features
- PostgreSQL database
- Trigger function for automatic salary calculation
- Insert employee records
- View complete salary data
- Prevents manual calculation errors

---

## Technologies Used
- PostgreSQL
- SQL (DDL, DML, Triggers, Functions)

---

## Project Structure
Employee-Salary-Management-System/
│
├── README.md
├── database.sql
└── output.txt


---

## How to Run
1. Open PostgreSQL (pgAdmin or psql)
2. Run the `database.sql` file
3. Execute:
```sql
SELECT * FROM employees;
