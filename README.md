# Sales-Analytics-using-Power-BI

### Goal: The Goal of this project was to create a sales analytics dashboard for a superstore and analyse it's profit, loss and the area of improvements.

### About the Project: 
The entire project was performed using Microsoft Power BI Desktop. Initial step was to import the data set into Power BI. The data set was in the form of excel workbook (global_superstore_2016). The Data set contains three tables or sheets namely Orders, People and Returns. Each contains many features like Date of Order, Date of Delivery, Country, Customer Names, etc. The following are the steps of my analysis and the corresponding insights that were derived are clearly visible in the screenshot provided below:

1. A custom column named Delivery days was created by subtracting order date from ship date.
2. Cards were made for total sales, total quantity and average delivery days and Return Orders.
3. Year was extracted from the order date and a custom column was created for that. This helped to create the Year slicer.
4. A conditional column was created for the Returns Table and total return orders was calculated by placing a condition. When Yes, then 1, else 0.
5. A Map was created setting location Region and size Sales. This showed the sales by region. From this we can get the regions where it needs to improve and the regions where it is performing well. 
6. A clustered bar chart was created placing product name on the Axis and Profit on values. This chart shows the top 7 products by profit. Similarly, bottom 7 products by profit
was also calculated.
7. A pie chart was created putting sales in the value and legend as Segment. This shows the proportion of total sales by consumer, corporate and home office. 
8. A Donut chart was created putting sales in the value and legend as Markets. This shows the proportion of total sales by markets all over the world.

My suggestions after working on this project would be that the store should focus on increasing its store chain into more other countries as well. The store should try to retain its most profitable customers by providing exciting deals. The products that gave the least amount of profit should be sold at a discounted rate or should be discarded.

### A Glimpse of the Dashboard

![Screenshot (170)](https://user-images.githubusercontent.com/75041273/133881736-e05beddc-75f1-42cf-9f7b-a53566c3295a.png)

### Tech Stack

<img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black"/> 
