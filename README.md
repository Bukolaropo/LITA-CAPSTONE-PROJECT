# LITA-CAPSTONE-PROJECT

## Project Title: Sales Performance Analysis for LITA Retail Store

## Project Overview
---
The data analysis aims to generate insight into the sales performance of the LITA retail store between year 2023 and 2024. By analysiing the various parametres I seek to gather insights as per the best performance from the data. This will enable us to tell compelling stories aroud the data and help the company makes reasonable decisions.

## Data Sources
---
The primary source of data used is Salesdata.csv tahat was provided by Incubator Hub.

## Tools Used
---
- Microsoft Excel [download here] (https.//www.microsoft.com)
  1. for data cleaning
  2. for analysis and
  3. for visualisation
- SQL - Structured Query Language for Querying of Data
- GitHub for Portfoli Building

## Exploratory Data Analysis
---
This involves the exploring of the Data to answer some questions about such as;
- What is the total quantity sold by product
- What istotal quantity sold by region
- What is total sales by product
- What is total sales by region
- What is montly sales
- What is average sales by product
- What is total revenue by region
- Which products are top sellers

## Data Analysis
---
Here some basic lines of code or queries were used for analysis. Such as,

SELECT * FROM SalesData;

--- 1. retrieve the total sales for each product category.---
SELECT Product, SUM(Sales) AS TotalSales
FROM SalesData
GROUP BY Product

EXEC sp_rename 'SalesData.TotalSales', 'Sales', 'COLUMN';

## Data Visualization

![image](https://github.com/user-attachments/assets/2df4a4f1-c097-4cc9-915a-3cd2aba6d189) ![image](https://github.com/user-attachments/assets/a54485c6-edc9-403a-8d07-1e8b03ca061f)




