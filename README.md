# Power_BI_Project_1

Step 1: Data Prep

Imported data from Excel workbook.
Transformed data by promoting the first row as headers for all tables.
Unpivoted Actual and Target tables.
Renamed attributes to "Month" and values to "Sales".
Changed the data type of the month.
Added year, month, and month name columns to the calendar table.

Step 2: Data Modeling

Connected the tables.
Recognized Actual and Target tables as separate Fact tables.
Connected Calendar[Date] to Targets[Month] and Actual[Month].

Step 3: DAX Calculations

Calculated crucial KPIs including Total sales - actual, Total sales - target, Variance, and Variance %.
Calculated additional KPIs such as YTD Sales Actual, YTD Sales Target, YTD Variance, YTD Variance %, and Target reached - Month Count.

Step 4: Dashboard Creation

Created a theme for the dashboard.
Added Card visualizations for key KPIs.
Implemented Reference Label feature to provide context to KPI cards.
Enhanced variance labels with emojis using DAX measures.
Created a monthly trend chart displaying Total Sales Actual, Total Sales Target, and Variance %.
Generated a Salesperson performance Table showing name, Actual performance, target performance, and variance.
