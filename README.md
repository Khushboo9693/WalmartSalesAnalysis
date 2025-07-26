# Walmart Sales Data Analysis

## About

This project focuses on analyzing Walmart sales data to gain insights into product sales trends and customer behavior. The dataset used in this analysis is from the Kaggle Walmart Sales Forecasting Competition( https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting).

Objective of project

The main goal of this project is to analyze Walmart’s sales data to understand:

The performance of different product lines. Strategies to optimize and improve sales performance.

About Data

The dataset was obtained from the Kaggle Walmart Sales Forecasting Competition. This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows:














Analysis List

   Product Analysis
   
Conduct analysis on the data to understand the different product lines, the products lines performing best and the product lines that need to be improved.

Approach Used

1.Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
  1.Build a database
  2.Create table and insert the data.
  3.Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are      filtered out.

2.Feature Engineering: This will help use generate some new columns from existing ones
  1.Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
  2.Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
  3.Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.

3.Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

4.Conclusion:

Business Questions To Answer

Generic Question
  1.How many unique cities does the data have? - 3
  2.In which city is each branch? - A , B , C

Product
 1. How many unique product lines does the data have? - 6
 2. What is the most common payment method? - Cash
 3. What is the most selling product line? - food and beverages
 4. What is the total revenue by month? (Jan , Feb , Mar)
 5. What month had the largest COGS? (Jan)
 6. What product line had the largest revenue? - food and beverages
 7. What is the city with the largest revenue? - C
 8. What product line had the largest VAT? - food and beverages
 9. Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
 10.What is the most common product line by gender? fashion women , health men
 11.What is the average rating of each product line? - food and beverges have highest and home and lifestyle have lowest

Revenue And Profit Calculations
$ COGS = unitsPrice * quantity $
$ VAT = 5% * COGS $
