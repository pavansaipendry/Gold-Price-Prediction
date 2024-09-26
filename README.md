# Gold Price Prediction using Random Forest

This repository contains a project that uses **Random Forest Regression** to predict the price of gold based on several market factors. The dataset includes various commodity prices and features related to gold prices, and the model is trained to predict the future prices of gold using historical data.

## Introduction

The objective of this project is to predict gold prices using various market-related features. A Random Forest Regressor is trained on the dataset to achieve accurate predictions. The model can be used to help analysts and investors in the financial sector by providing data-driven predictions of gold prices.

## Dataset

The dataset used for this project is the [Gold Price Data] containing historical data of gold prices and various other factors that might influence the price of gold.

**Note**: The dataset should be loaded as `gld_price_data.csv`.

## Project Workflow

1. **Data Loading**: Load the dataset using Pandas.
2. **Data Preprocessing**: Remove unnecessary columns (e.g., 'Date'), standardize the features using `StandardScaler`.
3. **Correlation Analysis**: Analyze the correlations between different features and the target variable (GLD price).
4. **Model Training**: Train a Random Forest Regressor model on the preprocessed data.
5. **Evaluation**: Evaluate the model using metrics such as R-squared (R²) and visualize the actual vs. predicted prices.
6. **Prediction System**: Implement a function to predict gold prices using new input data.


