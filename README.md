# Laptop Price Prediction Project

## Overview

This project aims to predict laptop prices based on various features such as hardware specifications, brand, operating system, and more. By leveraging machine learning techniques, we developed models that can estimate laptop prices with reasonable accuracy. The dataset used for this project is `laptop_data.csv`.

## Dataset

The dataset contains comprehensive information about various laptops, including:

- Company
- Product Type
- RAM
- Weight
- Screen Resolution
- CPU
- GPU
- Operating System
- Price

The dataset has been preprocessed and cleaned to ensure quality and consistency in the training process.

## Steps Taken

### Data Preprocessing

- **Data Cleaning:** Removed unnecessary columns (`Unnamed: 0`).
- **Data Transformation:** Converted RAM and Weight columns to appropriate data types.
- **Feature Engineering:** Extracted useful features from existing columns (e.g., Touchscreen, IPS, etc.).
- **Data Formatting:** Resolved inconsistencies and formatted data for analysis.

### Exploratory Data Analysis (EDA)

- Explored relationships between features and the target variable (Price).
- Visualized distributions, correlations, and trends in the data.
- Utilized libraries such as Pandas, Matplotlib, and Seaborn for analysis and visualization.

### Model Building

We employed a supervised learning approach, specifically regression techniques, to train our models. The dataset was split into training and testing sets, and we experimented with different algorithms to determine the most suitable model for our task:

- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **KNN**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**
- **ExtraTrees**
- **AdaBoost**
- **Gradient Boost**
- **XGBoost**
- **Stacking Regressor**
- **Voting Regressor**

### Evaluation Metrics

To assess the performance of our models, we utilized metrics such as:

- **Mean Absolute Error (MAE)**
- **R-squared (R2) Score**

These metrics provide insights into how well our model generalizes to unseen data and its ability to accurately predict laptop prices.

## Conclusion

Through this project, we developed machine learning models that predict laptop prices with reasonable accuracy. The best-performing model can be used for real-world applications such as pricing optimization, market analysis, and budget planning.
