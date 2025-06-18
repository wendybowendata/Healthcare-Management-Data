# Healthcare-Management-Data

Project Title: Basic Healthcare Data Analysis
Project Description:
This project uses SQL to perform basic analysis on a simple healthcare dataset. The
dataset includes information about patients, their demographics, medical conditions,
and treatments. The project aims to provide insights into prevalent conditions, patient
demographics, and overall trends in patient care.

Project Structure:
healthcare_data_analysis/
├── README.md
├── data/
│ └── patients.csv
│ └── conditions.csv
│ └── treatments.csv
├── sql/
│ └── create_tables.sql
│ └── analyze_data.sql
Files:
1. README.md: Provides an overview of the project, instructions for setting up the
database, and guidance on running the SQL queries.
2. data/patients.csv: A text file (CSV format) containing patient demographic
information, including Patient ID, Name, Age, and Gender.
3. data/conditions.csv: A text file (CSV format) containing patient medical condition
information, including Patient ID, Condition Name, and Diagnosis Date.
4. data/treatments.csv: A text file (CSV format) containing patient treatment
information, including Patient ID, Treatment Name, and Treatment Date.
5. sql/create_tables.sql: An SQL script to create the necessary tables in your
database to store the data from the CSV files.
6. sql/analyze_data.sql: An SQL script containing queries to analyze the data and
extract insights.
README.md (Example Content):
markdown

# Basic Healthcare Data Analysis Project
## Project Overview
This project focuses on basic data analysis of a simulated healthcare dataset
using SQL. The project will explore patient demographics, common medical
conditions, and treatments.


## Dataset
The dataset includes three CSV files:
* `patients.csv`: Patient information (ID, Name, Age, Gender)
* `conditions.csv`: Patient medical conditions (Patient ID, Condition Name,
Diagnosis Date)
* `treatments.csv`: Patient treatments (Patient ID, Treatment Name,
Treatment Date)


## Setup
1. **Database:** Choose a database management system (e.g., MySQL,
PostgreSQL, SQL Server).
2. **Create Tables:** Execute the `create_tables.sql` script to create the
necessary tables in your database.
3. **Import Data:** Import the data from the CSV files into the
corresponding tables using your database tool import functionality.

## Analysis
Execute the queries in `analyze_data.sql` to perform the following analyses:
* **Query 1:** Count the number of patients by gender.
* **Query 2:** Find the average age of patients.
* **Query 3:** Identify the most common medical conditions.
* **Query 4:** List the treatments received by patients with a specific
condition.
* **Query 5:** Determine the number of treatments administered on a
particular date.
## Notes
* This is a simplified dataset for educational purposes.
* The SQL queries provided are basic and can be expanded for more in-depth
analysis.
