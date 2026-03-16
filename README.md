# Data-cleaning.

# Overview

Cleaning the country column in the store_income_data_task.csv to ensure only three standardised values remained. 
This included:
- Converting tect to lowrcase
- Removing trailing whitespace
- Using fuzzy string matching to identify those close variations
- Replacing inconsistent entries with standardised country names
- Dropping invalid or empty values

# Implementation
The following libraries were used:
- pandas for data manipulation
- numpy for handling missing values
- fuzzywuzzy (and thefuzz) for approximate string matching
- chardet for encoding detection

# Outcome
After cleaning, the dataset's country column contains three consistent values:
- United States
- South Africa
- United Kingdom
This ensures accurate grouping and reliable analysis of store income data acroess these regions.
