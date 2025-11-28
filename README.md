Data Cleaning & Analysis using Python
# Python-Fundamentals-Capstone-Project

## 📌Overview

The Python Fundamentals Capstone Project is a hands-on, end-to-end data manipulation and analysis project designed to simulate real-world data processing workflows.
Using three interconnected datasets—Employee Information, Seniority Levels, and Project Records—the project emphasizes creating, cleaning, transforming, merging, and analyzing data using Python, Pandas, and NumPy.

Throughout the tasks, you will:

• Load and structure raw data

• Handle missing values

• Apply running averages

• Split and transform columns

• Merge DataFrames

• Apply business rules (bonus, demotion, promotion)

• Aggregate total project costs

• Query employees based on conditions

This capstone strengthens your understanding of loops, conditional logic, dataframes, and essential data-handling techniques used in real-world data science scenarios.

## ⭐ Key Features
1. Data Creation & Saving

Build three Pandas DataFrames from the provided tables.

Save each DataFrame as a separate .csv file.

2. Data Cleaning

Detect missing values in the Project Cost column.

Replace missing values using a running average implemented with a for loop.

3. Data Transformation

Split the Name column into First Name and Last Name.

Remove the original Name column to maintain a clean structure.

4. Dataset Integration

Merge all three datasets into a unified master DataFrame named Final.

5. Business Logic Implementation

Add a 5% bonus for employees who completed their projects.

Demote designation level by 1 for employees associated with failed projects.

Remove records of employees whose designation level becomes greater than 4.

Add Mr./Mrs. prefixes based on gender and drop the Gender column.

Promote employees older than 29 years by increasing their designation level by 1.

6. Data Aggregation

Calculate the Total Project Cost for each employee.

Store aggregated results in a new DataFrame named TotalProjCost.

7. Filtering & Querying

Retrieve and display employee details where the City name contains the letter “o”.

## 🛠 Technologies Used
### 1. Python

Primary programming language used throughout the project.

### 2. Pandas

Used for:

Constructing DataFrames

Reading & writing CSV files

Merging datasets

Column operations (split, drop, rename)

Filtering, grouping, summarizing data

### 3. NumPy

Used for:

Numerical computations

Calculating running averages

Handling missing values


## ✔ Conclusion

The Python Fundamentals Capstone Project serves as a comprehensive introduction to real-world data handling using Python. By working through tasks involving data cleaning, transformation, merging, business rule implementation, and aggregation, this project helps solidify foundational skills essential for data analysis and data engineering roles.

Through practical use of Pandas and NumPy, you gain hands-on experience in managing messy datasets, applying logical conditions, and deriving meaningful insights. Completing this project demonstrates your ability to work with structured data, implement custom logic, and build clean, efficient workflows—making you better prepared for more advanced projects and real-world data challenges.
