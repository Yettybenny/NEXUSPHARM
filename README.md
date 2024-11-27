# NEXUSPHARM REPORT

## INTRODUCTION

NexusPharm is a leading provider of animal drugs and supplements in Nigeria, operating across the six geo-political zones. Established in 2019, the company has been in business for four years (2019–2022) and 
has served a significant number of customers. As a data analyst, I was tasked with analyzing the available data to create the following reports:

- Executive Report
- Income Statement
- What-If Analysis
- Product Report
  
![Screenshot (132)](https://github.com/user-attachments/assets/20660593-fe69-446a-9117-8a42b1029261)

### About the Dataset:

The dataset comprises five tables: Customer, Returns, Product, Store, and Transaction, provided in Excel format. Data transformation and analysis were conducted using Microsoft SQL Server, 
while Power BI was used for visualization and reporting.



## Problem Statements

- Executive Report: Develop an executive-level report to provide insights into inventory, customer profitability, revenue trends, product sales, and return rates, 
   aimed at driving strategic business decisions.
- Income Statement: Generate a detailed income statement that highlights key financial metrics, including revenue, net profit, operating expenses, and gross margin. Provide a month-over-month breakdown 
to track financial performance.
- What-If Analysis: Perform a scenario analysis to assess the impact of price adjustments on critical financial metrics such as revenue, net profit, and gross margin. Simulate price increments 
ranging from 0.1% to 1%.
- Product Report: Provide a comprehensive product performance analysis to optimize strategy and improve profitability.

## Tools Used

- SQL Server: For data transformation and analysis.
- Power BI: For data modeling, visualization, and reporting.

## Process Workflow

1. Imported the dataset into SQL Server.
2. Transformed and analyzed the data using SQL.
3. Imported the cleaned data into Power BI.
4. Modeled the data to establish relationships between tables.
5. Created DAX measures to enhance analysis.
6. Designed a wireframe for the reports.
7. Built interactive and user-friendly reports.

## Key Insights

  - KPIs: Revenue, Gross Profit, Units Sold, and Percentage Returns.

    
![Screenshot (133)](https://github.com/user-attachments/assets/d82a8560-fa0d-4839-8eb7-ea695bea4c32)

  - The highest revenue was recorded in June, with a total of ₦3.24 billion while the lowest revenue was recorded in December, at ₦1.90 billion.

  - Class J recorded the highest units sold, totaling 461,000 units, followed by Class A with 415,000 units. The product Hydromorphone was the most profitable but also had the highest return rate.


![Screenshot (134)](https://github.com/user-attachments/assets/45a89bcd-33e6-4f34-bd09-1cd4fc67a315)

  - Kaduna generated the highest revenue, totaling ₦11.7 billion, followed by Lokoja (₦7.3 billion) and Uyo (₦5.2 billion).

  - The Little Beekeeping company generated the highest revenue, totaling over ₦214 million.

  - The Lokoja warehouse had the lowest stock availability, with 35.99% of stock remaining, followed by Uyo at 33.29%.

    
![Screenshot (135)](https://github.com/user-attachments/assets/f601c55c-1d20-4115-b13f-c47cb98bdb3b)

  - Monthly trends for Operating Income, Operating Expenses, Gross Margin, and Revenue were analyzed.
  
  - Hydromophone which is the product with the highest profit was also the recorded as the product with the highest number of returns

## Recommendations

1. Restocking Strategy: Lokoja and Uyo, despite being top-performing locations, have the lowest stock availability. Restocking these locations is essential to meet customer demand.

2. Seasonal Strategy: June consistently recorded the highest revenue. The factors contributing to this performance should be identified and replicated in other months to maximize revenue.

3. Price Adjustment: The What-If analysis revealed that a 50% price increase would result in revenues of ₦42.68 billion and net income of ₦34.20 billion. A gradual price adjustment strategy
   can be tested to evaluate market response before implementing major changes.

4. Cross-Selling: Products with lower sales can be bundled with high-performing products to boost overall sales.

5. Return Rate Investigation: The top five most profitable products also have the highest return rates. Investigating the reasons behind these returns and addressing them could significantly
   increase revenue and reduce losses.

6. Implementing a slight price increase of 0.1 can positively impact net income and gross margin, but efforts should also be directed towards addressing the reasons for returns to minimize their
   impact on overall profit. Additionally, conducting regular reviews of expenses and exploring opportunities for cost optimization can further enhance financial performance.

## Project Link: https://app.powerbi.com/view?r=eyJrIjoiYTkzMDFlYzQtNWI1OS00YTE0LWIwYWMtNzQwM2UyNzRhOWQ2IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9
