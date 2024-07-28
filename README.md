# Feature Engineering on Hotel Booking Cancellation

## Overview
This project aims to predict hotel booking cancellations by utilizing machine learning techniques on a dataset containing hotel booking information. By conducting exploratory data analysis (EDA) and performing feature engineering, we aim to preprocess the data for modeling and evaluate different machine learning algorithms to create an accurate predictive model.

## Problem Statement
The task is to predict whether a hotel booking is likely to be canceled or not. To achieve this, we need to preprocess the data, including handling missing values, transforming categorical and numerical features, and scaling the data. Subsequently, we will evaluate various machine learning models to select the most suitable one for predicting booking cancellations effectively.

## Activities Completed
1. **Exploratory Data Analysis (EDA)**
   - Conducted data quality checks.
   - Treated missing values.
   - Analyzed categorical data.
   - Analyzed numerical data.

2. **Data Transformation**
   - Transformed categorical data using techniques such as One-Hot Encoder, Label Encoder, and Ordinal Encoder to convert categorical variables into a format suitable for machine learning algorithms.
   - Transformed numerical data using the Power transform to handle skewness and ensure a more normal distribution of features.

3. **Data Scaling**
   - Scaled the data to ensure that all features have the same scale, which is crucial for many machine learning algorithms to perform effectively.

## Next Steps
With the data preprocessed and transformed, the next steps involve:
- Splitting the data into training and testing sets.
- Selecting appropriate machine learning algorithms for model evaluation.
- Evaluating the performance of each model using appropriate metrics such as accuracy, precision, recall, and F1-score.
- Fine-tuning the hyperparameters of the selected model(s) using techniques such as grid search or random search.
- Selecting the final model based on evaluation results and deploying it for predicting hotel booking cancellations.


## Dataset
The dataset used in this project can be found `hotel.csv`.

## Notebook
The Jupyter notebook containing the code for this project can be found `Hotel Booking Feature Eng`.
