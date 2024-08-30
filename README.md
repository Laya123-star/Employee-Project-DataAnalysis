# Employee-Project-DataAnalysis
# Project Tasks and Dataset Descriptions

# Dataset Attributes:

1) id: Unique identifier for the project head responsible for managing the project.
2) name: Name of the person handling the project.
3) gender: Gender of the project head (Male - M, Female - F).
4) city: Location of the project.
5) age: Duration in years for which the project will be active.
6) status: Current status of the project.
7) designation level: Position rank of the project head:
Excessive failures may result in a downgrade in designation grade.
A good reputation can lead to promotion to a higher designation level.
Designation scale:
a) 1 - Highest
b) 2, 3 - Mid positions
c) 4 - Lowest (exceeding 4 results in ineligibility for leading projects).
# Tasks Overview:

# Task 1:
Create three DataFrames as described above and save them as separate .csv files. For all subsequent tasks, use the saved .csv files.

# Task 2:
Address missing values in the "Cost" column of the Project DataFrame. Compute and replace missing values using a running average, applying a "For" loop.

# Task 3:
Split the "name" column in the Employee DataFrame into "First Name" and "Last Name" columns, then remove the original "name" column.

# Task 4:
Merge all three DataFrames into a single DataFrame named "Final."

# Task 5:
Add a new "Bonus" column to the Final DataFrame, granting a 5% bonus on project cost to employees who completed their projects.

# Task 6:
Demote the designation level by 1 for employees with failed projects. Remove records of employees whose designation level exceeds 4.

# Task 7:
Prefix "Mr." or "Mrs." to the first names based on gender and drop the gender column.

# Task 8:
Promote the designation level by 1 for employees aged over 29 years using an IF condition.

# Task 9:
Create a new DataFrame, "TotalProjCost," summarizing the total project costs for each employee with columns ID, First Name, and Total Cost.

# Task 10:
Display details of employees whose city names contain the letter "o."
