# Comparative-Study-of-Countries
The task is to compare various parameters such as income, life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio of different countries using the sample insurance dataset and world development indicators dataset.
Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.





Step 1: Open Tableau 
Step 2: On the home page Click Connect then click Microsoft Excel. 
Step 3: Connect to the Global Financial Development Database - Jul2018 Excel file. 
Step 4: Drag and drop Data July 2018 tables to the canvas area. 
Step 5: Then Connect Insurance Sample Dataset Excel file. 
Step 6: Go to sheet 1 rename as MAP add country to detail income to colour and country code to text, Change automatic to map.
Step 7 : Create Sheet 2 Rename as KPI. Create two parameters SELECT CATEGORY AND SELECT.
Step 8:Create calculated field Select category cf, category cy(Current year) , category py(Previous year) and growth.
Drag Measure Names to Row and filter it to Category CY , Category PY , Growth. And Measure Values to Text Mark card.
Create calculated field growth indicator. Click on show parameter option![image](https://github.com/Nith777/Comparative-Study-of-Countries/assets/114760849/d173594b-2b73-41b2-8e46-e8d50aa11124)
Step 9: click and drag select category calculated field to rows and years to columns. Also add years to pages . Select the show history and trails.
STEP:10    Go to dashboard click and drag map, KPI, Trendline , Growth Indicator.On format select actions add Hyperlink and Filter.
