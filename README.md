# Project Background
TechPlay is an international e-commerce retailer that primarily sells electronic products in a B2C (Business-to-Consumer) environment

The company's data extends from 2019 to early 2021. It includes _sales data_, _marketing data_, _product data_, and _customer data_.
The company has seen a decline of sales in 2021, and along with finding areas of improvement, they want to know whether the cause of this decline can be pinpointed to an internal factor within the 4 data groups, or an external factor that could be adapted to.




The project seeks the root cause of the decline alongside any weaknesses by providing insights in:
+ **Sales Trend Analysis** from 2019 to 2020 to determine historical patterns before the decline to gain more context, particularly focusing on _Revenue, Quantity Sold, and AOV (Average Order Value)_.
+ **Regional Analysis** To evaluate sales and demographics by region
+ **Customer Analysis** To Assess customer base and its impact on sales
+ **Product Analysis** To understand changes in performance and how products compare with each other.

This analysis was encapsulated in two interactive Tableau dashboards: A customer dashboard, and a sales dashboard, which can be found **here**.\
The cleaned Excel file, which contains documentation for the cleaning process, can be found **here**.

# Data Structure
The dataset provided by TechPlay consists of an **Orders table** containing _21864_ rows and a **region table** containing _192_ rows\
‎ \
‎ 
![image alt](https://github.com/tamerwe/project/blob/main/dataStructure.png?raw=true)\
Rigorous quality checks were conducted on the data before beginning the analysis, as documented in the prior **Excel Link**

# Executive Summary
### Overview of Findings
TechPlay's revenue noticeably surges at the start of 2020 and continues rising until reaching its peak in december, where it then sharply declines by the start of 2021. The timing of the decline, alongside the abnormal growth the company had seen in 2020 (With a **164%** increase in revenue and **30%** increase in AOV), suggests that both the peak and decline were broadly caused by the covid's impact on the market, with the decline marking a return to normalcy after the pandemic. There are, however, other factors notable factors and areas of improvement that the following sections will explore.

Below are the Tableau dashboards for Sales and Customers, both can be found **here**
![image_alt](https://github.com/tamerwe/project/blob/main/SalesDashboard.png?raw=true)
![image_alt](https://github.com/tamerwe/project/blob/main/CustomerDashboard.png?raw=true)

### Sales Analysis
+ Sales periodically spike in September and December, matching with the normal surges in sales associated with seasonality like Back-To-School (September) and Holiday season (December). Sales Peaked in December 2020, with $549,435 in revenue from 1,671 orders, compounding the seasonality with the impact of covid.
+ Sales sharply declined in January 2021 in response to the end of the holiday season and the start of the market returning to pre-pandemic levels, which is natural after the abnormal spike preceeding it.
+ The decline significantly slowed down in the following month, but in spite the decline, revenue for February 2021 is 97% higher than its pre-pandemic level in February 2019.
### Product Analysis
+ The product line's top 3 items (#1. 27k 4k gaming monitor, #2. Playstation 5 bundle, #3. Nintendo Switch) significantly outperform the rest of the items in revenue, meaning that revenue depends on these 'Superstar' and would fluctuate with their change.
+ In spite of being #2 in revenues, the Playstation 5 bundle is #5 in quantity sold, meaning that its profit is driven by its high price rather than the volume of sales.
+ Inversely, the Nintendo Switch outperforms the other products by a wide margin in the volume of sales, yet is only #3 in revenue, meaning it derives its value from the high volume of sales rather than price.
### Region Analysis
+ The United States leads all other countries as the most lucrative market in terms of both revenue and volume of customers, generating 70% of all revenue and containing 71.8% of all customers in 2020.
+ Europe, and particularly the United Kingdom make up the second largest market
+ In Comparison, the Latin America(5.6%) and Asia-Pacific(12.3%) regions lag behind.
**PUT IMAGE HERE**
### Customer and Marketing Analysis
+ TechPlay has 19,851 unique customers, with only 472 having ordered more than once, resulting in a very low customer retention of 2.4%.
+ Among the channels used for marketing, direct and affiliate yield the highest Average-Order-Value at $300~, and are the most popular channels for selling expensive products such as the Playstation 5 Bundle.
+ Email marketing, having the lowest AOV, is the most popular channel for selling the Nintendo Switch.
+ The 24in 4k gaming monitor is consistently the second most profitable in each of the marketing channels, and is the second best seller in all categories except E-mail. Its status as the company's overall most profitable product suggests that this balanced exposure between marketing channels is a factor in its success.
**PUT IMAGE HERE**
+ 90.5% of all purchases were made through the company's website rather than its mobile app, signaling a severe underutilization of the latter.
**PUT IMAGE HERE**
+ There's no wide margin between the values of the top 20 customers, indicating a lack of dependency on any 'Key' customers whose loss would otherwise impact the profits.
