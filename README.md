# Sales Performance Analysis

## Overview
 The sales performance analysis  provides an overview of the sales data dashboard created using Power BI, which covers sales data from 2003 to 2005. The dashboard offers comprehensive insights into monthly sales performance, total sales, ordered value and revenue, helping stakeholders understand key metrics and trends.

 ## Key Insights
1.Total Sales
10.03 million 

2.Average Order Value (AOV)
$2.94 thousand

3.Total Revenue
$8.29 million

4.November consistently recorded the highest sales for two years.

5.Classic Cars have the highest sales volume among all product categories.

6.Orders Shipped: 2566 orders

Sales Cancelled: 60 orders

## Measures Used

Average Order Value (AOV) = AVERAGEX(sales_data_sample, sales_data_sample[QUANTITY ORDERED] * sales_data_sample[PRICE EACH])

Total Sales Revenue = SUMX(sales_data_sample, sales_data_sample[QUANTITY ORDERED] * sales_data_sample[PRICE EACH])

## Conclusion
By leveraging this dashboard, stakeholders can make data-driven decisions to optimize sales strategies and improve overall performance.
