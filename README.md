# Capstone-Project 
# Executing an End-to-End Analytics Process 
## Scenario:

We are assisting a credit analyst who wants to gather, organise and analyse data on credit card transactions and customers in order to identify fraudulent information. We nee to execute an end-to-end analytics process to accomplish this task.

## Tools used:  
To complete this project, we need the following database and software: 
1. Credit_Database.db 
2. capstone workbook.xlsx 
3. Task 5.1 Model Data for Clustering
4. Task 5.2 Model Data for Classification
5. DB Browser (SQLite) 
6. Power Pivot in Microsoft Excel 
7. Power BI
8. Orange 

#### Tasks performed using SQLite
Utilize the 'Credit_Database.db' file to execute a SQL query that determines the total number of customers holding multiple cards. Next, using the same file, perform a SQL query to calculate the average sales per customer segment. Finally, run a SQL query to identify the total number of fraudulent transactions and the corresponding total fraudulent amount.

#### Creating Data Model using Excel Power pivot.
Using 'capstone workbook.xlsx', create a data model in Excel Power Pivot with the four tables and a calendar table. Display the relationships between these tables. Add Cust_ID to the TransactionBase table by referencing it from the CustomerBase table. Create a Pivot table showing the monthly percentage (MoM %) change in sales. Next, create a combo chart displaying sales per month, previous month sales, and %MoM spend. Add slicers for customer segment and customer vintage groups, ensuring the chart and Pivot table records update according to the slicer selections.

#### Create data visualizations using tables, charts, and interactive dashboards in Power BI.
Using 'capstone workbook.xlsx', create a dashboard in Power BI with the following elements:

1. Create 4 Cards:

Total number of cards

Total number of customers

Total number of transactions

Current monthly sales

2. Line Chart: Display average transaction value by month.

3. Bar Chart: Show the average age for each customer vintage group.

4. Matrix/Table: Include rows displaying the quarters, total sales, total number of transactions, total number of fraudulent transactions, percentage of fraudulent transactions, and average transaction value for each quarter.

5. Link Charts: Connect the charts to the customer segment slicer and month dropdown, ensuring the line chart showing average monthly transactions does not change when a month is selected in the dropdown.

#### Apply the clustering and classification technique to classify information  
Using the 'Task 5.1 Model Data for Clustering' file, identify the customer segments by applying the clustering technique in Orange. Using the ‘Task 5.2 Model Data for Classification' file, determine the rules to identify fraudulent transactions.
