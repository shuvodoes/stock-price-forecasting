# Stock Price Prediction Model

This project predicts stock prices using machine learning with **Random Forest Regressor**. The model is trained on Yahoo Finance stock data.

# Requirements

- Python
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - openpyxl (for reading Excel files)

# Model Overview

- The model uses Yahoo Finance stock data (Open, High, Low, Close, Volume).
- **Feature Engineering**: It calculates two Simple Moving Averages (SMA_10 and SMA_50) as features.
- **Model**: The model uses a Random Forest Regressor to predict future stock prices.
- **Evaluation**: The model is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE) and R² Score.

## License
MIT License

Made by Shuvo.
