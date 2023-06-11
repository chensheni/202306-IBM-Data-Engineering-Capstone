# Module 3: 

Scenario

You are a data engineer hired by an ecommerce company named SoftCart.com . The company retails download only items like E-Books, Movies, Songs etc. The company has international presence and customers from all over the world. The company would like to create a data warehouse so that it can create reports like

total sales per year per country  
total sales per month per category  
total sales per quarter per country  
total sales per category per country  

You will use your data warehousing skills to design and implement a data warehouse for the company.

Objectives

Design a Data Warehouse using the pgAdmin ERD design tool.  
Create the schema in the Data Warehouse

Tools / Software

ERD Design Tool of pgAdmin  
PostgreSQL Database Server

1 - Design the dimension table softcartDimDate  
Using the ERD design tool design the table softcartDimDate. The company is looking at a granularity of a day. Which means they would like to have the ability to generate the report on yearly, monthly, daily, and weekday basis.

2 - Design the dimension table softcartDimCategory  
Using the ERD design tool design the table softcartDimCategory.

3 - Design the dimension table softcartDimItem  
Using the ERD design tool design the table softcartDimItem.

4 - Design the dimension table softcartDimCountry  
Using the ERD design tool design the table softcartDimCountry.
 
5 - Design the fact table softcartFactSales  
Using the ERD design tool design the table softcartFactSales.

6 - Design the relationships   
Using the ERD design tool design the required relationships(one-to-one, one-to-many etc) amongst the tables.

7 - Create the schema.  
Download the schema sql from ERD tool and create the schema in a database named staging.
