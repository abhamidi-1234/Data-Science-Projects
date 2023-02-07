# Data Science Projects

### 1. Detecting Parkinson's Disease using XGBoost

  - Detecting Parkinson's disease with XGBoost
  - Dataset: UCI ML Parkinson's dataset from https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/
  - Features have been scaled to be between -1 and 1
  - Hyperparameter tuning using GridSearchCV
  - Accuracy = 94.87%
  
### 2. Time Series Analysis and prediction of Wind Generation
  
  - Time series analysis of wind generation data
  - Analyse Autorcorrelation plots
  - Analyse variability of wind generation over different time scales
  - Variance Ratio test to check the random walk hypothesis
  - AdFuller test to check for stationarity
  - Use AIC and BIC to select optimal parameters for the ARIMA model
  - ARIMA model to predict wind generation
  
### 3. Detecting Heart Disease using SVM

  - Dataset from UCI Machine Learning Repository
  - Deal with missing data
  - Use One-Hot Encoding for categorical data
  - Hyper-parameter tuning with GridSearchCV
  - Visualized the results using PCA by reducing dimentionality
  - Achieved an accuracy of 89.33%

### 4. Stock Price Sentiment Analysis using News Headline

  - Pre-process data by removing numbers and punctuations 
  - Create bag-of-words model  
  - Generate unigram and bigram features from 25 news headlines for each company 
  - Use random forest classifier to predict whether the stock price will increase or decrease
  - Achieved an accuracy of 85%

### 5. Stock Price Prediction using Stacked LSTM

  - Gather stock data using Yahoo Finance API
  - Take a window of previous 100 days to use as training data and 101st day as output
  - Build Stacked LSTM neural network
  - Predict the stock price
  - Plot an interactive stock price graph with predicted values
 
