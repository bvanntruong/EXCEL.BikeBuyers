# Cleaning Bike Buyers Data
First, I upload the csv file to Excel to view, filter, and manipulate our data. 
## Remove Duplicates
The first step in cleaning is to Remove Duplicates. Before doing so, I make sure it also recognizes that my data has headers.

![Removed Duplicates](https://github.com/bvanntruong/EXCEL.BikeBuyers/blob/main/RemovedDuplicates.png)
## Find and Replace
I notice that the Marital Status and Gender Columns both have "M" as their unit of identification. I want the values to be spelled out. 
Under the Martial Status column, the values should be Married or Single. Under the Gender Column, the values should be Male or Female.

![Find and Replace](https://github.com/bvanntruong/EXCEL.BikeBuyers/blob/main/FindandReplace.png)
## Standardize Data
For my preference, I change the number format for the Income Column to Currency without decimals. 

Upon reviewing the age columns, I decide that the data will be more useful to group by age. To do so, I create a new column called "Age Brackets".
I write an IF formula to check the age listed in Column L and categorize it into the new column. 
The values are Old ( *over 54 yrs* ), Middle Age ( *34-53 yrs* ), and Adolescent ( *under 31 yrs* ). 
If the value in the Age Column L does not fit in these parameters, it will compute to "Invalid".

![Standardize Ages](https://github.com/bvanntruong/EXCEL.BikeBuyers/blob/main/Standardize_AgeBrackets.png)

# Pivot Tables and Charts
I create pivot tables and charts to visualize our data. 
I was curious to know if commute distance was relevant to whether a bike was purchased. 
Another point of interest was whether the average income also impacted bike sales. This data was grouped by Gender.
Finally, age brackets were also visualized to see its correlation with bike sales.

![Pivots](https://github.com/bvanntruong/EXCEL.BikeBuyers/blob/main/Pivots.png)

# Dashboard with Slicers
Finally, I created an interactive dashboard in Excel that includes Slicers for Marital Status, Region, and Education. 
These allow all the Pivot Charts to be dynamic and change upon data needs that are not directly a value on the chart.

![Dashboard](https://github.com/bvanntruong/EXCEL.BikeBuyers/blob/main/BikeBuyers%20Dashboard%20Image.png)
