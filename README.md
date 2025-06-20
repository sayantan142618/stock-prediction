# 📈 Stock Price Prediction using Linear Regression

This project demonstrates a simple yet effective approach to predict stock prices using **Linear Regression** with historical data. The model uses closing prices of a selected stock over time and fits a linear regression model to forecast future prices.

## 🧠 Technologies Used

- Python 3
- Jupyter Notebook
- Scikit-learn
- yFinance
- Matplotlib
- Pandas

## 📁 Files in this Repository

- `Stock_prediction Linear Regression.ipynb` – Jupyter notebook version of the model.
- `Stock_Price_Prediction model.ipynb` – Alternative/extended version of the notebook.
- `Stock Linear Regression Python File.py` – Python script version for CLI or IDE use.

## 🚀 How It Works

1. **Data Collection**  
   Stock data is fetched using the `yfinance` library (default: AAPL from 2015 to 2024).

2. **Preprocessing**  
   - Extracts closing prices.
   - Converts dates into numerical values (days since start).

3. **Model Training**  
   - Linear Regression is trained on historical data.
   - Train/Test split is used to evaluate model performance.

4. **Prediction & Visualization**  
   - Displays model accuracy using Mean Squared Error (MSE).
   - Visualizes actual vs. predicted prices.
   - Forecasts stock price 30 days into the future.

## 📊 Sample Output

- **Model Equation**:  
Price = m * Days + c


## 📦 Requirements

Install the required packages using pip:
pip install yfinance scikit-learn matplotlib pandas

⚠️ Limitations
1.This is a basic linear regression model that assumes a linear trend in stock prices over time.

2.Market behavior is non-linear and influenced by complex, external factors (e.g., news, macroeconomics, investor sentiment).

3.Does not include features like volume, open/high/low prices, or technical indicators.

4.Not suitable for real financial trading decisions. This model is intended for educational/demo purposes only.

5.No handling for volatility, seasonal patterns, or sudden shocks. 
🛠 Customization
Change the ticker symbol (e.g., "GOOG", "TSLA") in the script.

Adjust date ranges or prediction horizons.

Replace Linear Regression with other models (e.g., SVR, LSTM) for improved performance.
