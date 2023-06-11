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
Start MySQL server.  

2 - Design the OLTP Database  
Task 1 - Create a database.  
Create a database named sales.  

3 - Design a table named sales_data.  
Design a table named sales_data based on the sample data given.  
Create the sales_data table in sales database.

4 - Load the Data  
Download the file oltpdata.csv from https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0321EN-SkillsNetwork/oltp/oltpdata.csv  
Import the data from oltpdata.csv into sales_data table using phpMyAdmin.

5 - List the tables in the database sales.  
Take a screenshot of the command you used and the output.

6 - Write a query to find out the count of records in the tables sales_data.  

7 - Create an index  
Create an index named ts on the timestamp field.

8 - List indexes  
List indexes on the table sales_data.

9 - Write a bash script to export data.  
Write a bash script named datadump.sh that exports all the rows in the sales_data table to a file named sales_data.sql
