# Module 3: module3 Datawarehouse design, setup, and report

## Scenario

You are a data engineer hired by an ecommerce company named SoftCart.com . The company retails download only items like E-Books, Movies, Songs etc. The company has international presence and customers from all over the world. The company would like to create a data warehouse so that it can create reports like

total sales per year per country  
total sales per month per category  
total sales per quarter per country  
total sales per category per country  

You will use your data warehousing skills to design and implement a data warehouse for the company.

## Objectives

Design a Data Warehouse using the pgAdmin ERD design tool.  
Create the schema in the Data Warehouse

## Tools / Software

ERD Design Tool of pgAdmin  
PostgreSQL Database Server

### 1 - Design the dimension table softcartDimDate  
Using the ERD design tool design the table softcartDimDate. The company is looking at a granularity of a day. Which means they would like to have the ability to generate the report on yearly, monthly, daily, and weekday basis.

### 2 - Design the dimension table softcartDimCategory  
Using the ERD design tool design the table softcartDimCategory.

### 3 - Design the dimension table softcartDimItem  
Using the ERD design tool design the table softcartDimItem.

### 4 - Design the dimension table softcartDimCountry  
Using the ERD design tool design the table softcartDimCountry.
 
### 5 - Design the fact table softcartFactSales  
Using the ERD design tool design the table softcartFactSales.

### 6 - Design the relationships   
Using the ERD design tool design the required relationships(one-to-one, one-to-many etc) amongst the tables.

### 7 - Create the schema.  
Download the schema sql from ERD tool and create the schema in a database named staging.

## Scenario

You are a data engineer hired by an ecommerce company named SoftCart.com . The company retails download only items like E-Books, Movies, Songs etc. The company has international presence and customers from all over the world. You have designed the schema for the data warehouse in the previous assignment. Data engineering is a team game. Your senior data engineer reviewed your design. Your schema design was improvised to suit the production needs of the company. In this assignment you will generate reports out of the data in the data warehouse.

## Objectives
In this assignment you will:

Load data into Data Warehouse  
Write aggregation queries  
Create MQTs  
Tools / Software  
Cloud instance of IBM DB2 database  

### 1 - Load data into the Data Warehouse
In this exercise you will load the data into the tables.

Task 1 - Load data into the dimension table DimDate  
Task 2 - Load data into the dimension table DimCategory  
Task 3 - Load data into the dimension table DimCountry  
Task 4 - Load data into the fact table FactSales

### 2 - Queries for data analytics
In this exercise you will query the data you have loaded in the previous exercise.

### 3 - Create a grouping sets query  
Create a grouping sets query using the columns country, category, totalsales.

### 4 - Create a rollup query  
Create a rollup query using the columns year, country, and totalsales.

### 7 - Create a cube query  
Create a cube query using the columns year, country, and average sales.

### 8 - Create an MQT  
Create an MQT named total_sales_per_country that has the columns country and total_sales.
