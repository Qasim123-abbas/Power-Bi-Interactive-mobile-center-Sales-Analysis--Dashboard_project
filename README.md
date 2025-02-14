**Mobile Sales Analysis_Report**

**Interactive Sales Analysis Dashboard in Power BI**

This project showcases an interactive dashboard built in Power BI, designed for analysing sales data to identify trends, measure performance, and provide actionable insights.
Mobile Sales Analysis Dashboard

**Project Overview**
This project showcases an interactive Power BI dashboard designed to provide comprehensive insights into mobile sales data. The dashboard helps users identify trends, track sales performance, and derive actionable insights to support business decisions.

##**Table of the Contents**

•	ETL Process

•	Key Features

•	Technologies Used

•	DAX Measures

•	Dashboard Pages 


**ETL Process**

1. Data Import: Imported raw sales data from an Excel file.
2. Data Cleaning and Transformation:
3. Merged and split columns.
4. Removed unnecessary rows and replaced specific values.
5. Changed data types for consistency and analysis readiness.
6. Data Modelling:
7. Established one-to-many and many-to-one relationships to ensure accurate data connections.
   
**Key Features**

1.**Visuals Created**:

(a)Column, bar, line, area, funnel, and map charts.

(b)Table and pie charts for detailed breakdowns.

2.**Filters and Interactions**:

(a)Used drop-down slicers to filter data by mobile brand, model, payment method, and month.

(b)Configured visual interactions using the Edit Interaction tool.

3.**User Experience Enhancements:**

(a) Added cards displaying key metrics: total sales, total quantity, transactions, and average price.

(b)  Incorporated a page navigator for seamless navigation between dashboard pages.

4.**Technologies Used**

(a)Power BI Desktop

(b)	Power Query

5.**DAX/DAX MEASURES** 

Developed custom measures to enhance the analysis, including:->

•	SUM(): Aggregate total sales from the online store.

•	SUMX(): Iterate and sum over a table to calculate sales performance.

•	COUNTROWS(): Count the number of transactions in the sales data.

•	AVERAGE(): Calculate the average order value.

•	TOTALMTD(): Calculate the month-to-date total sales.

•	SAMEPERIODLASTYEAR(): Compare current sales metrics with the same period in the previous year.

•	CALCULATE(): Apply filters to modify the context of calculations for deeper insights.

•	Created a custom calendar table for time-based analysis of sales trends.

**Dashboard Pages**

**1. Dashboard**

•	**Filters:** Mobile brand, mobile model, payment method, month.

•	**Visuals:**

o	Cards showing total sales, total quantity, transactions, and average price.

o	Map: Total sales by city.

o	Line chart: Total quantity by month.

o	Funnel chart: Customer ratings.

o	Pie chart: Transactions by payment method.

o	Bar chart: Top 3 total sales by mobile model.

o	Area chart: Total sales by day name.

o	Table chart: Brand, total sales, and transactions.

**2. MTD Report**

•	**Filters:** Same as the main dashboard.

•	**Visuals**:

o	Line chart: Month-to-date (MTD) sales analysis by year, quarter, month, and day.

o	Cards: Same metrics as the main dashboard.

**3. Same Period Last Year**

•	**Filter**s: Same as the main dashboard.

•	**Visuals:**

o	Cards showing total sales, total quantity, transactions, and average price.

o	Table chart: Year, quarter, total sales, and same period last year.

o	Column charts: Sales by year, month, and quarter for comparison with the previous year.
