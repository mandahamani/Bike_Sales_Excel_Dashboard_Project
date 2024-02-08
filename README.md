# Bike_Sales_Excel_Dashboard_Project
This is an Excel Project which shows the data original data, the cleaned data, the pivot tables and the final dashboard.

# Overview
The data cleaning consisted of using Find and Replace to change the format for the 'Gender' column. The currency was also changed for the 'Income' column to reflect the GBP symbol and I also decreased the decimal points so that there are only two digits shown after the decimal points. A formula had to be created to change the statuses in the 'Age Bracket' column. The formula used is shown below:

=IF(L2>54, "Old", IF(L2>=31,"Middle Aged", IF(L2<31,"Adolescent", "Invalid"))) 

The final dashboard was created using line charts and bar charts to show insights about bike sale purchases. The dashboard shows the commute distance between customers who purchased a bike vs customers who did not purchase a bike, it also shows the average income for different customers based on their gender and finally it shows which customers purchased bikes vs those who did not purchase bikes based on their age brackets.
