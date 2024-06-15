Data Cleaning Project README
Overview
This project focuses on data cleaning tasks using SQL scripts to prepare data for analysis or reporting. The main objectives include removing duplicates, standardizing data, handling null values, and correcting data inconsistencies.

Files
data_cleaning.sql: Contains SQL scripts for data cleaning operations.
layoffs_stagging: Original table structure for data staging.
layoffs_stagging2: Updated table structure after data cleaning.

Steps
Duplicate Removal:
Identifies and removes duplicate rows from the staging table.

Staging Table Creation:
Creates a new staging table with the cleaned data.

Standardize Data:
Removes leading and trailing spaces from the company column.
Standardizes the industry column by updating values.
Standardizes the country column by removing trailing periods.

Convert Date Format:
Converts the date column from string format to date format.

Handle Null Values:
Updates null values in the industry column.
Deletes rows with null values in total_laid_off and percentage_laid_off.

Data Correction:
Corrects missing industry values based on other non-null values for the same company.

Clean-up:
Removes unnecessary columns from the final cleaned table.

Usage
Run the SQL script data_cleaning.sql in your SQL environment.
Verify the changes and data cleanliness in the layoffs_stagging2 table.


Notes
Ensure backup copies of the original data are available before running the script.
Review and customize the script as per specific data cleaning requirements.
