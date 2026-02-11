# Airbnb-Texas-Price-Prediction
End-to-end data science project analyzing Airbnb listings in Texas and building machine learning models to predict nightly prices using Python, EDA, feature engineering, and XGBoost.


## 🏡 Airbnb Texas Price Prediction
### 📌 Project Overview

This project analyzes Airbnb listings in Texas to understand pricing drivers and build machine learning models to predict nightly rental prices. The goal is to provide insights for hosts on optimal pricing strategies and identify the most influential listing attributes.

### 🎯 Objectives

Explore Airbnb listing characteristics

Identify key factors influencing price

Build predictive models

Compare baseline vs advanced models

### 📊 Datasets Used

Listings

Calendar availability

Reviews

Neighborhood metadata

All datasets were cleaned and stored as Parquet files for efficient processing.

### 🧹 Data Cleaning Summary

Converted dates to datetime

Cleaned price fields and removed extreme outliers

Filled missing numerical values using medians

Encoded categorical variables

Capped unrealistic minimum and maximum nights

Removed columns with 100% missing values

### 📈 Exploratory Data Analysis

Key analyses include:

Price distribution

Price by room type

Correlation heatmap

Availability vs price

Reviews vs price

Example:

### 🤖 Modeling Approach

Baseline Model

Linear Regression
R² ≈ 0.24

Advanced Model

XGBoost Regressor
R² ≈ 0.61

XGBoost significantly improved performance.

### 🔍 Top Predictive Features (XGBoost)

Room Type (Private room, Hotel room, Shared room)

Minimum nights

Reviews per month

Host listing count

Latitude & Longitude

Availability_365

### 💡 Key Insights

Room type is the strongest driver of price

Listings requiring longer minimum stays tend to be more expensive

More active listings (higher reviews per month) charge higher prices

Location strongly influences price

### 📌 Business Recommendations

Hosts should optimize minimum night policies

Invest in amenities and guest experience

Price strategically based on room type

Adjust pricing by neighborhood

### 🛠 Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

### ▶ How to Run
pip install -r requirements.txt
jupyter notebook notebooks/airbnb-texas.ipynb

### 📌 Author

Reena Pinto
Aspiring Data Scientist
