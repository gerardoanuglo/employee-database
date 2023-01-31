# sql-challenege

## Background
It’s a beautiful spring day, and it’s been two weeks since I was hired as a new data engineer at Pewlett Hackard. My first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remains of the database of employees from that period are six CSV files.

I performed data modeling, data engineering, and data analysis.

### Data Modeling 

I inspected the CSv files and sketched out an Entity Relationship Diagram of the tables. ERDs provide a visual starting point for database design and help determine information system requirements.

<img width="646" alt="Screenshot_20230130_055647" src="https://user-images.githubusercontent.com/85320743/215646105-391578df-09de-4a51-89b1-3167c149bc28.png">

### Data Engineering

I created a table schema for each of the six CSV files and imported the files into their corresponding tables. The departments, employees, and titles tables have primary keys, they are values that uniquely identify each row in a table. The other three tables have composite keys, which takes two primary keys to uniquely identify a row. 

<img width="498" alt="Screenshot_20230130_060601" src="https://user-images.githubusercontent.com/85320743/215646157-26be1c12-b7b2-44e5-bb90-320a56cac9de.png">

## Data Analysis

### The queries for these questions are located in the file SQL_queries.

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency count of employee last names (i.e., how many employees share each last name) in descending order.
