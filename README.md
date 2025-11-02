# Assignment1

# Data

This dataset on evictions in NYC was retrieved from NYC Open Data
the goal was to identify which borough was experiencing the highest number of evictions

I uploaded the raw data into Google Sheets, removed unnecessary columns to clean the dataset. 

Raw data: https://docs.google.com/spreadsheets/d/1uXdsbYcyqiP0fI_g5UlX9rgfcX03J4RNFxzw2QrTzzo/edit?gid=0#gid=0

The final version included only the year of the violation, the borough, and the postal code.
Data: https://docs.google.com/spreadsheets/d/1lB7ZSbulhxDSkYnIYzOn8OA2ushTy1mX9qETC11_P6g/edit?gid=0#gid=0 

# Methodology

This notebook shows how I analyzed the data: http://localhost:8888/notebooks/dataProjects/Analysis1.ipynb?

Next, I analyzed the cleaned data using Pandas in Python. 
I read the CSV file into a DataFrame and used Python to count the number of evictions per borough in order to determine which one had the highest total. 

I also calculated the mode to see if a particular neighborhood was experiencing disproportionately high eviction rates, and whether it was located in the same borough with the overall highest rate.

# Analysis Summary

Here is the analysis of the data: https://docs.google.com/document/d/1PCyoUPWeC4sKBrB-4BYTVAkLMzNbBoH1JbOOYk8d2as/edit?tab=t.0

The data tells the story of the Bronx, a borough in NYC that experiences racial and economic inequities as shown in the high number of evictions. While evictions is only a part of the issues that persist in the Bronx, this data shows how the economic inequities they are experiencing is showing up. 

This data can be used to tell a story about how developers and landlords may betaking advantage of rent payers here. It can also be a story about how housing policy fails residents in New York. The data can also be used to go into more details about zip codes and see if there are developers or landlords who are monoplizing housing in specific areas. 
