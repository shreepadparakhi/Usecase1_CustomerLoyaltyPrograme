# Usecase1_CustomerLoyaltyPrograme
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a  risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry  and ramen.  Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant  has captured some very basic data from their few months of operation but have no idea how  to use their data to help them run the business. 

## Table of Contents
1. [Problem Statement](##problem-statement)
2. [Entity Relationship Diagram](##entity-relationship-diagram)
3. [Case Study Questions](##case-study-questions)

## Problem Statement: 
Danny wants to use the data to answer a few simple questions about his customers, especially 
about their visiting patterns, how much money they’ve spent and also which menu items are 
their favourite. Having this deeper connection with his customers will help him deliver a better 
and more personalised experience for his loyal customers. 
He plans on using these insights to help him decide whether he should expand the existing 
customer loyalty program - additionally he needs help to generate some basic datasets so his 
team can easily inspect the data without needing to use SQL. 
Danny has provided you with a sample of his overall customer data due to privacy issues - but 
he hopes that these examples are enough for you to write fully functioning SQL queries to help 
him answer his questions! 
Danny has shared with you 3 key datasets for this case study: 
- sales 
- menu 
- members 

## Entity Relationship Diagram:
![alt_text](https://github.com/shreepadparakhi/Usecase1_CustomerLoyaltyPrograme/blob/main/ERD.png?raw=true)

## Table description:

### Sales-
The sales table captures all customer_id level purchases with a corresponding order date 
and product_id information for when and what menu items were ordered.

![alt_text](https://github.com/shreepadparakhi/Usecase1_CustomerLoyaltyPrograme/blob/main/SalesTable.png?raw=true)

### Menu-
The menu table maps the product_id to the actual product_name and price of each menu 
item. 

