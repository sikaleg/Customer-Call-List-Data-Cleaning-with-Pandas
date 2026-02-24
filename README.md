# Customer Call List Data Cleaning with Pandas
## Project Overview

This project demonstrates a complete data-cleaning workflow using Python and Pandas to transform a messy customer call list into an analysis-ready dataset. The raw dataset contained multiple data quality issues such as:
- Inconsistent phone number formats
- Missing values and "N/A" entries
- Non-standardized Yes/No fields
- Combined address column
- Records marked as Do Not Contact
- Blank and invalid phone numbers
The goal of this project was to clean, standardize, and prepare the data for downstream analysis and reporting.

## Data Description
**Raw Data** 
<a href='https://ourworldindata.org/covid-deaths'>Dataset:</a> Contains the original unmodified dataset with data quality issues.
<img width="901" height="454" alt="Screenshot 2026-02-23 171649" src="https://github.com/user-attachments/assets/1f24ef99-b45c-4af0-ba00-243c84220bfb" />

**Cleaned Data**
<a href='https://ourworldindata.org/covid-deaths'>Cleaned Data:</a> Final output after applying all cleaning and transformation steps in Pandas.
<img width="761" height="430" alt="Screenshot 2026-02-23 171836" src="https://github.com/user-attachments/assets/c865b390-65be-4e8b-81cf-e7bef45af404" />

## Data Cleaning Tasks Performed
- Removed duplicate records
- Standardized Yes/No → Y/N for categorical consistency
- Formatted phone numbers into US format: XXX-XXX-XXXX
- Split the address column into:
  - Street Address
  - State
  - ZIP code
- Removed rows where Do_Not_Contact = Y
- Removed rows with missing or invalid phone numbers
- Converted "N/A", "Null", and blank spaces to proper null values
- Replaced null values with blanks where appropriate
- Trimmed leading and trailing spaces
- Reset the DataFrame index after cleaning

## Tools & Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Key Data Quality Improvements
- Removed non-contactable customers
- Standardized categorical fields for consistent analysis
- Ensured all remaining records have valid phone numbers
- Transformed raw data into an analysis-ready format
This significantly improves the dataset’s usability for:
- Customer segmentation
- Call campaign analysis
- CRM reporting
- Business decision-making

## Skills Demonstrated
- Data cleaning and preprocessing with Pandas
- Handling missing and inconsistent data
- Regular expressions for pattern-based transformation
- Data quality validation
- Reproducible data workflows
- GitHub project documentation
## Author

## Author
Godwin Sikale | Data Analyst
