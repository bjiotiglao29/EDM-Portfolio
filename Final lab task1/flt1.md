## Final lab Task-1
Final Lab Task 1 - MySQL Basics
In this task, we used MySQL to create a functional database and learned how to properly write and execute the required SQL queries. We were tasked with creating multiple tables that represent a sample company, which were later linked through relationships.
These are the guide given by our instructor:

## Task 1: Create the employees table

Define employee_id as a unique integer, auto-increment, and primary key.
Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.

## Task 2: Create the departments table

Define department_id as a unique integer, auto-increment, and primary key.
Define department_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 3: Create the employee_departments table

Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
Set a composite primary key on the combination of employee_id and department_id.

## Task 4: Create the employee_projects table

Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
Define project_name as a VARCHAR (up to 255 characters), and make it not null.

## Task 5: Create the managers table

Define manager_id as a unique integer, auto-increment, and primary key.
Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.

## Query Statement
- Step - 1 Employee Table Query
- 
![1 - Copy](https://github.com/user-attachments/assets/1e13f544-0981-4937-834f-c82bb003b938)

- Step - 2 Department Table Query
- 
![2 - Copy](https://github.com/user-attachments/assets/a11a51df-5ca6-4094-b6c9-02461942f255)

- Step - 3 Employee Department Table Query
- 
![3 - Copy](https://github.com/user-attachments/assets/673c5cfb-08cc-45e3-86ad-462258a00f08)

- Step - 4 Project Table Query
- 
![4 - Copy](https://github.com/user-attachments/assets/dff9c221-95ae-4e94-b639-602c27006650)

- Step - 5 Managers Table Query
- 
 ![5 - Copy](https://github.com/user-attachments/assets/ecade4a3-23af-4d05-8ff8-10ce7df9ceac)

## Table Structures
- Step 1 - Employee Table Structure
- 
![6 - Copy](https://github.com/user-attachments/assets/c9986ac6-ade7-469e-b09b-66549b2de646)

- Step 2 - Department Table Structure
- 
![7 - Copy](https://github.com/user-attachments/assets/0aac10ce-b591-455e-9d44-882d7c6b97f5)

- Step 3 - Employee Department Table Structure
- 
![9 - Copy](https://github.com/user-attachments/assets/2a754f43-f0e8-4c25-a32f-4df65514a676)

- Step 4 - Project Table
- 
![10 - Copy](https://github.com/user-attachments/assets/afccb8ae-a5a4-452f-9e2d-8b8e504713b4)


- Step 5 - Managers Table Structure
- 
![10 - Copy](https://github.com/user-attachments/assets/50e08d87-75b7-41e6-a3a9-a9717a033136)

  ## Entity-Relational Schema

  - Relation Schema attached below
  
![11](https://github.com/user-attachments/assets/92fa8d3f-d5c0-43c7-88d0-d1f87333d392)
