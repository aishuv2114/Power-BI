# Sample PowerBI Report using AdventureWorks Dataset.

I created this dashboard as part of the bootcamp by Maven Analytics. This report analyzes data of a fictional company called AdventureWorks Cycles that has multiple products such as Cycles, Jerseys, Caps, Bottles etc. 


## Power Query

Using Power Query,
- Imported Excel Data Sources using the GetData Feature. 
- Cleansed Data using various features such as String Functions(Lowercase, Uppercase, Capitalize each Word, Trim, Clean, Add Prefix, Add Suffix), Date Functions, Grouping and Aggregating Data, Pivoting,Merging and Appending on the Transform tab to modify an existing column and Add Column Tab to add a new column.

## Data View Tab

- Created relationships between the source tables to build a snowflake schema.
- Defined active and inactive relationships and also ensured that the relationship cardinality is one to many 
- Also, ensured that there is a shared lookup between the two data tables to be able to represent data from both the fact tables in a single view
- Hid the fields that aren't required in the report view

![Screenshot_2](https://user-images.githubusercontent.com/113862057/193489876-88575192-bc23-4ab5-a6bc-3a2728078710.png)

## DAX

- Created Calculated Columns and Calculated Measures
- Created Explicit measures to use them in other dependant calculations
- Used complex DAX functions like calculate(),all(),filter(),iterator functions like sumx() and time intelligence functions like dateadd() to calculate Prev Month Revenue/Orders and datesinperiod()   to calculate the Rolling Revenue.

## Report View

- Created various report types such stacked bar charts, trended, gauge, KPI's and doughnut charts.
- Used slicers to increase user interactivity and filters such as Visual Level Filters, Page Level Filters, Report Level Filters and Drill Through Filters 

![Screenshot_3](https://user-images.githubusercontent.com/113862057/193491261-32c92f79-31de-4c4a-8d94-f62963a8d394.png)

![Screenshot_4](https://user-images.githubusercontent.com/113862057/193491292-dd583411-9439-4edb-9423-62137505b3b4.png)

![Screenshot_5](https://user-images.githubusercontent.com/113862057/193491343-45a5ac7a-40ba-4e17-911f-1fd25f6b07ea.png)


