**#Summarized Retail Dashboard - Power BI Project**

Project Overview

**Title: Summarized Retail Dashboard**

**Scope: Retail dashboard visualizing the summary to provide an overall picture of the business's performance.**

Data Sources: Microsoft Excel

Cleaning and Visualization Tools: Power Query and Power BI

**Understanding the Information in the Data Source:**

**Dataset Overview:**

**Three Sheets:**
Dim Tables
Fact Table
Aug Data

**More Insights:**

**Dim Tables:**
Lookup tables used to group sales data.
The financial year in Australia runs from July to June.
Classified dates into financial year, financial quarter, and financial year month.
Contains information about postcodes, suburbs, states, buyers, and managers.

**Fact Table:**
The dataset spans from January 2016 to July 2017.
Importing into Power BI for Transformation and Visualization:
Converted each sheet to tables in Excel.
Loaded tables into Power BI.

**Cleaning and Visualization:**

**Cleaning:**
Ensured correct data types.
Added new columns to the sales table for Total Sales, Cost, and Gross Profit.
Changed data types of new columns to decimal numbers.
Closed and applied changes in Power Query to load into Power BI.


**Visualization:**

**Establishing Relationships in the Data Model:**
Created relationships between sales, managers, and regions tables.
Manually created a relationship between the date table and other tables.
Deselected the relationship between regions and the sales table.

**Fixing the Summarize Icon for Postcode Fields and the Financial Year Month:**
Adjusted summarize settings for postcode and financial year month fields.

**Formatting Gross Profit, Cost, and Sales:**
Formatted columns to currency and removed decimal places.

**Visualizing the Dataset:**

**KPI of Sales Figure Over Time:**
Utilized a KPI visual and displayed figures in millions.

**Sales by State Broken Down by Chain:**
Used a clustered column chart.
Fields: Sales over region, broken down by chain.

**Sales and Gross Margin by Financial Year Quarters:**
Created charts for sales, gross profit, and financial year quarters.
Changed the gross profit to a line visual.
Formatted labels to one decimal place.

**Breakdown of Sales by Chain with a Pie Chart:**
Utilized a pie chart for chain-wise sales breakdown.

**Map View Showing State Performances:**
Used a globe map visualization with state and sales against the state.
Concatenated state and country for specificity.
Created a new column using the power pivot module for a more specific state representation.
Removed the state field and replaced it with the newly created column (state, country).
Note: Higher density of colors indicates higher value.

**Sales and Category by Chain Using a Bar Chart:**
Utilized a bar chart for sales and categories by chain due to long category names.
Sorted by the largest categories and then by sales.

**Visual of Sales and Gross Profit by Category Across Time Using a Bubble Chart:**
Created a bubble chart with a play axis for financial quarters.
Calculated gross profit percentage and formatted it into one decimal place.
The gross profit represents the size of the bubble.
X-axis had the gross profit percentage.

**Slicer for State Filtering:**
I created a slicer to enable the dashboard to be filtered by state.

**POWER BI PROJECT LINK:**

**Summarized Retail Dashboard**

https://app.powerbi.com/view?r=eyJrIjoiZDY4NTQxYTEtZDY2MS00NDhlLWIxNWMtZWI2NDkxYzkzMjYxIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9
