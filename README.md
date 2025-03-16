# Amazon Stock Price Prediction

## Goal
The goal of this project is to predict Amazon's stock price for 2030 using historical stock data and machine learning models.

## Files
- `AMZN_stock_data.csv`: Historical stock data for Amazon.
- `stock_closing_prices.png`: Plot of Amazon stock's closing prices over time.
- `prediction_errors.png`: Visualization of prediction errors (residuals).
- `stock_price_prediction.png`: Visualization comparing true values and model predictions.

## Steps
1. **Data Preprocessing**: Load, clean, and process the stock data. 
2. **Feature Engineering**: Create lag features and rolling averages.
3. **Model Training**: Train three models (Linear Regression, Random Forest, and Support Vector Machines) and evaluate them.
4. **Prediction**: Use the trained model to predict Amazon's stock price for 2030.
5. **Evaluation**: Display performance metrics like MAE, MSE, and RMSE for each model.

## How to Run
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
