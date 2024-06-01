# E-commerce-Financial-Web-Traffic-Analysis
This project analyzes the financial metrics and web traffic of an online e-commerce store specializing in barefoot shoes. The objective is to measure website conversion and understand product sales and impact using SQL.

## 📊 SQL Code

To see the complete SQL code used for this analysis, please visit the [SQL Code](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/E-commerce%20Financial%20Web%20Traffic%20Analysis.ipynb)

## 🪟 Overview

The goal of this project is to analyze the current state of an e-commerce business selling barefoot shoes. The analysis focuses on measuring web conversion and using data to understand sales and product impact. 

Key metrics include:

* Sales Metrics: Evaluating gross sales, absolute profit margins, and identifying top-performing products.
* Web Traffic Metrics: Measuring web sessions, identifying the most effective ads and content, and understanding traffic sources and their impact on sales.

The company specializes in selling barefoot shoes and currently offers three models:

* Barefoot Running
* Barefoot Casual
* Barefoot Hiking
  
By analyzing these areas, we aim to provide actionable insights that can help improve the business strategy and drive growth.

## 🗃️ Dataset

The dataset consists of four CSV files:

* [order_items.csv:](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/Dataset/order_items.csv) Details of the items in each order, including prices and costs.
* [orders.csv:](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/Dataset/orders.csv) Information on the orders, including dates, users, and quantities.
* [products.csv:](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/Dataset/products.csv) Details of the products, including launch dates and names.
* [website_sessions.csv:](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/Dataset/website_sessions.csv) Information on web sessions, including traffic sources and devices.

## 🖇️ Model

Here is the relationship diagram of the tables used in this project:

![image](![image](https://github.com/IrisMejuto/E-commerce-Financial-Web-Traffic-Analysis/blob/main/Image/Model.png)

## ❓ Key questions the project answers

### Sales Analysis:

* ✅ What are the gross sales and absolute margins by year and month?
* ✅ What are the top 10 average gross sales by month and year? What do you observe?
* ✅ Which product has the highest sales in monetary terms (gross sales)?
* ✅ Which product has the highest profit margin?
* ✅ Can we determine the launch date of each product?
* ✅ Calculate the gross sales by year and the numeric and percentage margin of each product, ordered by product.
* ✅ What are the top 3 months with the highest gross sales?
  
### Web Traffic Analysis:

* ✅ Which ads or content have attracted the most sessions?
* ✅ Are sessions the same as users? What is the number of unique users?
* ✅ What is the number of users and sessions by source?
* ✅ Which sources have generated the most sales?
* ✅ Which months have attracted the most traffic?
* ✅ For the month with the highest traffic, what is the number of sessions from mobile and desktop?
* ✅ Which campaigns have generated the most profit margin by product?
  
## ⭐ Conclusions

### Sales:

* The product "Barefoot Running" generated the highest sales and profit margin.
* Specific months and campaigns significantly influence sales trends.
  
### Web Traffic:

* Most traffic comes from "brand awareness" campaigns on gsearch.
* There is a notable difference between sessions and unique users.
