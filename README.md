# <p align="center" style="margin-top: 0px;"> 🍜 Case Study #1 - Danny's Diner 🍜
<div align="center"> <img src="https://github.com/user-attachments/assets/2ab8f43f-5e14-4965-908e-78b5e4db3dd0" alt="Image description" width="600"/> </div>

---

 
*Welcome to my solution for [Danny's Diner case study #1](https://8weeksqlchallenge.com/case-study-1/), part of the [8 Week SQL Challenge](https://8weeksqlchallenge.com/) hosted by Danny Ma. This project focuses on solving various SQL challenges related to Danny's Diner, a fictional restaurant. Below, you'll find the problem statement, my approach, and the SQL queries used to derive the solutions.*

*This repository contains my solutions for the 8 Week SQL Challenge, initiated by Danny Ma through the Data With Danny virtual data apprenticeship program, which consists of 8 different SQL challenges.*

*The solutions are coded in [MySQL](https://www.mysql.com/).*

---
## <p align="center"> Introduction 
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.

## <p align="center"> Problem Statement

Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues - but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

Danny has shared with you 3 key datasets for this case study:

- sales
- menu
- members

## <p align="center"> Entity Relationship Diagram (ERD)

![Screenshot 2024-07-30 230019](https://github.com/user-attachments/assets/4a4e5554-0aaa-48d8-93d4-82ba9cb5fbfa)


## <p align="center"> Table 1: sales
The `sales` table captures all `customer_id` level purchases with an corresponding `order_date` and `product_id` information for when and what menu items were ordered.
















# Case Study #1 - Danny's Diner 
Prepared By Aniruddha Biswas  
[<img src="https://github.com/user-attachments/assets/17f4e5f1-3600-46c2-b17e-c8df7b82d82d" alt="LinkedIn" width="70" height="70">](https://www.linkedin.com/in/aniruddha-biswas/)

## Case Study Questions
### 1. What is the total amount each customer spent at the restaurant?
### 2. How many days has each customer visited the restaurant?
### 3. What was the first item from the menu purchased by each customer?
### 4. What is the most purchased item on the menu and how many times was it purchased by all customers?
### 5. Which item was the most popular for each customer?
### 6. Which item was purchased first by the customer after they became a member?
### 7. Which item was purchased just before the customer became a member?
### 8. What is the total items and amount spent for each member before they became a member?
### 9.  If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
### 10. In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?

## Bonus Questions

### 11. Join All The Things: 
The following questions are related creating basic data tables that Danny 
and his team can use to quickly derive insights without needing to join the underlying tables using SQL.
Recreate the following table output using the available data:  
![aniruddha1](https://github.com/user-attachments/assets/c5ae97d5-2b72-4fc6-b4b4-7faf8e00eabc)

### 12. Rank All The Things
Danny also requires further information about the ranking of customer products, 
but he purposely does not need the ranking for non-member purchases 
so he expects null ranking values for the records when customers are not yet part of the loyalty program.  
![aniruddha2](https://github.com/user-attachments/assets/45f00449-2da4-42a0-a944-b6335916350d)




