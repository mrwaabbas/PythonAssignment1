# Assignment1

# Data
This dataset on evictions in NYC was retrieved from NYC Open Data. I wanted to identify which borough was experiencing the highest eviction rates. 

# Methodology
I copied the raw data into Google Sheets and removed unnecessary columns to clean the dataset. The final version included only the year of the violation, the borough, and the postal code.

# Output
Next, I analyzed the cleaned data using Pandas in Python. I read the CSV file into a DataFrame and used Python to count the number of evictions per borough in order to determine which one had the highest total. I also calculated the mode to see if a particular neighborhood was experiencing disproportionately high eviction rates, and whether it was located in the same borough with the overall highest rate.
