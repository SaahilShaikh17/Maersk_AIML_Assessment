# Sourcing Cost Forecasting

## Overview

This project aims to forecast the sourcing cost for a company's products using time series analysis and machine learning techniques. The dataset contains historical information about sourcing costs, product types, manufacturers, sourcing channels, geographical locations, and temporal trends. The goal is to develop accurate forecasting models to optimize sourcing strategies and minimize costs.

## Dataset

The dataset consists of the following columns:

- Date: The date of sourcing.
- Sourcing Cost: The cost incurred for sourcing the product.
- Product Type: Categorical variable indicating the state of the product (Powder/Liquid)
- Manufacturer: Categorical variable specifying the manufacturer of the product.
- Sourcing Channel: Categorical variable representing the channel through which the product was sourced.
- Area Code: Numerical variable identifying the geographical area of sourcing.
- ProductType: Categorical variable indicating the type of the product
- Month of Sourcing: Categorical variable indicating the month in which the sourcing of the product happened.

## Problem Statement

The primary objective is to develop forecasting models that can predict sourcing costs accurately based on historical data. The challenges include handling temporal trends, seasonality, and geographical variations in sourcing costs. The goal is to optimize sourcing strategies, reduce costs, and improve operational efficiency.

## Methodology

1. **Data Preprocessing**: Clean the dataset, handle missing values, and encode categorical variables.
2. **Exploratory Data Analysis (EDA)**: Analyze the distribution of sourcing costs, explore temporal trends, geographical variations, and correlations between variables.
3. **Time Series Analysis**: Apply time series techniques such as ARIMA to model and forecast sourcing costs.
4. **Machine Learning Models**: Train machine learning models such as RandomForestRegressor and XGBoost to predict sourcing costs based on additional features.
5. **Model Evaluation**: Evaluate the performance of models using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.

## Findings

- The ARIMA time series model performed poorly, indicating the need for alternative approaches.
- Machine learning models, particularly RandomForestRegressor and XGBoost, outperformed the ARIMA model in forecasting sourcing costs.
- Geographical analysis revealed variations in sourcing costs across different areas, highlighting opportunities for optimization.
- Temporal analysis identified trends and seasonality in sourcing costs, guiding strategic decision-making.

## Future Directions

- Further optimization of machine learning models through hyperparameter tuning and feature engineering.
- Exploration of additional features or external factors that may influence sourcing costs.
- Continuous monitoring and refinement of forecasting models to adapt to evolving trends and patterns.

## Author
  **Saahil Shaikh**
  **TY CSE**
Symbiosis Institute of Technology
