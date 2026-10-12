# Titanic Dataset Cleaning Project

## Objective
To identify and clean missing values, duplicate records, incorrect data types, and inconsistent values in a public dataset.

## Dataset
Titanic passenger dataset from the Seaborn public data repository.

## Tools Used
- Python
- Pandas
- Google Colab

## Data Cleaning Steps
1. Identified missing values.
2. Filled missing age values using the median.
3. Filled missing embarked and embark_town values using the mode.
4. Replaced missing deck values with "Unknown".
5. Removed 110 exact duplicate rows.
6. Standardized data types.
7. Checked text values for extra spaces and inconsistencies.
8. Validated the cleaned dataset.

## Final Results
- Original rows: 891
- Final rows: 781
- Columns: 15
- Missing values remaining: 0
- Duplicate records remaining: 0

## Files Included
- `Titanic_Data_Cleaning.ipynb` — Notebook containing Python code and outputs.
- `titanic_cleaned.csv` — Cleaned dataset.
- `README.md` — Project documentation.

## Conclusion
The dataset was cleaned and validated using Python and Pandas. The cleaned CSV file is ready for further analysis.
