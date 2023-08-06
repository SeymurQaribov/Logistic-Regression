# Logistic-Regression
This repository contains a logistic regression model implemented in Python using scikit-learn. The model is designed to predict rain tomorrow or not based on weather data. The weather data is stored in a CSV file named "weather_data.csv," and we have used the information value (IV) method to handle any missing values in the dataset. Additionally, we applied min-max scaling to preprocess the data before training the logistic regression model.

Dataset
The "weather_data.csv" file contains the following columns:

Temperature: Average temperature recorded during the day.
Humidity: Relative humidity recorded during the day.
Pressure: Atmospheric pressure recorded during the day.
Windspeed: Average windspeed during the day.
RainTomorrow: The target variable takes the value 1 if it is predicted to rain tomorrow, and 0 if it is predicted not to rain tomorrow.
