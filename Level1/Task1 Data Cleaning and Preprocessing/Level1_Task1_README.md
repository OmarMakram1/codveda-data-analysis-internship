# Task 1 - Data Cleaning and Preprocessing | Level 1

## Overview

Working with a raw CSV dataset that contains missing values, duplicate records, and inconsistent data formats. The goal is to clean and prepare the data so it's ready for any further analysis.

## Objectives

- Load the dataset using pandas
- Identify and handle missing values through imputation or removal
- Remove duplicate rows
- Standardize inconsistent data formats (dates, categorical variables)

## Tools & Libraries

- Python
- pandas

## Project Structure

```
├── notebook.ipynb
├── dataset.csv
└── README.md
```

## Notes

Missing value strategy depends on the column — numerical columns use mean/median imputation while categorical columns use mode or are dropped if the column is too sparse.
