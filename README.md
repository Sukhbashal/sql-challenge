**sql_challenge**

**Scenario**

As a data engineer at the company, I was tasked with modeling, engineering, and analyzing data related to employees who worked at the company during the 1980s and 1990s. The objective was to design the database schema, import the relevant CSV files, and perform various SQL-based analysis tasks.

**Data Modeling**

To design the database schema, I reviewed the provided CSV files and identified the necessary columns and data types for each table. I determined the appropriate Primary Keys (PKs) and Foreign Keys (FKs) to establish relationships between the tables.

After understanding the data structure, I created an Entity Relationship Diagram (ERD) using the QuickDataBaseDiagram tool to visualize the database architecture.

**Data Engineering**

Using the ERD as a blueprint, I manually wrote SQL queries to create the tables in the PostgreSQL database. Although the QuickDBD tool offers an export feature for generating SQL queries directly from the ERD, I chose to write the queries myself to gain additional hands-on experience.

I created six tables, defining all necessary columns, data types, Primary Keys, and Foreign Key constraints to ensure data integrity. After the tables were set up, I used pgAdmin 4's "Import/Export Data" tool to import the data from the provided CSV files into the respective tables. Once the data was successfully imported, I proceeded to perform the required analysis.

**Data Analysis**

The following 8 analysis tasks were required:

**Employee Details:** List the employee number, last name, first name, sex, and salary of each employee.

**Employees Hired in 1986:** List the first name, last name, and hire date of employees who were hired in 1986.

**Managers of Each Department:** List the manager of each department along with their department number, department name, employee number, last name, and first name.

**Employee Department Details:** List the department number for each employee along with their employee number, last name, first name, and department name.

**Employees Named Hercules:** List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with "B".

**Employees in Sales Department:** List all employees in the Sales department, including their employee number, last name, and first name.

**Employees in Sales and Development Departments:** List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

**Last Name Frequency Counts:** List the frequency counts of all employee last names in descending order (i.e., how many employees share each last name).
