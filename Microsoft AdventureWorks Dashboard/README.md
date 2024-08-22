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
The dataset is a subset of the Microsoft AdventureWorks Data warehouse. I used SQL to clean and transform the relevant information from the Data Warehouse and form the following data model.

For Instance, this is the query I used to get relevant facts from the Internet sales fact table:

This is the SQL Query used to extract the relevant information to form the customer dimensional table. 


