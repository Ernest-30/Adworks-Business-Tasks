
## Introduction

The business management has requested for insights into the sales performance across products and customers. Below are the business tasks to be answered.
This data analysis project focuses on analyzing sales and customer data from Adventure works stores. The project aims to uncover insights, trends, and key performance indicators to answer business questions. The data source is the companys SQL Database and includes the following tables;
- Sales Table
- Product Category Table
- Product Subcategory Table
- Products Table
- Territory Table
- Customer Table
- Returns Table
- Calender Table

### Data Preparation:

- Cleaning and preprocessing the dataset to ensure data quality and consistency.
- Consolidating the sales table from different years into one Overall sales table
- Creating additional columns from exisitng data required for the analysis
- Segmenting the customers into different Age Groups and Income_segments
- Segmenting the customers based on Last purchase date

## Analysis
The analysis was done on SQL Server. Click [Here](https://github.com/Ernest-30/Adworks-Business-Tasks/blob/main/Adventure_works_task_query.sql) to view the complete analysis query

## Business Task

### Sales Performance:

1.	Calculate the year-over-year growth rate of sales revenue.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/955b040c-4ecc-444a-8174-32a5832e7a1c)

   Revenue grew by 45.58% in 2021 but dropped by -1.49% in 2022

   
2.	Calculate the total revenue generated by each product category.


Bikes	generated the highest revenue ($23,642,495) while Clothing generated the least revenue ($365,419)



3.	Determine the top 10 customers based on their total purchase amount.

   ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/b2e265b3-4ed5-4837-ad45-6cceea8dc2ca)

These are the top 10 customers.


5.	Identify the 5 most profitable product subcategory.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/0a12dafa-14e6-4631-b9f4-a093b608b487)

Road Bikes generated the highest profit ($4,368,347) hence it is the most profitable subcategory.



7.	Identify the seasonality of sales by analyzing monthly sales trends.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/8e3472aa-006a-4a27-964f-484cbc72f45b)

Revenue manintained an upward trajectory from January and peaks in June, then starts decling from July to November before it starts growing again. June recorded the highest revenue ($3,030,801)
making it the top performing month.



9.	Analyze the trend of sales profit over the years for each product category.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/b7bf203d-35d1-4c72-b16b-591bc972c044)

 Bikes generated the highest revenue year on year for the 3 years.


 
11.	Calculate the total revenue generated by each Continent.

   ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/9575bb54-1f12-4338-abe4-768ced164a14)

   North America generated the highest revenue making it the top performing Continent in terms of revenue generation.
   

 
13.	Analyze the trend of sales revenue over the years for each Country.

    ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/395a70f0-c644-4312-a393-fa8260d47136)


  Australia generated the highest revenue in 2020 and 2021, while United States generated the highest revenue in 2022  



## Product Performance:

1.	Analyze the return rate for each product category.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/84673a55-fcf8-4b10-a88c-1a05901e7240)

Bikes recorded the highest return rate, making it the category with the most returned products.



2. 	Identify the top-selling products in each product subcategory.

   ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/49bb7b7b-4c5d-41ae-a7fc-c3cf7fa0d543)



3.	Identify Top 10 cross-selling opportunities by analyzing frequently co-purchased products.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/993527c7-14e7-4572-ac7b-71763790beea)


   
4.	Identify Top 5 slow-moving products.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/dbcb56eb-f020-401a-9cf1-14547b3d1694)


   
5.	Analyze the Monthly distribution of order quantities to identify bulk purchase trends.

    ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/c1d6988e-e79b-4af2-bc55-58a3f0595616)

Quantity Sold manintained an upward trajectory from January and peaks in June, then starts decling from July to November before it starts growing again. June recorded the highest quantity sold (8,784)
making it the top performing month in terms of quantity sold.



## Customer Behavior :

1.	Identify the most profitable customer segments based on purchase history.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/ec138d75-7caa-4359-87c5-8f2708d70080)

Middle income (40001 - 80000 per annum) earners generated the highest profit. 



2.	Analyze the distribution of Customer Age groups per region.

	![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/68d23e3d-f5af-46b2-83c6-c44bfa10aabe)



3.	Calculate customer churn analysis distribution.

![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/0195bdbc-0fa6-4751-81f9-a8d623405872)

   Active segment recorded the highest number of customer segments while lost segment recorded the least number of customers.



4.	Identify the Educational level with the highest purchased units.

   ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/590ed8dc-ab4f-402e-a6a5-e6c4b8ca35df)

   Customers with Bachelors degree recorded the highest purchase units while customers under the partial high school level recorded the lowest.



5.	Calculate the Order distribution per customer occupation per weekday.

   ![image](https://github.com/Ernest-30/Adworks-Business-Tasks/assets/123366282/35730321-2c61-488c-a4b7-4591e89f0561)

