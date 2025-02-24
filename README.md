# Food-Delivery-Sales-Dashboard-in-Excel
 Food Delivery Sales Analysis with Dashboard in Excel

![]()

 ## Objective
The goal of this project is to:
✦ **Analyzing sales data and creating visual charts**
✦ **Creating charts and formatting with shadow**
✦ **Formatting and customizing charts and tables in Excel**
✦ **Creating a dashboard in Excel using separate charts**
✦ **Creating and using slicers for dynamic data filtering**
✦ **Connecting and filtering data in Excel charts with slicers.**
✦ **Creating a pie chart to display percentage of total sales**
✦ **Creating a connected dashboard in Excel**
✦ **Calculating highest profit using pivot table.**

## Procedure

1)Insert Tab-> Pivot Tables. Row = Region, Values = Selling price. 
  Create Bar chart.
  
2) For Top 10 customers: Create Pivot table with Row= CustomerID , values= Selling price(Sum). Go to Filter-> Value Filters -> Top 10.
   Sort by values-> largest to smallest. Create Bar chart.
   
4) For Month and Year Wise Sales: Create Pivot Table with Row=Date and Values= Selling Price(sum). Group the Date by Year and Month. 
   Create Scatter Line Chart.
   
6) Delivery Person Region Wise Sales: Create Pivot Table with Row= Delivery Person, Column= Region, Values= Selling Price.
   Create Horizotal Bar Chart.

7) To Create Final Dashboard, Another Sheet-> Remove Gridlines in View Tab
   Create a rectangle shape from Insert Tab. Insert a Word Art 'Sales Dashboard' in it.
   Colour the background using Ctrl+A.
   copy paste charts from Sheet 2.
   
9)  Providing filters to these charts require slicers. Click on chart Insert Slicer from Analyse Tab.
    Select Year, Delivery Person, Region . Now to connect other 3 charts with slicers:
    Click on each slicer, Report Connections -> Click on each sheet. 

10) Create a Pivot Table with Profit Region Wise: Row=Region, Values=Cost Price & Selling Price. 
   Go To Fields,Items&Sets in Analyze .Type Name and Formula= Sp-Cp/Cp. convert into % 
