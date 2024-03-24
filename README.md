# Zomato1-stock-price-prediction-
Project based on Zomato Stock Price Prediction Machine Learning model using LR,DT&amp;RF Method

https://youtu.be/dMmBoLOCAPA?si=_lFjmXHMiLYxeIti

DESCRIPTION

This dataset presents historical stock price information for Zomato, a leading online food delivery and restaurant aggregator company. The dataset is compiled with data collected over a specific time period, showcasing the fluctuation in Zomato’s stock prices over days, weeks, or months, depending on the granularity of the dataset.This dataset is valuable for analysts, researchers, and investors interested in studying the historical performance and trends of Zomato’s stock in the financial markets. It can be utilized for various purposes such as technical analysis, trend forecasting, and quantitative modeling to make informed decisions related to investments or understanding market dynamics.

Approach

Step 1. Importing the Libraries such as

1.pandas,
numpy
matplotlib
seaborn
os
sklearn model selection import train_train_slpit
sklearn.preprocessing import OneHotEncoder,StandardScaler
sklearn.linear_model import LinearRegression,Ridge,Lasso
joblib import dump, load
klearn.linear_model import LinearRegression,Ridge,Lasso
sklearn.tree import DecisionTreeRegressor
sklearn.ensemble import RandomForestRegressor

Step 2. Dataset Reading.

Step 3.Describing Dataframe & shape.

Step 4. Data cleaning,creating Datetime index& checking null values.

Step 5. EDA (Exploratory Data Analysis),plotting graph with X as date vs y as open & close,
plotting graph X as date vs y as low & high,inding daily lag,Daily Returns,Daily returns mean & Std.

Step 6. Splitting The data,By importing train,test&split creating train test datas,checking x_train& y_train.

step 7.Separating Numerical & categorical datas.

step 8.Encoding categorical Data & scaling Numerical Data.

step 9.concatting Numerical & categorical data.

step 10. checking the values of train with Linear Regression,Decision tree Regression & Random Forest Regression.

step 11. creating Testpipeline and checking the values of y pred.

step 12. evaluating the model with linear Regression,Decision Tress Regression & Random Forest Regression.
Thank you.
