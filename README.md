# NY-Taxi-Demand-FB-Prophet-Time-Series-Forecast
In New York City, taxi has always been one of the main way to travel accross the entire city. Hence, it is important to deep dive into the demand data and understand the trend, seasonality, and patterns. The ultimate goal of this project is to create an effective time series forecasting model to forecast future demand.

## Data Source
In this project, the dataset comes from Kaggle. The link to the database is attached below. Within the dataset, we had information about every taxi trip that happened and started in NYC from 2016/01/01 to 2016/03/31. In general, there are 19 columns within the data frame. The data includes information, such as taxi pickup datetime, taxi dropoff datetime, number of customers, toll fee, total amount of the trip, total distance of the trip, and so on. https://www.kaggle.com/datasets/vishnurapps/newyork-taxi-demand

## Project Overview
In this project, I will aggregate the data to hourly level. In the end, I will create an hourly time series forecasting model. As for modeling techniques, in this project, I will try esemble models, such as ARIMA+PROPHET, ARIMA+LSTM, and LSTM+Prophet. In addition, I will also try time-based cross-validation techniques.
