# Task 2 - Time Series Analysis | Level 2

## Overview

Analyzing a time-series dataset to detect trends, seasonality, and recurring patterns. The analysis goes beyond simple plotting by decomposing the series and applying smoothing techniques.

## Objectives

- Plot the time-series data and identify visible patterns
- Decompose the series into trend, seasonality, and residuals
- Apply moving average smoothing and visualize the output

## Tools & Libraries

- Python
- pandas
- matplotlib
- statsmodels

## Project Structure

```
├── notebook.ipynb
├── dataset.csv
└── README.md
```

## Notes

Decomposition is done using `seasonal_decompose()` from statsmodels with an additive model. The datetime index is set before any analysis to ensure proper time-based operations.
