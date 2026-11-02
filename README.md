# Synthetic Retail Sales Dashboard

A Power BI dashboard that analyses retail sales by product, region and month to uncover performance trends.

## Problem
A retail business wants to understand which products and regions drive sales, how revenue changes over time, and where performance can improve.

## Dataset
- Source: Synthetic (generated) retail sales data
- Size: [number of rows and columns]
- Key columns: [e.g., Order Date, Product, Category, Region, Quantity, Sales, Profit]

## Tools Used
Python, Pandas, Numpy, Power BI, DAX, Power Query, CSV data preparation

## What I Did
- Cleaned and prepared the data in Python Using pandas and numpy
- Created DAX measures such as Total Sales, Total Quantity, Average Order Value, [and Month-over-Month Growth]
- Built visuals for monthly sales trend, top products, regional performance and category split
- Added slicers for [date, region, category] for interactive filtering

## Key Findings
- Retained revenue was $1,176.65 across 20 orders, after discounts and excluding returned orders.
- The overall return rate was 15%: 3 of 20 orders were marked returned.
- Home was the top category by retained revenue, contributing $523.55—about 45% of the total. Clothing contributed $347.68, and Electronics $305.42.
- Electronics had the most returned orders: 2 of 7 orders (about 29%). Clothing had 1 of 6 returned (about 17%); Home had none of 7.
- Seattle had the most orders, with 8 of 20 (40%), followed by Portland with 6. Boise and Spokane had 3 each.
- Average shipping time was 3.65 days.

## Screenshots
![Dashboard Overview](images/dashboard-overview-1.png)

## How to View
Download `Synthetic_Retail_Sales_Dashboard.pbix` and open it in Power BI Desktop.

## Author
Gopal Mukherjee