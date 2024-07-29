### Stock Price Prediction and Trading Strategy

### Overview

This project develops a stock price prediction model and trading strategy using machine learning techniques to optimize trading decisions based on historical data.

### Motivation

The primary motivation for this project is to leverage machine learning and advanced data analysis techniques to predict stock price movements accurately. By developing an effective predictive model, we aim to enhance trading strategies, maximize profits, and reduce financial risks. This project also explores the application of deep learning and ensemble methods in financial markets, contributing to the broader field of quantitative finance.

### Workflow

1) Data Preparation

Connect to Google Drive for dataset access.
Calculate percentage changes in stock closing prices.
Classify price changes into decrease, no change, and increase.

2) Feature Engineering

Generate features from OHLC data for the last 100 rows.
Enrich the dataset with these features.

3) Model Training

Train models like Decision Trees, Gradient Boosting, SVCs.
Use balanced class weights to handle data imbalance.
Implement cross-validation and grid search for model tuning.

4) Model Evaluation and Ensembling

Compare performance of different models.
Employ ensembling techniques for better accuracy.
Explore deep learning models.

5) Testing and Execution

Test models on external datasets.
Implement and evaluate trading strategies based on predictions.

### Technologies and Libraries

1) Data Handling: pandas, numpy, matplotlib
2) Technical Analysis: ta
3) Statistics: scipy, statistics
4) Machine Learning: sklearn, xgboost, torch, torchensemble
5) Optimization: torch.optim
6) Model Evaluation: cross_val_score, RepeatedStratifiedKFold, GridSearchCV
7) Preprocessing: LabelEncoder
8) Visualization: matplotlib, quantstats
9) Trading Simulation: gym, stable-baselines3, gym_anytrading
10) Utilities: pickle, tqdm, warnings

### Conclusion

This project significantly enhanced my understanding and skills in machine learning, particularly in applying these techniques to financial markets. The models developed not only provided accurate predictions but also helped in creating robust trading strategies. For customers, the predictive models demonstrated high accuracy, with precision scores above 85% in identifying stock price movements. These models can serve as powerful tools for traders and financial analysts, aiding in making informed decisions and optimizing trading strategies. By leveraging advanced ensemble methods and deep learning, this project contributed to more reliable and effective financial forecasting, ultimately helping to maximize returns and minimize risks in trading activities.
