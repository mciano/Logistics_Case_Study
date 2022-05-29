# Logistics_Case_Study

## Overview of Project

This project has the main purpose to analyse Sales and metrics with a given dataset. Following pre-set questions, the analyst had to follow the guidance and show some findings using Business Intelligence tool.

Dashboard is available on. Tableau Public [Tableau_Marcio_Ciano](https://public.tableau.com/views/Logistics_Case_Study/Case_Study?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
## Purpose

The purpose of this analysis is to make visual the opportunities captured on the dataset, answer the questions and show "how" using Tableau.

## Questions

### 1 Using the product hierarchy data provided in the ‘Product’ tab, help the senior leader to understand which categories / sub-categories are driving sales trends for the past 2 years.

First of all to make this possible, Excel dataset was loaded on Tableau, then make the relationships between each sheet using a unique ID. 
As below picture Order Tab, People Tab, Product Tab, and Returns Tab, using the cardinality Many to Many.

![](/Resources/Images/data_source.png)

After having the relationship established between all tabs, was possible to jump into the first question: 

A horizontal bar chart was used to show the sales by Category and sub-category between the years 2017 and 2018. 
![](/Resources/Images/1_sales_cat_subcat.png)

Analyst Explanation: Sales has increased from 2017 to 2018 in all Category and Sub-Category overall, Phones in Technology and Chairs in Furniture are the outliers. 

### 2.  Return (# of order lines returned / total # of order lines) is particularly high or low for a given month in the past 2 years.  Can you tell what the drivers are for those outliers? 

The challenge to making the Ratio of Return was to make the calculated field (# of order lines returned / total # of order lines).
![](/Resources/Images/ratio_calculated_field.png)

![](/Resources/Images/total_orders.png)

![](/Resources/Images/total_return_order.png)

After the calculation being validated, was plotted the line chart: 

![](/Resources/Images/2_return_ratio_line_chart.png)

Analyst Explanation: The year of 2017 outliers was *January and October* and 2018 was *February and August*, where the return amount for these particular months was higher compared to the number of Orders.

### 3.  The senior leader has asked for a dashboard summarizing key metrics that would be refreshed monthly.  Typical ways of summarizing data are Sales by region, date, category/sub-category, and by state as a few examples. 

The KPI was based on Sales, showing a total of sales by Region, the filter was applied to each chart to have the relationship between all charts. Metrics of sales are shown by region as well as Category and Sub-Category and Sales map with a total of Sales for each State.

![](/Resources/Images/3_KPI.png)

### 4. If you had more time, what other visualizations or analysis might you do?  

If I had more time, I would have done more calculated fields to check the difference between one year to another, as well as check-in deep the Logistics Ship Mode by Shipped date, what was the weekly volume. 
Perhaps if the dataset had more fields was possible to analyze the distance from Distribution center to the final Customer, make the cost per mile, and check opportunities for consolidations. 


#

**Contact:**
**E-mail:** mciano@hotmail.co.uk

**LinkedIn:** https://www.linkedin.com/in/marciorciano/

