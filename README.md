# Author: Peanut

# Class Activity 3: Software Packages & Database CRUD Operations 

## Question 1: Vertical vs. Horizontal Software 

### Vertical Software
- Vertical Software is designed for a specific industry or type of business. Example, Hospital management software, which helps hospitals manage patients, appointments and medical records.

### Horizontal Software 
- Horizontal Software is designed for general tasks that can be used by diffrent types of businesses. Example, Microsoft Excel, which businesses use for calculations, budgeting and managing information.

- The difference between the two above is that Vertical Software serves a specific industry, while Horizontal Software serves different industries.

## Question 2: Operating Sytems Modes

### Batch Processing
- Batch Processing involves collection data and processing it in groups without requiring immediate user interaction. Example, a company processing monthly employee salaries.

### Real-Time Processsing
- Real-Time Processing involves processing data immediately it is received. Example, a bank processing ATM transactions.

- The difference between the above two is that Batch processing handles data in groups, while real-time processing handles data as it occurs.


## Question 3: PostgreSQL DML Practical

### Database Creation
CREATE DATABASE company_db;

### Employees table
CREATE TABLE employees (
    id SERIAL PROMARY KEY,
    name VARCHAR(100),
    department VARCHAR(100),
    salary DECIMAL(10,20
);

### INSERT Operation
Added three employees records:
- Peanut Nkhumishe - IT - 150000
- Letlhogonolo Vincent - HR - 12000
- Kwando Baddest - Finance - 18000

### SELECT Operation
SELECT * FROM * employees
WHERE salary > 12000;

Retrieved employees earning above 12000.

### UPDATE Operation 
UPDATE employees 
SET salary = 155000
WHERE id = 1;

Peanut Nkhumishe's salary was updated to 155000.

### DELETE Operation
DELETE FROM employees 
WHERE id = 2;

Letlhogono;o Vincent's record was deleted.

### Final Records
SELECT * FROM employees;

final records:
- Peanut Nkhumishe - IT - 155000
- Kwando Baddest - Finance - 18000


