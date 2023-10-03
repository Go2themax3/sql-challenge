# sql-challenge
Background
This repository is dedicated to a research project on employees employed by Pewlett Hackard during the 1980s and 1990s. The dataset comprises six CSV files which are remnants of the employee database from that period. The project involves data modeling, data engineering, and data analysis.
Repository Structure
.
├── EmployeeSQL/
│   ├── Data/                 # Folder containing the six CSV files
│   ├── ERD.png              # Entity Relationship Diagram
│   ├── table_schema.sql     # SQL schema creation script
│   ├── queries.sql          # SQL queries for data analysis
│   └── README.md
└── README.md
Setup and Installation
Clone this repository to your local machine:
git clone https://github.com/your_username/sql-challenge.git
Navigate to the EmployeeSQL directory.

Import the table_schema.sql in your SQL database system to set up the tables.

Load each CSV from the Data/ directory into its corresponding SQL table.

Tasks and Instructions
Data Modeling
Inspect the CSV files.
Sketch an Entity Relationship Diagram of the tables. The ERD sketch can be found as ERD.png.
Data Engineering
Create a table schema for each of the six CSV files, ensuring to specify data types, primary keys, foreign keys, and other constraints.
Import each CSV file into the corresponding SQL table.
Data Analysis
Execute the provided queries in queries.sql to:

Retrieve the employee number, last name, first name, sex, and salary of each employee.
List employees hired in 1986.
Identify the manager of each department.
List the department details for each employee.
List employees named Hercules with last names starting with B.
List employees in the Sales department.
Identify employees in both the Sales and Development departments.
Count the frequency of each last name in descending order.
Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss the changes you'd like to make.
