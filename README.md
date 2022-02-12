# Demand Forecasting
### Store Item Demand Forecasting with LightGBM

<p align="center">
  <img width="600" height="300" src="https://imageio.forbes.com/specials-images/imageserve/6179e7e6179fcfe3c9e7de16/demand-spike/960x0.jpg?fit=bounds&format=jpg&width=960">
</p>

# Business Problem
It is desired to create a 3-month demand forecasting model for 10 different stores and 50 different products of a chain of stores.

# Dataset
A store chain's 5-year data includes information on 10 different stores and 50 different products.

The dataset covers the period between 01-01-2013 and 31-12-2017.
# Variables
date – Date of sales data (There is no holiday effect or store closures.)

store – Store ID (Unique number for each store.)

item – Product ID (Unique number for each product.)

sales – Number of items sold, Number of items sold from a particular store on a given date
# Task
Using the following time series and machine learning techniques, a 3-month demand forecasting model was created for the relevant store chain.

Random Noise

Lag Shifted Features

Rolling Mean Features

Exponentially Weighted Mean Features

Custom Cost Function (SMAPE)

Model Validation with LightGBM

# Results

I obtained an average SMAPE score of 14.14 for the forecasted demands over the test data. It is observed that the exponentially weighted mean features produce the most distinguishing characteristics for the task.




