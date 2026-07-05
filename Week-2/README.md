# 🚗 Tesla Deliveries Analysis and Forecasting

This repository contains my Week 2 Machine Learning Foundation assignment completed as part of the Celebal Technologies Internship Program.

## 📌 Project Overview

This project analyzes Tesla deliveries data from 2015 to 2025 using Python and Machine Learning techniques. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, predictive modeling, time series validation, and forecasting to understand delivery patterns and estimate future deliveries.

## 🎯 Objectives

* Explore the Tesla deliveries dataset
* Perform data cleaning and quality checks
* Visualize delivery trends across regions, vehicle types, and time
* Engineer useful time-based features
* Build and evaluate Linear Regression and Random Forest models
* Compare model performance using MAE, RMSE, and R² Score
* Perform an Augmented Dickey-Fuller (ADF) test for stationarity
* Generate forecasted delivery estimates

## 🛠️ Tools and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels

## 📂 Repository Structure

```text
ML-Foundation-Week-2-Tesla-Deliveries-Analysis/
│
├── ML_Foundation_Week_2_Tesla_Deliveries_Analysis.ipynb
├── tesla_deliveries_dataset_2015_2025.csv
└── README.md
```

## 🔄 Workflow Followed

1. Import required libraries
2. Load and inspect the dataset
3. Check missing values and duplicates
4. Perform exploratory data analysis (EDA)
5. Encode categorical variables
6. Create lag and rolling mean features
7. Split the data chronologically into training and testing sets
8. Train a Linear Regression model
9. Apply Time Series Cross-Validation
10. Tune a Random Forest model using GridSearchCV
11. Compare model performance
12. Perform ADF stationarity testing
13. Generate forecast results
14. Present final insights and conclusions

## 📈 Results

### 🚀 Linear Regression

* R² Score: 0.9862

### 🔄 Time Series Cross-Validation

* Mean R² Score: 0.9886

### 🌲 Random Forest

* Hyperparameter tuning performed using GridSearchCV
* Competitive predictive performance achieved

### 📉 Stationarity Test

* ADF Test confirmed the time series is stationary (p-value < 0.05)

## 📚 Key Learning Outcomes

This project helped strengthen my understanding of:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering for time-series data
* Regression model evaluation
* Cross-validation techniques
* Hyperparameter tuning
* Forecasting concepts
* Model comparison and interpretation

## 👨‍💻 Author

Devratan  
PGDM (Business Analytics) 
Lloyd Business School  
Data Scientist, Celebal Technologies

## 📝 Note

This repository has been created for academic submission and learning purposes as part of the Machine Learning Foundation Program at Celebal Technologies.
