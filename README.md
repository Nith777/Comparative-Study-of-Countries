# Comparative-Study-of-Countries
The task is to compare various parameters such as income, life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio of different countries using the sample insurance dataset and world development indicators dataset.
Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

Datasets:

Primary Dataset – Insurance Sample Dataset

Secondary Dataset – Global Financial Development Database

Note: Use Data Blending with Relationships between Country Code, Country, and Year

Steps to Perform: 

Create a geographic map showing the countries' fields. Color the map based on the income column from the secondary dataset

Include income group filter in the dashboard

Include a webpage to show data from the world bank webpage driven by an URL action from a geography graph

The country names in the map will act as the trigger

https://en.wikipedia.org/wiki/Country
Create a KPI Table to show the comparison between the selected period and the period prior to the selected one
Create two parameters for Year Selection and Category Selection
Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio
Create a calculated field to calculate the Growth %
Create a table to show these values
Title should be updated based on the category selection
Create Growth Indicator Shapes based on the Growth %
Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it
Create a trend line to show the selected category values
The line shows an arrow or triangle at the last mark
Create a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well
Formatting should be done appropriately





Step 1: Open Tableau 
Step 2: On the home page Click Connect then click Microsoft Excel. 
Step 3: Connect to the Global Financial Development Database - Jul2018 Excel file. 
Step 4: Drag and drop Data July 2018 tables to the canvas area. 
Step 5: Then Connect Insurance Sample Dataset Excel file. 
Step 6: Go to sheet 1 rename as MAP add country to detail income to colour and country code to text, Change automatic to map.
Step 7 : Create Sheet 2 Rename as KPI. Create two parameters SELECT CATEGORY AND SELECT.
Step 8:Create calculated field Select category cf, category cy(Current year) , category py(Previous year) and growth.
Drag Measure Names to Row and filter it to Category CY , Category PY , Growth. And Measure Values to Text Mark card.
Create calculated field growth indicator. Click on show parameter option.
Step 9: click and drag select category calculated field to rows and years to columns. Also add years to pages . Select the show history and trails.
STEP:10    Go to dashboard click and drag map, KPI, Trendline , Growth Indicator.On format select actions add Hyperlink and Filter.
