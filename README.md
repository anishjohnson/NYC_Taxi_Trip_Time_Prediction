![image](https://user-images.githubusercontent.com/87002524/152673275-92be9501-59c5-4d45-b9b9-c6d1e4c8202a.png)
# Project Title : Taxi trip time Prediction : Predicting total ride duration of taxi trips in New York City
## Problem Description
### Your task is to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.
## Data Description
### The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.
## NYC Taxi Data.csv - the training set (contains 1458644 trip records)

# Data fields:
### id - a unique identifier for each trip
### vendor_id - a code indicating the provider associated with the trip record
### pickup_datetime - date and time when the meter was engaged
### dropoff_datetime - date and time when the meter was disengaged
### passenger_count - the number of passengers in the vehicle (driver entered value)
### pickup_longitude - the longitude where the meter was engaged
### pickup_latitude - the latitude where the meter was engaged
### dropoff_longitude - the longitude where the meter was disengaged
### dropoff_latitude - the latitude where the meter was disengaged
### store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
### trip_duration - duration of the trip in seconds

# Steps involved:
### 1. Import Data and Libraries.
### 2. Exploratory Data Analysis.
### 3. Data Cleaning and Feature Engineering.
### 4. Data Preparation.
### 5. Model Selection.
### 6. Hyperparameter Tuning.
### 7. Conclusions.

### *Currently four algorithms have been utilised to predict trip_duration which include Linear Regression, Decision Tree Regressor, XG Boost Regressor, Hist Gradient Boosting Regressor.*
### *From which Hist Gradiennt Boosting Regressor has given the best results in terms of r2_score and RMSE.*
