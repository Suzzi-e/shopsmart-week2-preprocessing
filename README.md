# ShopSmart Retail — Week 2: Data Preprocessing & Feature Engineering

## Project Overview

This project focuses on preparing the ShopSmart Retail dataset for machine learning. It builds on the Week 1 project by examining data quality, engineering useful features, encoding categorical variables, scaling numerical features, detecting outliers, and reviewing potential predictors.

The dataset contains 50,000 records covering orders, customers, products, stores, transaction amounts, and return status.

## Business Objectives

The project supports two planned machine learning tasks:

- **Regression:** Predict `Order_Total`.
- **Classification:** Predict `Return_Flag`.

## Project Contents

- `Week2_Preprocessing.ipynb` — Jupyter notebook documenting data inspection, preprocessing, feature engineering, analysis, and visualisations.
- `shopsmart_processed.csv` — Processed dataset saved for further analysis and model development.
- `Business Understanding Report.pdf` — Business objectives, analytical findings, and potential business implications.
- `Data Preprocessing Report.pdf` — Data quality checks, preprocessing decisions, feature engineering, encoding, scaling, outlier analysis, and feature selection.

## Key Findings

- The dataset contains 50,000 records.
- Beauty has the highest record count among the five product categories.
- `Line_Total` and `Order_Total` have an almost perfect positive correlation.
- Home has the highest observed record-level return rate (5.13%), while Groceries has the lowest (4.58%).
- The processed dataset contains 41 columns and retains missing values in `Customer_Tenure_Clean` for further investigation.

## Important Preprocessing Notes

- Date columns were converted to datetime format.
- Date-based and customer-tenure features were engineered.
- A constant `Sub_Category` feature and the constant `Order_Year` feature were removed from the relevant working/final dataset.
- One-hot encoding and numerical scaling were demonstrated separately from the final saved dataset.
- Model-specific feature selection and training-only preprocessing are still required before model training.

## Related Project

See the [ShopSmart Retail Week 1 repository](https://github.com/Suzzi-e/shopsmart-machine-learning) for the earlier project work.

## Status

Week 2 preprocessing and reporting deliverables have been prepared. Model training and evaluation are separate subsequent steps.