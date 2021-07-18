# Sales PowerBI Dashboard

## Business Request & User Stories

 @| As a (role) | I want (request / demand) | So that I (user value) |Acceptance Criteria
--- | --- | --- | --- |--- 
1 | Sales Manager | To get a dashboard overview of internet sales | Can follow better which customers and products sells the best | A Power BI dashboard which updates data once a day 
2 | Sales Representative | A detailed overview of Internet Sales per Customers and Products | Can follow up my customers that buys the most and who we can sell more to | A Power BI dashboard which allows me to filter data for each customer and products

## Data Cleansing & Transformation (SQL)
In order to achieve the required output from the data,below listed steps are executed.

1 Exploratory Data Analysis (to know about required fields and cleaning clutter)

2 Data Export

Note: DataSource and SQL Scripts are inculded in the "Data Source & SQL Scripts" folder.

## Data Model

Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget hsa been connected to FACT_InternetSales and other necessary DIM tables.

[![Data-Model.jpg](https://i.postimg.cc/x1XMvJz7/Data-Model.jpg)](https://postimg.cc/18Z8PzMc)


## Sales Management Dashboard
The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

### Sales Overview
[![Sales-Overview.jpg](https://i.postimg.cc/cCQ0yc2j/Sales-Overview.jpg)](https://postimg.cc/D4yt112d)

### Customer Details
[![Customer-Details.jpg](https://i.postimg.cc/HxkyLrdB/Customer-Details.jpg)](https://postimg.cc/LqGXC6q1)

### Product Details
[![Product-Details.jpg](https://i.postimg.cc/qRFzMQmv/Product-Details.jpg)](https://postimg.cc/CBjFcCT3)
