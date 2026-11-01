# Practice1.sql

# Creating a Database
CREATE DATABASE database_name;

# Altering a Database
ALTER DATABASE database_name;
#can add the collation, encryption and read only.

# Deleting a Database
DROP DATABASE database_name;

# SELECT Function allows us to select a column from a table
#Eg.
SELECT `course name`
FROM `courses`;

# DISTINCT Function allow us to select unique values from a given column in a given table.
SELECT DISTINCT `course name`
FROM `courses`;

# AS Function allows us to use temporary name\abbreviations for column names or table names.
# AS function for column names.
SELECT `GPA` AS 'Grade Average'
FROM `student information`;

# AS Function for table names 
SELECT c.`course name`, s.`GPA`
FROM `courses` AS c,`student_information AS s;






