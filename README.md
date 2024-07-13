# Business Insights 360 - Power BI

I have worked on this project as part of the [CodeBasics Power BI 2.0 Course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

Here's a link to my [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmZiYjgyNTYtNmEzMS00N2M0LTg5YjItNTUyZWNhMjIzMjBmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9) and my [Presentation Video]()

All icons used in the dashboard are created by [Freepik](https://www.flaticon.com/authors/freepik) at [Flaticon.com](https://www.flaticon.com)


## Problem Statement

AtliQ Hardware has become one of the fastest companies in the electronic goods market. While they grew substantially in the last few years, they had some bitter experiences in Latin America. They tried to establish their presence their by opening stores, but ended up suffering a huge loss because they made decisions based on their intuitions and a few surveys. In the annual strategic meeting, they decided to onboard data analytics into their company and make data-driven decisions. Previously, they have done some analysis using Excel files, but due to the companies substantial growth, analysis on Excel doesn't work for them anymore. 
AtliQ Hardware has hired a team to onboard data analytics into their company and bring transparency for accurate decision making. Their main competitor, Dell, is growing substantially and are giving a tough compeition to Dell, possibly because of their huge data analytics team who do anaylysis in customer demographic, consumtion patterns, income levels, and so on.


### Task Lists
You are one of the data analysts hired by AtliQ Hardwares and have been provided two datasets. You have been tasked with:

-  Creating a dashboard with the mock-up provided by shareholders
-  Having relevant information for each department in the country
-  Implementing changes suggesting by shareholders following the shareholder meeting


## Dataset Description
-  gdb041
    -  dim_customer : contains the name, unique ID, market, platform (Brick & Mortal or E-Commerce) and channel (Direct, Retailer, Distributor) for each customer
    -  dim_market : contains a list of each market, and the region and sub-zone they belong to
    -  dim_product : contains the name, variant, unique ID, category, segment, and divison of each product
    -  fact_forecast_monthly : contains the unique forecasted sales quantity for each customer and product on a specific date
    -  fact_sales_monthly : contains the amount sold of each product by each unique customer on a specific date
   
- gdb056
    -  freight_costs : contains the freight costs for each market in a fiscal year
    -  gross_price : contains the gross price of each unique product in a fiscal year
    -  manufacturing_cost : contains the manufacturing cost of each unique product in a fiscal year
    -  pre_invoice_deductions : contains the pre invoice discount given to each customer in a fiscal year
    -  post_invoice_deductions : contains the discount given to each customer, for each product on a specific date


## Dashboard Pages Description
-  Home Page : Contains a link to each of the views. Also contains a information and a support button in case the user requires assistance
-  Finance View : Contains a profit and loss statement for any of the filters selected and a trend graph for the selected item from the profit and loss statement
-  Sales View : Contains KPIs such as Net Sales and Gross Sales % for each of the customers to analyze the performance of, and discounts given to each customer.
-  Marketing View : Contains KPIs such as Gross Margin and Net Profit % for each of the products to analyze how well each product sold, and the expenses for each product.
-  Supply Chain View : Contains the Net Error and Forecast Accuracy % for each of the customers and products to help analyze how the inventory should be kept.
-  Executive View : Contains the Market Share and a general analysis on the top performing products by revenue and other key metrics.



## Key Analysis from Dashboard
-  The Sales Quantities are increasing and the business is growing globally, however the profitability of the business is still low due to the negative Net Profit %
-  Amazon, and the AtliQ stores have the highest amount of Net Sales with AtliQ Exclusive having one of the highest Gross Margin % among all the stores as well.
-  The Forecast Accuracy % has increased meaning the Supply Chain Team is making better predictions for managing the inventories.
-  Despite being a relatively new company, AtliQ Hardwares has had a huge spike in Market Share %, with the Market Share % increasing from 1% to almost 6% in just one year.
-  Despite the low profitability, AtliQ is making their presence known globally as shown by their portion of the market share and their spike in Net Sales, which is healthy for the         company in the long run
