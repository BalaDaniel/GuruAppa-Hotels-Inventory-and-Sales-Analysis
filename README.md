# This project about Inventory Cost and Sales analysis of GuruAppa Hotels pvt limited for the November month 2023
## Aim of the Project
1. To build the dashboard that total inventory cost category wise and total sales.
2. To find the inventory cost category wise per day and total sales per day for comparison
3. To find the trand of inventory cost and sales throughout the month
4. To find the relationship between total inventory cost category wise per day and total inventory cost

## Source
1. Data of inventory cost category wise and sub category wise per day and total sales per day in the excel.
2. It consists of 918 rows and 96 columns


## Solution
### Data Transformation
1. Inserted the pivot tables for inventory cost per day, where each date as column header. Here in this stage I can't find the top categories in inventory cost.
2. I loaded above table into the power query editor.
3. Unpivot the all columns except the cateogry column. Now my all dates in single column earlier it was as each date column header.
4. Sort the all the data date wise.
5. Closed and loaded the data into the excel.
6. Sales data sheet loded into the power query editor and changed the data type of date column.
7. Inserted the pivot tables for both transformed tables.
8. Opened the power pivot created relationship between invenstory consumption transformed data and and sales keeping date as a primary key from the sales table.
9. Inserted a slicer for date which activates the both tables
10. Calculated total inventory cost, sales and profit from the pivot tables
11. When we click on the specific date on the date slicer inventory cost, sales and profit for the ccliked will be shown.
### Data Visualization
1. Created a three rectangular shapes to display the total inventory cost/month, total sales/month and total profit/month.
2. Formatted with colors according to required colors and sizes.
3. Created another three rectangular shapes to display total inventory cosy/day, total salesday, total profit/day.
4. Inserted the formula in the shapes to diaplay the values.
5. Created one bar chart that display category wise inventory cost and slicer will work as input to diplay day wise categorical inventory cost
6. Created the line chart for the total inventory cost day wise for the month that trend line for the all days and sales line chart as same as inventory cost.
7. Put slicer for to pick specific(1 to 30) of November month.
8. Slicer will act as input to the Invntory cost/day, sales/day, profit/day and inventory cost perday category wise visuals.
  


