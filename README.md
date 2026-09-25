# SWYNEX-Data-Analysis-
A data cleaning project using Python and Pandas to identify and handle missing values, duplicate records, incorrect data types, and inconsistent values. The cleaned dataset is prepared for further data analysis.
 1. Project Overview
This project focuses on cleaning a raw dataset using Python and Pandas. The goal was to identify and correct data quality issues and prepare the dataset for further analysis.

 2.  Tools Used
 3.   Python, Pandas, NumPy, Jupyter Notebook

 4. Data Quality Issues Identified

The following issues were checked during the cleaning process:

* Missing values (null values)
* Duplicate records
* Incorrect data types
* Inconsistent values
* Invalid values, such as negative ages

 5. Data Cleaning Steps

. Identified missing values using `isnull()` and `sum()`.
. Checked and handled duplicate records using `duplicated()` and `drop_duplicates()`.
. Converted columns to appropriate data types.
. Identified invalid age values and handled them.
. Checked inconsistent values and corrected them where necessary.
. Verified the dataset after cleaning.

 6. Files Included
Relational data set(need to merge)
  Original dataset before cleaning are
    customers.csv
    Orders.csv
    payments.csv
    products.csv
cleaned_dataset.csv — Cleaned dataset after processing.
readme.txt — Project description and summary.
SWYNEX-Python-Internship.ipynb — Jupyter Notebook containing the cleaning code.

 7. Final Result

The dataset was cleaned and prepared for further data analysis. The cleaned CSV file is included in this repository.

 8. Conclusion

This project helped me practice data cleaning using Python and Pandas, including handling missing values, duplicates, incorrect data types, and inconsistent data.
