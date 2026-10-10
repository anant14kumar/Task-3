# House Price Prediction using Linear Regression

## Overview
This project builds an end-to-end Machine Learning pipeline to predict house prices based on residential features (e.g., Area, Bedrooms, Bathrooms, Year Built, Location). Both standard Ordinary Least Squares (OLS) Linear Regression and Ridge Regularization (L2) were evaluated.

## Key Features & Workflow
1. **Exploratory Data Analysis (EDA):** Inspected data distributions, summary statistics, and missing value checks.
2. **Feature Engineering & Preprocessing:** Handled missing data via median/mode imputation and transformed categorical variables using One-Hot Encoding.
3. **Correlation Analysis:** Generated heatmaps to isolate key drivers influencing sale price.
4. **Model Training:** Built models using an 80/20 train-test split.
5. **Evaluation & Diagnostics:**
   - Evaluated metrics: MSE, RMSE, and $R^2$ Score.
   - Diagnostic analysis via Actual vs. Predicted plots and Residual error distribution plots.
   - Coefficient analysis to highlight highest positive/negative predictors.
6. **Regularization Comparison:** Compared Linear Regression against Ridge Regression.

## Project Structure
```text
House_Price_Prediction/
│── house_data.csv               # Dataset
│── house_price_prediction.ipynb # Complete Jupyter Notebook with code & markdown
│── requirements.txt             # Project dependencies
└── README.md                    # Project documentation