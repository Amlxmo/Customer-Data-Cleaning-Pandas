# Customer Data Cleaning with Pandas

Data cleaning project using Python and pandas to transform messy customer data into a clean, analysis-ready dataset.

## Project Overview

This project focuses on cleaning and preparing a messy customer dataset for analysis. The dataset contained inconsistent formatting, missing values, invalid values, mixed date formats, and duplicate records.

The goal was to identify data quality issues, clean the data using pandas, and validate the final dataset without making assumptions about missing information.

## Data Cleaning Process

The following steps were performed:

1. **Initial data inspection**
   - Examined the dataset structure, columns, data types, and unique values.

2. **Country standardization**
   - Standardized inconsistent country names, capitalization, and whitespace.

3. **City standardization**
   - Cleaned inconsistent city names and formatting.

4. **Signup date cleaning**
   - Converted mixed date formats into a consistent datetime format.
   - Invalid dates were converted to missing values.

5. **Annual spend cleaning**
   - Removed currency text and formatting.
   - Converted values to numeric.
   - Handled invalid negative values.

6. **Age cleaning**
   - Converted age to an appropriate integer data type.
   - Identified and handled invalid age values.

7. **Order cleaning**
   - Checked order values and handled invalid negative values.

8. **Email standardization**
   - Standardized email formatting.

9. **Customer segment standardization**
   - Standardized inconsistent customer segment categories.

10. **Duplicate handling**
    - Identified duplicate records.
    - Investigated duplicate customer IDs.
    - Removed confirmed duplicate rows.

11. **Missing value review**
    - Reviewed missing values and retained them when the correct value could not be reliably determined.

12. **Final validation**
    - Rechecked data types, missing values, duplicates, and cleaned categorical values.

## Tools

- Python
- pandas
- Jupyter Notebook
- VS Code

## Key Takeaway

This project demonstrates a practical data cleaning workflow where data quality issues are investigated before changes are made. Missing or invalid information was not automatically replaced when the correct value could not be reliably determined.

The final dataset is cleaner, more consistent, and ready for further analysis.
