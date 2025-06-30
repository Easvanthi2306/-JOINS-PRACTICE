# -JOINS-PRACTICE
Objective:
Practice different types of SQL joins including INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN to combine data from multiple tables in a meaningful way.
Deliverable: A set of SQL join queries with their respective outputs demonstrating how data from related tables can be merged and queried.

COMPANY: CODTECH IT SOLUTIONS

NAME: EASVANTHI S

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

DESCRIPTION:

Task-1: Joins Practice 
This SQL script demonstrates the practical use of various SQL JOIN operations using two simple and relatable tables: patients and appointments. The purpose of this task is to understand how different types of joins work when retrieving data from multiple related tables. This is a fundamental concept in relational databases and essential for performing accurate data analysis.

The first table created is patients, which contains the basic details of patients. It includes two columns: patient_id (the primary key) and patient_name. The table is populated with sample data for four patients: Arjun, Sneha, Kabir, and Megha.

The second table is appointments, which records appointment details including appointment_id, patient_id, doctor_name, and appointment_date. Here, patient_id serves as a foreign key to relate to the patients table. The inserted data includes appointments for patient IDs 1, 2, and 5. Patient ID 5 is intentionally not present in the patients table to demonstrate how joins behave when the relationship is missing.
The joins are tested with meaningful sample data that reflects real-world scenarios such as unmatched records and null handling. This makes it easier to understand how each type of join functions. Each query output highlights the differences between join types and shows how records are included or excluded based on the matching criteria.

This task serves as a strong foundation for understanding join operations in SQL. It is particularly useful for students, beginners, and database learners who are practicing SQL queries for projects or interviews. The code is clean, simple, and runs well in platforms like SQLFiddle, DB-Fiddle, or local SQL environments like MySQL Workbench and PostgreSQL.

In summary, this Task-1 script demonstrates INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN with meaningful examples, and prepares the learner for more complex multi-table queries in real database systems.

#OUTPUT:

![Image](https://github.com/user-attachments/assets/33f9ea9e-6a10-4330-81a8-b937508c0e36)

