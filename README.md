# Data-Analyst-Internship-Task-1
# Data Cleaning and Preprocessing Summary

The Customer Personality Analysis dataset was cleaned and prepared for further analysis using Python and the Pandas library.

The following data cleaning steps were performed:

1. The dataset was loaded and inspected using `head()`, `shape()`, and `info()`.
2. Missing values were identified using `isnull().sum()`.
3. Missing values in the Income column were handled using the median value.
4. Duplicate records were checked using `duplicated()` and removed using `drop_duplicates()`.
5. Column names were standardized by converting them to lowercase and removing unnecessary spaces.
6. Text values were cleaned by removing extra spaces and standardizing capitalization.
7. The customer registration date column was converted to a consistent datetime format.
8. Data types were checked and corrected where necessary.
9. An Age column was created using the Year_Birth column.
10. Unrealistic age values were identified and removed.
11. Numerical data was checked for potential outliers using the IQR method.
12. The final dataset was validated for missing values, duplicate records, and correct data types.
13. The cleaned dataset was saved as `cleaned_data.csv`.

The final dataset is clean, structured, and ready for data analysis and visualization.
