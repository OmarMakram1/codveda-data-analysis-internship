# Task 1 - Predictive Modeling / Classification | Level 3

## Overview

Building and evaluating classification models to predict categorical outcomes, specifically customer churn. Multiple models are trained and compared to find the best performer, followed by hyperparameter tuning.

## Objectives

- Preprocess the data (encode categorical variables, apply feature scaling)
- Train and test Decision Tree, Logistic Regression, and Random Forest models
- Evaluate each model using accuracy, precision, recall, and F1-score
- Perform hyperparameter tuning using Grid Search

## Tools & Libraries

- Python
- pandas
- scikit-learn
- matplotlib

## Project Structure

```
├── notebook.ipynb
├── dataset.csv
└── README.md
```

## Notes

`GridSearchCV` is used with cross-validation for tuning. Models are compared using classification reports and confusion matrices to give a full picture beyond just accuracy.
