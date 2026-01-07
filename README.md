# Predictions-of-House-Prices-in-Ames-Lowa.
This dataset, originally published as part of a public data science competition on a leading machine learning platform, contains detailed records of residential homes in Ames, Iowa. It includes 79 explanatory variables describing various aspects of the properties, such as location, size, etc, along with the target variable sale price.

Project Overview

This project is an end-to-end machine learning regression pipeline built to predict residential house prices using the Ames Housing Dataset. The dataset contains 79 explanatory features describing different aspects of houses such as location, size, quality, and condition.

The goal of this project is to:

Build and evaluate predictive regression models

Handle real-world data challenges (missing values, categorical features, skewed target)

Compare baseline and advanced models

Visualize model performance using Power BI

Dataset Description

Source: Ames Housing / Kaggle – House Prices: Advanced Regression Techniques
Observations: ~1,460 houses
Features: 79 explanatory variables
Target Variable: SalePrice

Feature Categories

Property size: Lot area, living area, basement size

Quality & condition: Overall quality, overall condition

Location: Neighborhood, zoning classification

Structure: Year built, roof type, exterior material

Amenities: Garage, basement, fireplace

Data Cleaning & Preprocessing

Real-world housing data contains significant missing values and mixed data types. The following steps were applied:

Missing Value Analysis

Columns with more than 40% missing values were dropped to avoid noise and bias

Remaining missing values were handled as follows:

Numerical features: Median imputation

Categorical features: "None" imputation 

Feature Engineering

Dropped non-informative identifier column (Id)

Applied log transformation to SalePrice to reduce skewness

Converted categorical variables using One-Hot Encoding

Ensured column alignment between training and test datasets

Train–Validation Split

Training data split into:

80% training set

20% validation set

Used validation set for unbiased performance evaluation

Models Implemented
Baseline Model: Linear Regression

Used as a benchmark model

Helps understand linear relationships in the data

Advanced Model: Random Forest Regressor

Captures non-linear relationships

Handles feature interactions effectively

Achieved superior performance compared to Linear Regression

Model Evaluation

The models were evaluated using standard regression metrics:

R² Score – proportion of variance explained

RMSE (Root Mean Squared Error) – average prediction error magnitude

Best Model Performance

Random Forest Regressor

R² ≈ 0.88 (88%)

This indicates that the model explains approximately 88% of the variance in house prices, which is a strong result for a real-world dataset.

Visualization (Power BI)

Model outputs were exported and visualized using Power BI to improve interpretability and stakeholder communication.

Key Visuals

Actual vs Predicted Price Scatter Plot

Note: GitHub does not render .pbix files. The Power BI dashboard is provided as a downloadable file.
