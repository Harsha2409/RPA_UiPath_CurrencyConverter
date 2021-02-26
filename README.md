# RPA_UiPath_CurrencyConverter
------------------------------------------------
This repo contains the Robotic Process Automation project using UiPath's StudioX Community Cloud for the following scenario:

## Corporate Hierrarchy: Principal Sales Manager > Sales Lead(s) > Sales Branch Head(s)

## Sales Branch Head(s) manages sales of product A in various countries.

## At EOD, Sales Branch Head(s) need to perform the following tasks and mail the report to their Sales Lead(s):
- Calculat Total Slaes in USD
  - Google Currency to USD for each country and write it to Excel
  - Perform VLOOKUP operation for calculations (Quantity*Price*ConversionRate)
  - Perform Pivot BY location (Countries) ON SUM(Sales in USD)
 - Create a seperate Report File
 - Send an email with a summary of sales and the report
 
 
 ### Not difficult, rather tedious job for EOD
 
 ## This was done using UiPath's StudioX. All that needs to be done is hit `Run`
