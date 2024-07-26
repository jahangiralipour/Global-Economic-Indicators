# Global-Economic-Indicators
This repository contains a Power BI report that analyzes global economic indicators using yearly data from the World Bank. The report leverages data on population and economic output of various countries worldwide, providing insights through interactive visualizations and detailed analysis.

Data Sources
API Source: World Bank API
https://api.worldbank.org/v2/country/all

https://api.worldbank.org/v2/sources/2/series/NY.GDP.MKTP.KD/metadata

https://api.worldbank.org/v2/sources/2/series/SP.POP.TOTL/metadata

CSV Source: World Bank datasets available on their website
URL: https://data.worldbank.org/
Data Transformation Process
The data from the World Bank API and CSV files were parsed and transformed using Power Query in Power BI. Several tables were merged to create a comprehensive dataset. The transformation process involved:

Parsing and Cleaning: Initial raw data was cleaned to remove inconsistencies and irrelevant information.
Merging Tables: Relevant tables were merged to create a unified dataset.
Calculations and Measures: Using DAX (Data Analysis Expressions), necessary measures such as GDP annual growth rate and GDP per capita were defined.
Features
Global Overview: The main dashboard provides a global overview of key economic indicators.
Country-Specific Analysis: A drill-through page allows users to select a specific country and view detailed economic data for that country.
Interactive Visualizations: Various interactive charts and graphs help users understand trends and patterns in the data.
Key Measures and Calculations
GDP Annual Growth Rate: Calculated as the year-over-year percentage change in GDP.
GDP per Capita: Calculated as the GDP of a country divided by its population.
Screenshots
Main Dashboard

Country-Specific Drill-Through Page

How to Use
Download the Power BI report file (worldbank.pbix) from this repository.
Open the file in Power BI Desktop.
Interact with the dashboard to explore the data. Use the drill-through functionality to get detailed information about specific countries.
