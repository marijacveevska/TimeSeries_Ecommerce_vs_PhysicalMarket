# Forecasting the Superior Fit for Business Growth: E-commerce vs. Physical Market
Time Series Analysis in R Language.

## Outline
1. [Preprocessing the Data](#1-preprocessing-the-data)
2. [Exploratory Data Analysis](#2-exploratory-data-analysis)
3. [Finding the Best Model](#3-finding-the-best-model)
4. [Forecasting](#4-forecasting)
5. [Conclusion and Possible Improvements](#5-conclusion-and-possible-improvements)

## 1. Preprocessing the Data
Data preprocessing is a crucial step in any data analysis project. For this project, the following steps were taken:
- **Data Cleaning**: Removed missing values, handled outliers, and corrected inconsistencies in the dataset.
- **Data Transformation**: Normalized and scaled data to ensure compatibility with various models.
- **Feature Engineering**: Created new features that could provide additional insights and improve model accuracy.

## 2. Exploratory Data Analysis
Exploratory Data Analysis (EDA) involves examining the dataset to understand its structure, main characteristics, and potential relationships between variables. The following steps were performed:
- **Visualization**: Plotted time series line plots to visualize trends and distributions.
- **Statistical Analysis**: Calculated summary statistics to understand the central tendencies and dispersions.
- **Correlation Analysis**: Identified correlations between different features to understand their relationships.

## 3. Finding the Best Model
The goal was to identify the best model for forecasting sales in both the E-commerce and Physical Market sectors.

### Models Explored for Physical Market
1. **Generalized Bass Model (GBM) + SARMAX**: Combined to capture both innovation diffusion and seasonality.
2. **Time Series Regression, Piecewise Regression**: Evaluated for their ability to model different segments of the data.

### Models Explored for E-commerce
1. **GAM with Holt-Winters'**: Used to capture smooth trends and seasonal effects.
2. **Generalized Bass Model with ARIMA and Gradient Boosting**: Combined linear and nonlinear modeling approaches.

## 4. Forecasting
Based on the model testing phase, the following models were selected for forecasting future sales:

### Physical Market Modeling
- **Piecewise Regression**: Identified as the best fit model for forecasting sales in the physical market due to its ability to model different segments effectively.

### E-commerce Modeling
- **GBM with ARIMA and Gradient Boosting**: Chosen as the best model for E-commerce due to its superior performance in capturing both diffusion and complex nonlinear patterns.

## 5. Conclusion and Possible Improvements

### Market Forecasts for 2027
- **Physical Market**
  - **Forecasted Sales (2027)**: $2,153,330
  - **Growth (2022-2027)**: 38.6%
- **E-commerce**
  - **Forecasted Sales (2027)**: $559,325
  - **Growth (2022-2027)**: 84.5%

This project demonstrates the effective application of different time series and regression models to forecast sales in E-commerce and Physical Markets. The insights derived can guide strategic decision-making and business growth planning.\

Dataset - Combined data sources from census.gov and statista.com
Team Members: MARIJA CVEEVSKA | SULEYMAN ERIM | JOAN ORELLANA RIO
