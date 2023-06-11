# Module 2: Querying data in NoSQL databases

## Scenario

You are a data engineer at an e-commerce company. Your company needs you to design a data platform that uses MongoDB as a NoSQL database. You will be using MongoDB to store the e-commerce catalog data.

## Objectives

import data into a MongoDB database.  
query data in a MongoDB database.  
export data from MongoDB.  

## Tools / Software  

MongoDB Server  
MongoDB Command Line Backup Tools  

### 1 - Check the lab environment
Before you proceed with the assignment :

Check if you have the ‘mongoimport’ and ‘mongoexport’ installed on the lab, otherwise install them.  
Download the catalog.json file from https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DB0321EN-SkillsNetwork/nosql/catalog.json.

### 2 - Working with MongoDB
Task 1 - Import ‘catalog.json’ into mongodb server into a database named ‘catalog’ and a collection named ‘electronics’

### 3 - List out all the databases

### 4 - List out all the collections in the database catalog.

### 5 - Create an index on the field “type”

### 6 - Write a query to find the count of laptops

### 7 - Write a query to find the number of smart phones with screen size of 6 inches.

### 8 - Write a query to find out the average screen size of smart phones.

### 9 - Export the fields _id, “type”, “model”, from the ‘electronics’ collection into a file named electronics.csv
