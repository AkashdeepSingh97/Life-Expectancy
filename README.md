# Life-Expectancy
Predicts country-wise life expectancy using WHO and UN data (2000–2015) with Random Forest regression. Includes data preprocessing, cross-validation, and model interpretability to identify key health, economic, and social factors impacting lifespan.
Overview
This project predicts life expectancy for 193 countries (2000–2015) using health, economic, social, and immunization data from WHO and United Nations. It employs Random Forest regression with cross-validation for robust accuracy, identifying key factors affecting lifespan globally.

Dataset
Source: WHO Global Health Observatory and United Nations economic data

Includes 2938 rows, 22 columns (predictors + target)

Key features: Immunization rates, mortality rates, GDP, schooling, lifestyle factors

Features
Data cleaning and missing value imputation

Feature engineering (e.g., GDP per capita)

Random Forest and Linear Regression models

GroupKFold cross-validation by country to evaluate generalization

Model interpretability with feature importance analysis

Usage
Clone the repo

Install dependencies (e.g., scikit-learn, pandas, numpy, matplotlib, seaborn)

Run preprocessing.ipynb or preprocessing.py to prepare the data

Run modeling.ipynb or modeling.py to train and evaluate models

View results and plots in notebooks or generated files

Results
Random Forest achieves mean R² ~0.90, MAE ~2 years, RMSE ~2.9 years

Important predictors include HIV/AIDS prevalence, income composition, schooling

Model insights help guide public health policy decisions

