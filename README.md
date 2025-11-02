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
