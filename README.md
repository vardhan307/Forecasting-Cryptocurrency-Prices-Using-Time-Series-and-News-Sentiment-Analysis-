#  FORECASTING CRYPTOCURRENCY PRICES USING TIME SERIES AND NEWS SENTIMMENT ANALYSIS
# Project Overview
This project leverages advanced machine learning models such as GRU, LSTM, ARIMA, and XGBoost to forecast Bitcoin prices. By integrating sentiment analysis from social media and news, it aims to enhance predictive accuracy and provide insights into market trends.
# Features
#data collection :
i have downloaded bitcoin data from yahoo finance and uploaded the file in the git hub after downloading.
for Sentiment data we are using it through kaggle directly using API TOKEN i have uploaded the api token as well use that file to read the sentiment data
Preprocessing: Removing null values to prepare the dataset and Extracted Bitcoin price data and sentiment scores.
Feature Engineering: Created lagged features, rolling averages, and sentiment-price interaction terms.
# Model Implementation:
ARIMA: Captures linear trends.
LSTM and GRU: Learn sequential dependencies.
XGBoost: Handles non-linear feature interactions.
Sentiment Analysis: Captures market sentiment to improve forecasting.
Evaluation Metrics: RMSE, MSE, MAPE, and R² for performance comparison.
Installation and Dependencies
Python: Version 3.8 or above
# Required Libraries:
numpy
pandas
matplotlib
scikit-learn
tensorflow (for GRU and LSTM)
xgboost
statsmodels (for ARIMA)
Usage
EXPLORATORY DATASET ANALYSIS(EDA): performed analysis on my daya sets after preprocessing and creating features.
Feature Engineering: Added features for BTC price and sentiment data to interpret the results in multiple ways.
Model Training and Evaluation: Train models after splitting the data into train and test sets.
Forecast Visualization: Use libraries like matplotlib, Plotly, and Seaborn to generate visuals for better understanding.
Results
XGBoost outperformed other models with an R² of 0.97 and a low RMSE. Sentiment features enhanced short-term prediction accuracy.

# Future Work
Real-time sentiment analysis.
Testing models on other cryptocurrencies.
Exploring hybrid models for improved accuracy.
Acknowledgments
These sites contributed significantly to this project for finding research papers and datasets: [Google Scholar], [IEEE], and [Kaggle Datasets].
