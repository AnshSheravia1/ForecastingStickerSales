# Kaggle Sales Prediction Challenge

## Overview
This repository contains my solution for a Kaggle competition focused on predicting multi-year sales for various Kaggle-branded stickers across different fictional stores located in real-world countries. The dataset, while synthetic, mimics real-world sales data patterns, including seasonal trends, weekend and holiday effects.

## Dataset Description
The dataset consists of sales data from multiple stores, with key features representing time-series trends, holidays, and store-specific attributes. The goal was to accurately forecast future sales using machine learning models.

## Approach and Methodology

### 1. **Data Exploration & Visualization**
- Performed exploratory data analysis (EDA) to understand trends, seasonality, and outliers.
- Visualized sales distribution across different stores and time periods.
- Analyzed the impact of holidays and weekends on sales performance.

### 2. **Data Preprocessing**
- Identified and handled missing values, where removing NaN values resulted in the best model performance.
- Feature engineered holiday-related variables to better capture their impact on sales.

### 3. **Model Experimentation**
I experimented with multiple machine learning models to optimize sales predictions:
- **CatBoost**
- **K-Nearest Neighbors (KNN)**
- **Random Forest** (Best performing model)
- **Gradient Boosting**
- **Decision Tree**

Among these, **Random Forest** yielded the best performance in terms of accuracy and generalization.

### 4. **Performance Evaluation**
- Used **Mean Absolute Percentage Error (MAPE)** as the primary evaluation metric.
- Random Forest outperformed other models in minimizing MAPE and effectively capturing sales trends.

## Competition Ranking
I achieved a ranking of **960 out of 2722** participants in the competition, demonstrating a strong predictive capability through effective feature engineering and model selection.

## Another Model
I have also used AutoGluon in another notebook for the same competition which did improve my score from 0.18070 to 0.14281.
