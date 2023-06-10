# Module 1: 

Scenario

You are a data engineer at an e-commerce company. Your company needs you to design a data platform that uses MySQL as an OLTP database. You will be using MySQL to store the OLTP data.

Objectives

design the schema for OLTP database.
load data into OLTP database.
automate admin tasks.

Tools / Software

MySQL 8.0.22
phpMyAdmin 5.0.4

1 - Check the lab environment
\bStart MySQL server.

2 - Design the OLTP Database
Task 1 - Create a database.
Create a database named sales.

Task 2 - Design a table named sales_data.
Design a table named sales_data based on the sample data given.



Create the sales_data table in sales database.

Take a screenshot of the sql statement you used and the output.

Name the screenshot as createtable.jpg. (images can be saved with either .jpg or .png extension)

Exercise 3 - Load the Data
Task 3 - Import the data in the file oltpdata.csv
Download the file oltpdata.csv from https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0321EN-SkillsNetwork/oltp/oltpdata.csv

Import the data from oltpdata.csv into sales_data table using phpMyAdmin.

Take a screenshot of the phpMyAdmin import status.

Name the screenshot as importdata.jpg. (images can be saved with either .jpg or .png extension)

Task 4 - List the tables in the database sales.
Take a screenshot of the command you used and the output.

Name the screenshot as listtables.jpg. (images can be saved with either .jpg or .png extension)

Task 5. Write a query to find out the count of records in the tables sales_data.
Take a screenshot of the command you used and the output.

Name the screenshot as salesrows.jpg. (images can be saved with either .jpg or .png extension)

Exercise 4 - Set up Admin tasks
Task 6 - Create an index
Create an index named ts on the timestamp field.

Task 7 - List indexes
List indexes on the table sales_data.

Take a screenshot of the command you used and the output.

Name the screenshot as listindexes.jpg. (images can be saved with either .jpg or .png extension)

Task 8 - Write a bash script to export data.
Write a bash script named datadump.sh that exports all the rows in the sales_data table to a file named sales_data.sql

Take a screenshot of the contents of the datadump.sh bash file command you used and the output.

Name the screenshot as exportdata.jpg. (images can be saved with either .jpg or .png extension)

End of assignment.
