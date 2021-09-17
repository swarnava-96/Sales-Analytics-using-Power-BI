# Sales-Analytics-using-Power-BI

### Goal: The Goal of this project was to create a sales analytics dashboard for a custom superstore and analyse the profit, loss and the areas of improvement.

### About the Project: The entire project was performed using Microsoft Power BI Desktop. Initial step
was to import the data set into Power BI. The data set was in the form of excel workbook (global_superstore_2016). 
The Data set consists of three tables or sheets namely Orders, People and Returns. Each contains many features like
Date of Order, Date of DElivery, Country, Customer Names, etc. The following are the steps of my analysis and the corresponding
insights are displayed in the screenshot below:

1. A custom column named, Delivery days was calculated by subtracting order date from ship date.
2. Cards were made for total sales, total quantity and average delivery days and Return Orders.
3. Year was extracted from order date and a custom column was created for that. 
This helped to create the Year slicer.
4. Conditional column was created for the Returns Table and Return Orders was created 
on Returned column by placing a condition. When Yes, then 1, else 0.
5.  Map was created setting location Country and size Sales.
6. A clustered bar chat was created placing product name on the Axis and Profit on values.
This chart shows the top 7 products by profit. Similarly, bottom 7 products that gave maximum loss 
was calculated.
7. A pie chart was created putting sales in the value and legend as Sales.
8. A Donut chart was created putting sales in the value and legend as Markets.

My suggestions after working on this project would be that the store should focus on increasing its store chain
into other countries as well. The store should try to retain its most profitable customers by providing exciting deals.
The products that gave the least amount of profit should be sold at a discounted rate or should be discarded.

### A Glimpse of the Dashboard

![Screenshot (169)](https://user-images.githubusercontent.com/75041273/133863380-9cc00ab3-0adf-42e1-8ab7-b51469ce399d.png)
