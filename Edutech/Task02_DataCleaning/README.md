# Task 2: Data Cleaning & Preprocessing

## Objective
Perform data cleaning and preprocessing on the Titanic dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Tasks Performed
- Loaded the Titanic dataset
- Identified missing values
- Filled Age missing values using Median
- Filled Embarked missing values using Mode
- Removed Cabin column due to excessive missing values
- Checked and verified duplicate records
- Converted categorical variables to category data type
- Detected and handled outliers using the IQR method
- Normalized Age and Fare using MinMaxScaler
- Exported the cleaned dataset

## Dataset Information
- Original Rows: 891
- Original Columns: 12
- Missing Values:
  - Age: 177
  - Cabin: 687
  - Embarked: 2

## Deliverables
- task2.ipynb
- titanic.csv
- titanic_cleaned.csv

## Outcome
Successfully cleaned and preprocessed the Titanic dataset, improving data quality and preparing it for further analysis and machine learning applications.