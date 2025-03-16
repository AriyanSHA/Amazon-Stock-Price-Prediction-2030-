# Amazon Stock Price Prediction (2030)

This project aims to predict the Amazon stock prices for the year 2030 using historical stock price data and machine learning models. The primary goal is to forecast future prices based on past stock market performance.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Features](#features)
- [Modeling and Evaluation](#modeling-and-evaluation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project uses historical stock price data of Amazon (AMZN) to build machine learning models that can predict the stock price for the year 2030. The following steps are implemented:

1. **Data Preprocessing**: Clean and preprocess the data.
2. **Feature Engineering**: Create lag features and rolling averages.
3. **Modeling**: Train and evaluate different machine learning models:
    - Linear Regression
    - Random Forest Regressor
    - Support Vector Machine (SVM)
4. **Evaluation**: Evaluate the model's performance using error metrics like MAE, MSE, and RMSE.
5. **Prediction**: Forecast Amazon's stock price for 2030.

## Technologies Used

- **Python**: The primary programming language used for data analysis and modeling.
- **Pandas**: Data manipulation and preprocessing.
- **Matplotlib & Seaborn**: Visualization of stock prices and model predictions.
- **Scikit-learn**: Machine learning algorithms for prediction (Linear Regression, Random Forest, SVM).
- **NumPy**: Numerical computations and operations.
  
## Data

The data used in this project is Amazon's historical stock prices, which can be obtained from a CSV file. The dataset includes the following columns:

- `Date`: The date of the stock price data.
- `Open`: Opening stock price.
- `High`: Highest price of the stock during the day.
- `Low`: Lowest price of the stock during the day.
- `Close`: Closing stock price (used for prediction).
- `Volume`: Trading volume of stocks.

### Dataset Source

You can download the dataset from any public financial data provider (such as Yahoo Finance, Google Finance, etc.) or use the provided `AMZN_stock_data.csv` if available.

## Features

- **Lag Features**: These represent the stock price from previous days (e.g., 1, 5, and 30 days).
- **Moving Averages**: Rolling averages for 5 and 30 days are used as features to capture trends over time.

## Modeling and Evaluation

The following machine learning models are used in this project:

1. **Linear Regression**:
    - A simple yet effective method for predicting continuous values.
2. **Random Forest Regressor**:
    - A more complex model that can capture non-linear relationships.
3. **Support Vector Machine (SVM)**:
    - A powerful regression technique for high-dimensional datasets.

Each model is evaluated using the following error metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

## How to Run

1. **Install Dependencies**: You can install the required Python packages by running:

   ```bash
   pip install -r requirements.txt
