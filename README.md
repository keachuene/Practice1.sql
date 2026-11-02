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

#02 November 2026
# Creating Tables.
CREATE TABLE table_name(
column 1 DATATYPE,
column 2 DATATYPE,
column 3 DATATYPE,
.
.
.
column n DATATYPE
);

# ASSIGNING NOT NULL values. The NOT NULL function does not allow null\missing values in that specific column.
CREATE TABLE table_name(
column 1 DATATYPE NOT NULL,
column 2 DATATYPE,
column 3 DATATYPE
);

# Assigning UNIQUE values. The UNIQUE values function does not allow duplicates within that specific column.
CREATE TABLE table_name(
column 1 DATATYPE NOT NULL,
column 2 DATATYPE,
column 3 DATATYPE,
UNIQUE(column 1));

# INSERT INTO Function allows us to insert values into the attributes\ columns.
INSERT INTO table_name(column1, column2, column3)
VALUES('value1', 'value2', 'value3');

# UPDATE Function allows us to update the existing values in the columns.
UPDATE table_name
SET( column1 = value1, column2 = value2, column3 = value3)
WHERE unique key = given values;






