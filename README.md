# CarCast 🚗

A machine learning project that predicts the fair market price of a used car
based on features like brand, model, year, mileage, transmission, fuel type,
and ownership history. The goal is to help buyers and sellers estimate a
realistic price and avoid over/underpaying in the resale market.

## Objective
Build a regression model that accurately predicts used car prices, reinforcing
key machine learning concepts: data cleaning, feature engineering, model
evaluation, and interpretation.

## Project Structure
```
CarCast-/
├── data/
│   └── used_cars_dataset.csv    # Raw dataset
├── notebooks/
│   └── capstone_notebook.ipynb  # Main analysis & modeling notebook
├── README.md
└── requirements.txt
```

## Dataset
The dataset contains listings of used cars with the following features:
Brand, model, Year, Age, kmDriven, Transmission, Owner, FuelType, PostedDate,
AdditionInfo, and the target variable AskPrice.

## Approach
1. **Data Cleaning** – Handle missing values, fix inconsistent formatting
   (e.g. price and mileage stored as text), extract missing brand/model info
2. **Feature Engineering** – Encode categorical variables, create new relevant features
3. **Modeling** – Train baseline and improved regression models, evaluate with RMSE/R²
4. **Tuning** – Hyperparameter optimization via GridSearchCV
5. **Analysis** – Error analysis, over/underfitting checks, key insights

## Tools
Python, pandas, numpy, matplotlib, seaborn, scikit-learn

## Author
Anga Nonqane
