# Market Trend Prediction with Logistic Regression
This project focuses on predicting market trends (bullish or bearish) using machine learning techniques. 
The main objective is to build a model that can classify financial market data based on selected features using a logistic regression algorithm. 
The model provides insights into whether the market is likely to experience a positive (bullish) or negative (bearish) trend.

# Overview<br>
This project uses historical market data to predict whether the market will trend upwards (bullish) or downwards (bearish).
A logistic regression model was trained on selected features like moving averages, volume indicators, volatility measures, and other relevant financial metrics. 

# Features<br>
Market Data Processing: Data cleaning, feature extraction, and transformation based on various financial indicators such as moving averages, volatility, price momentum, and volume.<br>
Model Training: Logistic regression classifier for predicting market trends (bullish/bearish).<br>
Feature Scaling: The use of StandardScaler to normalize the data.<br>
SMOTE Balancing: Synthetic Minority Over-sampling Technique (SMOTE) is applied to balance class distribution during training.<br>
Model Evaluation: The model is evaluated using accuracy, precision, recall, and F1-score metrics.<br>
Key Features Used for Prediction:<br>
Close, Volume, policy_change, fedrate, Rolling Std (30-day), MA_7_50_diff, MA_30_200_diff, MA_7_slope, Price_Change_Open_Close, Shock Event, and others.<br><br>

# Technologies Used<br>
Python 3.x<br>
scikit-learn: For machine learning and data processing.<br>
pandas: For data manipulation.<br>
numpy: For numerical operations.<br>
matplotlib / seaborn: For visualization (if needed).<br>
joblib: For saving/loading models and scalers.<br>
imbalanced-learn: For SMOTE balancing.<br>

# License<br>
This project is licensed under the MIT License - see the LICENSE file for details.
