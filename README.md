Hospital Equipment Management System - PostgreSQL
📌 Project Overview
The Hospital Equipment Management System is a database project developed using PostgreSQL and managed through pgAdmin 4. The project stores and analyzes hospital patient records, department information, medical equipment usage, patient vital signs, hospital stay duration, and treatment costs. SQL queries are used to extract meaningful business insights that help improve hospital resource management and decision-making.

🎯 Project Objectives
Design a hospital equipment management database.
Store patient and equipment information efficiently.
Perform data analysis using SQL queries.
Generate business insights for hospital management.
Demonstrate PostgreSQL database operations using pgAdmin 4.

🛠️ Technologies Used
Database Management System: PostgreSQL
Database Administration Tool: pgAdmin 4
Query Language: SQL

📂 Database Table
Table Name
equipment

Columns
Column Name	Description
patient_id	Unique patient identifier
age	Patient age
department	Hospital department
admission_date	Date of admission
heart_rate	Heart rate (BPM)
bp_systolic	Systolic blood pressure
bp_diastolic	Diastolic blood pressure
oxygen_saturation	Oxygen saturation (SpO₂)
length_of_stay_days	Number of days admitted
equipment_used	Medical equipment assigned
treatment_cost_inr	Treatment cost (INR)

📊 Business Problems Solved
The project answers important hospital management questions, including:
Total number of admitted patients
Average patient age
Department-wise patient count
Most frequently used medical equipment
Total and average treatment costs
Longest hospital stay
Patients with abnormal vital signs
Department-wise equipment utilization
High blood pressure patient identification
Low oxygen saturation patient identification
Top five highest treatment costs
Department performance analysis

A total of 29 SQL business queries were developed to analyze the dataset.

📈 SQL Concepts Used
SELECT
WHERE
ORDER BY
GROUP BY
HAVING
Aggregate Functions
COUNT()
AVG()
SUM()
MAX()
MIN()
LIMIT
Subqueries
Date Functions

🚀 How to Run the Project
Install PostgreSQL.
Open pgAdmin 4.
Create a new PostgreSQL database.
Create the equipments table.
Import the dataset (CSV or SQL).
Open the Query Tool.
Execute the SQL queries.
View the generated reports and analysis.

📌 Project Outcome
This project demonstrates how PostgreSQL can be used to manage hospital databases and generate meaningful analytical reports. By executing SQL queries, hospital administrators can monitor patient health, optimize equipment usage, analyze treatment costs, and improve operational efficiency.

📚 Learning Outcomes
After completing this project, you will understand:
Database creation in PostgreSQL
Data management using pgAdmin 4
Writing SQL queries
Data filtering and aggregation
Business analytics using SQL
Healthcare database management
