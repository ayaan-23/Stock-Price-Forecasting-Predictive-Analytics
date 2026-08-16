# Stock-Price-Forecasting-Predictive-Analytics
Stock price forecasting using Linear Regression, Random Forest, and ARIMA with historical AAPL data, model evaluation, and 15-day future predictions.
# Stock Price Forecasting Using Predictive Analytics

## 📈 Project Overview

This project focuses on forecasting future stock prices using historical market data. The project follows a complete predictive analytics workflow, including data collection, cleaning, exploratory data analysis, feature engineering, model training, evaluation, and future forecasting.

Real historical **AAPL stock data** is collected using `yfinance`.

## 🎯 Objectives

* Analyze historical stock price trends
* Clean and preprocess historical data
* Perform exploratory data analysis
* Create useful features for prediction
* Build regression and time-series models
* Compare model performance
* Forecast future stock prices
* Visualize actual, predicted, and future prices

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* yfinance
* Google Colab / Jupyter Notebook

## 🤖 Machine Learning Models

### Linear Regression

Used to predict stock prices based on engineered historical features.

### Random Forest Regression

Uses multiple decision trees to capture nonlinear relationships in the data.

### ARIMA

A time-series forecasting model used to predict future stock prices from historical price patterns.

## 🔄 Project Workflow

1. Fetch historical AAPL stock data
2. Clean and preprocess the data
3. Perform exploratory data analysis
4. Create features for prediction
5. Split data into training and testing sets chronologically
6. Train Linear Regression
7. Train Random Forest
8. Train ARIMA
9. Evaluate model performance
10. Compare models
11. Perform residual analysis
12. Generate a 15-business-day forecast

## 📊 Model Performance

| Model             |   RMSE |    MAE | MAPE (%) |     R² |
| ----------------- | -----: | -----: | -------: | -----: |
| Linear Regression |  2.990 |  2.347 |    1.651 |  0.922 |
| Random Forest     |  3.354 |  2.638 |    1.860 |  0.902 |
| ARIMA             | 12.772 | 10.320 |    6.987 | -0.477 |

**Best model by RMSE: Linear Regression**

Linear Regression achieved an RMSE of **2.990** and an R² score of **0.922** on the evaluated test period.

## 📈 Visualizations

The project includes:

* Historical stock price trend
* Actual vs. predicted prices
* Model performance comparison
* Residual analysis
* Residual distribution
* Future stock price forecast
* 95% forecast confidence interval

## 🔮 Future Forecast

ARIMA is refitted using the full historical price series and used to forecast the next **15 business days**. A **95% confidence interval** is also generated around the forecast.

## 📌 Conclusion

This project demonstrates how historical stock-market data can be used for predictive analytics and forecasting. Three different models were evaluated, with **Linear Regression** achieving the best RMSE among the tested models. ARIMA was additionally used for future time-series forecasting.

The project provides practical experience in data preprocessing, feature engineering, regression, time-series analysis, model evaluation, visualization, and forecasting.

## ⚠️ Disclaimer

This project is created for educational purposes only. Stock-price predictions are uncertain and should not be considered financial advice.
