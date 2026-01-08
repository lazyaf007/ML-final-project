# Cryptocurrency Volatility Prediction

This project predicts cryptocurrency market volatility using machine learning techniques.

## Objective
The objective of this project is to forecast cryptocurrency price volatility using historical market data such as Open, High, Low, Close (OHLC) prices, trading volume, and market capitalization.

## Dataset
The dataset contains daily historical cryptocurrency data including:
- Open price
- High price
- Low price
- Close price
- Trading volume
- Market capitalization

## Feature Engineering
The following features were engineered:
- Volatility = (High − Low) / Close
- 7-day Moving Average
- 14-day Moving Average
- Liquidity Ratio (Volume / Market Capitalization)

## Model Used
- Random Forest Regressor

## Model Performance
- RMSE: 0.0510
- MAE: 0.0262
- R² Score: 0.5377

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run the Project
1. Place the dataset inside the `data` folder.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
