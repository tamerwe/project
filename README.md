# Project Background
TechPlay is an international e-commerce retailer that primarily sells electronic products in a B2C (Business-to-Consumer) environment.

The company's data extends from 2019 to early 2021. It includes _sales data_, _marketing data_, _product data_, _customer data_, and _regional data_.
The company has seen a decline of sales in 2021, and along with finding areas of improvement, they want to know whether the cause of this decline can be pinpointed to an internal factor within the 5 data groups, or an external factor that could be adapted to.




The project seeks the root cause of the decline alongside any weaknesses by providing insights in:
+ **Sales Trend Analysis** to compare 2019 with 2020 to determine historical patterns before the decline and gain more context, particularly focusing on _Revenue, Quantity Sold, and AOV (Average Order Value)_.
  
+ **Regional Analysis** To evaluate sales and demographics by region.
  
+ **Customer Analysis** To Assess customer base and its impact on sales.
  
+ **Product Analysis** To understand changes in performance and how products compare with each other.

+ **Marketing Analysis** To determine if products are given adequate exposure or if there are untapped opportunities.


This analysis was visualized with two interactive Tableau dashboards: A customer dashboard, and a sales dashboard, which can be viewed [here](https://public.tableau.com/views/PortfolioProject1_17571626103620/CustomerDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

The cleaned Excel file, which contains documentation for the cleaning process, can be downloaded [here](https://github.com/tamerwe/project/blob/cf038a9cd5d09189110d9372e74a2ad2c07033e4/Techplay-Order-Data-Cleaned.xlsx).


# Data Structure
The dataset provided by TechPlay consists of an **Orders table** containing _21864_ rows and a **region table** containing _192_ rows.

‎ 
‎ 
![image alt](https://github.com/tamerwe/project/blob/main/dataStructure.png?raw=true)

Rigorous quality checks were conducted on the data before beginning the analysis, as documented in the prior [Excel File](https://github.com/tamerwe/project/blob/cf038a9cd5d09189110d9372e74a2ad2c07033e4/Techplay-Order-Data-Cleaned.xlsx).


# Executive Summary
### Overview of Findings
**TechPlay's revenue noticeably surges at the start of 2020 and continues rising until reaching its peak in december, where it then sharply declines by the start of 2021**. The timing of the decline, alongside the abnormal growth the company saw in 2020 (With a **164%** increase in revenue and **30%** increase in AOV), suggests that both the peak and decline were broadly caused by the covid's impact on the market, with the decline marking a return to normalcy after the pandemic. There are, however, other notable factors and areas of improvement that the following sections will explore.

_Below are the Tableau dashboards for Sales and Customers, both can be found [here](https://public.tableau.com/views/PortfolioProject1_17571626103620/CustomerDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)._
![image_alt](https://github.com/tamerwe/project/blob/main/SalesDashboard.png?raw=true)
![image_alt](https://github.com/tamerwe/project/blob/main/CustomerDashboard.png?raw=true)

### Sales Analysis
+ **Sales periodically spike in September and December, matching with the normal surges in sales associated with seasonality** like Back-To-School (September) and Holiday season (December). Sales Peaked in December 2020, with $549,435 in revenue from 1,671 orders, compounding the seasonality with the surge of sales resulting from covid.
  
+ **Sales sharply declined in January 2021 in response to the end of the holiday season and the start of the market returning to pre-pandemic levels**, which is natural after the abnormal spike preceding it.
  
+ The decline significantly slowed down in the following month, but in spite the decline, revenue for February 2021 is **97% higher** than its pre-pandemic level in February 2019.
### Product Analysis
+ **The product line's top 3 items (#1. 27k 4k gaming monitor, #2. Playstation 5 bundle, #3. Nintendo Switch) significantly outperform the rest of the items in revenue**; revenue heavily depends on these 'Superstar' products and fluctuates with their change.
  
+ **In spite of being #2 in revenues, the Playstation 5 bundle is #5 in quantity sold**, signaling it as a luxury product whose profit is driven by its high price rather than the volume of sales.
  
+ **Inversely, the Nintendo Switch outperforms the other products by a wide margin in the volume of sales, yet is only #3 in revenue**; it derives its value from the high volume of sales rather than a high price.
  
### Region Analysis
+ **The United States leads all other countries by a wide margin as the most lucrative market in both revenue and volume of customers**, generating 70% of all revenue and containing 71.8% of all customers in 2020.
  
+ **Europe, and particularly the United Kingdom** make up the second largest market.
  
+ **In Comparison,** the Latin America(5.6%) and Asia-Pacific(12.3%) regions lag behind.
  
![image_alt](https://github.com/tamerwe/project/blob/main/RegionSales.png?raw=true)
### Customer and Marketing Analysis
+ **TechPlay has 19,851 unique customers, with only 472 having ordered more than once**, resulting in a very low customer retention of _**2.4%.**_
  
+ **79.7% of all orders came direct marketing**, with all the other channels significantly lagging behind.
  
+ **Among the channels used for marketing, direct and affiliate yield the highest Average-Order-Value at $300~**, with most of the revenue generated by them stemming from premium products.
  
+ **The 24in 4k gaming monitor is popular, consistently ranking as the second best seller in each of the marketing channels**, And also ranking between first and second in revenue.
  
![image_alt](https://github.com/tamerwe/project/blob/main/top3.png?raw=true)

+ **90.5% of all purchases were made through the company's website rather than its mobile app**, exposing a severe underutilization of the latter.
  
![image_alt](https://github.com/tamerwe/project/blob/main/PurchasePlatform.png?raw=true)
+ **There's no wide margin between the values of the top 20 customers**. Since there's no dependency on these top customers, they weren't a factor in the 2021 sales decline.

# Recommendations
+ Collaborate with key departments to re-adjust to pre-covid levels of operations.
  - **The operations department:** manage inventory efficiently and prevent over-stocking as demand decreases after the pandemic
  - **The finance department:** forecast appropriate budgets that keep reduced revenues in mind.
    
+ TechPlay's mobile app - along with every marketing channel except direct marketing, **is severely underutilized; work closely with the marketing department to increase exposure to these channels**.
  
+ Historically, we've been **unable to maintain customer retention**, with very little of the customers gained during the 2020 covid spike staying in 2021. Cooperate with the **customer service department to provide quality experiences that convert one-time buyers into loyal customers**, and work with the **marketing department to provide deals that appeal to promotion-driven customers who otherwise wouldn't return**.
+ **Re-evaluate underperforming products** with the product department, such as the newly introduced **Dell gaming mouse, which only made .73% of the company's revenue during 2020**, and the **Acer Nitro V gaming laptop, which has failed to ever make more than 2% of the company's total revenue** through the 3 years it has been in stock.
  
+ TechPlay made **84.8% of all revenue from only 3 out of their 8 products**. The risk of sales fluctuating if any change were to happen to these products is exacerbated by technology's short life span caused by rapid innovation. **Work with the risk management department and the product department to lessen the impact** the top 3 items have on revenue, as well to achieve balance between the value of different items in the product line.
  
+ Despite being international, **TechPlay is heavily US-centric in both demographic and profit**. **Investing more heavily into the European market** _- where it has the best chance of succeeding due to the pre-existing customer base present -_ would be an opportunity to **both reduce the risks** associated with relying too much on one region, as well as **capturing a promising consumer base**.
