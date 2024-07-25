# Working with SQL to analyze emloyee data

## Working with SQL to analyze emloyee data

### I was hired two two weeks ago as a new data engineer at Pewlett Hackard (a fictional company). Presented to me now is my first major task, to do a 
### research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

### To get the information needed for this project, I designed tables to hold the data from the CSV files, imported the CSV files into a SQL database, and then answered quest about ### the data through SQL queries. Once I found the answers to my questions, I performed data modeling, data engineering, and data analysis, respectively.

### Data Modeling was performed by inspecting the CSV files for relationships with each other, in order to sketch an Entity Relationshop Diagram of the 
### tables. To create the Entity Relationship Diagram sketch, I used a free application tool found at (https://app.diagrams.net).

### For Data Enginnering, I used the provided information to create a table schema for each of the six CSV files.  The schema involved specifying the data types, primary keys, ### ### foreign keys, and other constraints. For the primary keys, I verified that the column was unique. Otherwise, a composite key was used, which takes two primary keys to uniquely ### identify a row. The data was then imported into a SQL table to work with.

### And finally, Data Analysis Tables were queried using SQL with certain joins on tables in order to answer the following:

###    List the employee number, last name, first name, sex, and salary of each employee.

###    List the first name, last name, and hire date for the employees who were hired in 1986.

###    List the manager of each department along with their department number, department name, employee number, last name, and first name.

###    List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

###    List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

###    List each employee in the Sales department, including their employee number, last name, and first name.

###    List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

###    List the frequency counts, in descending order, of all the employees thatshare each last name.

### The answers were concise, and just what they needed, I am happy to say.

