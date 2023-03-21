# Stock Price Prediction Model
## Problem Statement
Stock prices are an essential component of the financial market, with billions of dollars being invested in stocks each day. Accurate stock price predictions are crucial for investors, traders, and financial institutions. A stock price prediction model can help address this challenge by providing accurate estimates of stock prices. A stock price prediction model can be used by investors and traders to make informed decisions about buying and selling stocks. By analyzing various economic and market factors such as company earnings, industry trends, market sentiment, and geopolitical events, these models can predict future stock prices with a high degree of accuracy. This information can help investors and traders make profitable decisions and minimize their risks.
## Data Information
The dataset can be download using this [link](https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021)

This dataset provides historical data of Tesla Inc (stock-TSLA). The data is available at a daily level. Currency is USD. It has been updated till 28/June/2021
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. In the current dataset, the date is given in a string format. So, we have converted it into a datetime format for processing.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the XGBRegressor as our model available in the xgboost library. We also need to evaluate the models using appropriate evaluation metrics.
