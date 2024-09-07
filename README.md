## Project Tile: Churn Datasheet Project
Title: Analysing Churn Datasheet to answer business questions using Excel and powerBI

Author: Abiola Yussuf

Date: 2024-08-31

## Project Description
This is a datasheet that shows the analysis of a telecommunication, which makes me analyse the data from Churn Datasheet and Churn table both on Excel and powerBI to solve different business questions.
I imported the dataset to excel and powerBI from local disk respectively.

## Disclaimer: 

This is not real-world project but use for the purpose of learning to demostrate my skills in Excel and PowerBI

## Problem Statement.

The goal of this anlysis is to solve the following in DAX PowerBI query;

- The customers who left within the last month

- The services each customer has signed up for: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

- The customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical

- Demographic info about customers – gender, age range, and if they have partners and dependents

Also solve the following with PowerBI; building a top-level KPI dashboard for the executive team. Its purpose should be to allow them to quickly understand the company's performance in key areas, including:

- Total Revenue

- Subscribed Customer
  
- contract Services
  
- Customer details
  
## Skills and Concept Demonstrated:

- Excel
1. Data Cleaning
2. Data modeling

- PowerBI
1. Creating new column to calculate total price
2. Creating key performance indicators (KPIs) and other business calculations,
3. Data modelling
4. Using Dax to perform basic measures
5. Filters
6. Tooltips
7. Creating Dashboard

## Data Source
The data used for this work is gotten from Churn Datasheet. I studied the Schema, Objects related to the Schema, data dictionary and found the right tables for the analysis.

You can find a link to get started with installation and restoration of the database to your local machine. [here](https://cdn.theforage.com/vinternships/companyassets/4sLyCPgmsy8DA6Dh3/02%20Churn-Dataset.xlsx)

## Data Transformation

Firstly, I Imported the data from excel and  i did a data transfromation which make me clean and added new column in the data called Loyality column, Risk category. This two column where add with the help of new measure query. 

![Tranformated Data 1](https://github.com/user-attachments/assets/f911393e-830c-4484-b3de-5f693249f844)

![Transformed Data 2](https://github.com/user-attachments/assets/9ac3b948-e36e-45aa-b786-f9a904eb3026)

After the data transformation , I began to write several Dax function with divide and count to create measures with right metrics. Measures created name is "churn -unprivot group".

![churn new measure 1](https://github.com/user-attachments/assets/3652c709-e6f9-4adc-82d7-e5237f88d539)

![Churn new measure 2](https://github.com/user-attachments/assets/3e549a97-e5ae-4c28-aa04-93cef2efa596)

## Data Modelling
Tables were automatically joined by creating relationships with them, PowerBI does this intelligently. However, as someone that understands the dataset and want to get specific insights and information. 
I had to desmostrate my skill in this by removing the automation and did another model.

![Relationship table](https://github.com/user-attachments/assets/bf52f0e8-1f6b-4ddf-8b67-a6e3f6af6be4)

## PowerBI dashboard 

The help of the data transformation and data modeling, I created two dashboard know as churn dashboard and risk analysis dashboard which shows the following trends

- Yearly charge and monthly charge including average monthly charge and average yearly charge.

- Number of customers, Number of admin ticket, Number of tech ticket, Number of senior citizen, Number of dependants, Number of partners.
  
- Paperless billing, payment method, gender, internet services.
  
- Potential customer and type of contract.

![Churn Dashboard](https://github.com/user-attachments/assets/de325534-7473-4f5c-a04e-e47345cd5d5e)


![Risk analysis Dashboard](https://github.com/user-attachments/assets/f1f3ae4d-a11b-4d86-912b-28f3cbb3a612)

## Insight

- There are 2 catergory of internet services with the total revenue of $2.86M

- The internet service that place the highest monthly charges is Fiber optic with $283k

- The male gender have the highest percentage of subscriber with 51% 

- Electric check has the highest payment method with 57%

- There are high rate of paperless billing with over 59%

- There are 1869 subscriber who are still using the internet service out of 7043 customer

- The customers with the multiplelines are 45% and the customer with phoneservice are 91%

- The customer that are streaming the movies and streaming the Tv are on the same range of 44%

## Recommendation

There are no doubts that the Business is performing well as the subscribers are opting out of the telecomm service. However there is room for more improvement.

1) Increase tech support capacity for Fiber Optic customers and lower tech tickets per customer to 0.5

2) Increase sale of 1 and 2 year contracts by 5% each

3) Yearly increase of automatic payments by 5%

## Thank you for reading

I am open for entry-level data anlalyst role.

Let us have discussion about your company and industry now!

Welcome to my portfolio. This project demostrate my skill in Excel and PowerBI





