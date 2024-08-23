# Microsoft AdventureWorks Sales PowerBI Dashboard

## Overview
![Overall_dash](https://github.com/user-attachments/assets/b13af47b-3e86-4b71-b836-554d9432a608)
![Detailed_Dash](https://github.com/user-attachments/assets/a205cb67-8cdb-487a-a226-d9370ce2eba3)

### Project Plan: Business Demand Overview

The project was planned based on business request I have summarised in a tablee below:

- **Value of Change**: Visual dashboards and improved Sales reporting or forecasting.
- **Necessary Systems**: Power BI, CRM System
- **Other Relevant Info**: Budgets have been delivered in Excel for 2021


| No | As a (role)            | I want (request/demand)                                | So that I (user value)                                        | Acceptance Criteria                                              |
|----|------------------------|-------------------------------------------------------|---------------------------------------------------------------|------------------------------------------------------------------|
| 1  | Sales Manager          | To get a dashboard overview of internet sales          | Can follow better which customers and products sell the best   | A Power BI dashboard which updates data once a day               |
| 2  | Sales Representative   | A detailed overview of Internet Sales per Customers    | Can follow up my customers that buy the most and who we can sell ore to | A Power BI dashboard which allows me to filter data for each customer |
| 3  | Sales Representative   | A detailed overview of Internet Sales per Products     | Can follow up my Products that sell the most                  | A Power BI dashboard which allows me to filter data for each Product  |
| 4  | Sales Manager          | A dashboard overview of internet sales                 | Follow sales over time against budget                         | A Power BI dashboard with graphs and KPIs comparing against budget |


### Dataset

The dataset used is a subset of the Microsoft AdventureWorks Data Warehouse. I utilized SQL to clean and transform the relevant information, creating the following **data model**:

![Model](https://github.com/user-attachments/assets/31541329-8195-4236-8c68-ef530d38e828)

## SQL Queries

To extract and refine key information from the data warehouse, I used T-SQL queries. These queries were critical in building the dimensional and fact tables that underpin the data model.

- **Customer Dimensional Table Query**  
  This query was crafted to generate the Customer Dimensional Table, capturing vital customer information for detailed analysis.

  ![Customer_dim](https://github.com/user-attachments/assets/ff7a5e59-2c3d-48e5-9dc8-73596dcdd37a)

- **Product Dimensional Table Query**  
  This query is responsible for constructing the Product Dimensional Table, ensuring all pertinent product data is included for comprehensive analysis.

  ![Product_dim](https://github.com/user-attachments/assets/32af91d9-bc82-441d-8e22-29f1d3887728)

- **Internet Sales Fact Table Query**  
  This query was executed to build the Internet Sales Fact Table, which aggregates sales data for in-depth analysis.

  ![Internet_sales_fact](https://github.com/user-attachments/assets/520ff16b-a91b-4ab2-9fd1-428b565063da)

## Insights

- **Sales by Customers and Cities**  
  With the help of slicers and an interactive Azure map, you can analyze sales by customers and cities. Selecting a customer automatically updates the map to display their respective city. For instance, Les Uilles stands out as the highest-grossing city, with Lisa Cai being the top customer there. Moreover, it's clear that bikes are the leading product category in terms of sales.

  ![top_city](https://github.com/user-attachments/assets/50581943-525a-4fea-82fb-f863f247051c)



 




