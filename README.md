# Data-cleaning-task

# Task 1: Data Cleaning and Preprocessing

## 📌 Objective
The objective of this task was to clean and preprocess a raw sales dataset by handling missing values, removing duplicates, fixing inconsistent formats, and converting data types

## 📂 Dataset Used
Sales-Export_2019-2020.csv
## 🛠 Tools Used
- Python
- Pandas
- Jupyter Notebook
- 
## 🔍 Steps Performed

1. Loaded dataset using pandas.
2. Checked dataset structure using df.info() and df.head().
3. Cleaned column names (removed spaces, converted to lowercase).
4. Removed special characters (commas) from numeric columns.
5. Converted numeric columns (order_value_eur, cost) to float type.
6. Converted date column to datetime format.
7. Checked and handled missing values.
8. Removed duplicate records.
9. Verified final data types and structure.
10. Saved cleaned dataset as Cleaned_Sales_Data.csv.
    
## ✅ Final Data Validation

- No missing values.
- No duplicate records.
- Correct data types:
  - order_value_eur → float64
  - cost → float64
  - date → datetime64[ns]
- Column names standardized.
  
## 🎯 Conclusion

The dataset was successfully cleaned and prepared for further analysis.  
It is now structured, consistent, and ready for data analysis or visualization.
