# INSAID2022-DL-Foundation-Air_Quality_Index_Prediction
INSAID 2022 Deep Learning Foundation Term Project
# Project Description
## Introduction
Client for this project is an Air Quality Monitoring company.

* Due to an increase in the number of vehicles in your city, the air pollution level is increasing and is consequently affecting nature.

* Key task is to predict the air pollution index based on the historical data provided to help the government and the organization to administer the same.

* One of the key measurements in this process is AQI (Air Quality Index).

## Current Scenario
The air_pollution_index depends on certain parameters such as humidity, wind speed and direction, temperature, visibility, and more on a particular date at a mentioned time.

## Problem Statement
The current process suffers from the following problems:

* There is no denying that air pollution is impacting nature and the climate.
* An Air Quality Index (AQI) value of 201 to 300 translates to very unhealthy air quality conditions for survival, with high levels of health concern.
* AQI depends on various factors, which is why detecting it manually accurately can be a tedious and time consuming task.
* They want to automate the process of predicting Air Quality Index (AQI).

## Project Task
* Dataset contains all the necessary parameters such as humidity, wind speed and direction, temperature, visibility, and more on a particular date at a mentioned time.
* Project task is to build a regression model for predicting Air Quality Index (AQI).
## Project Deliverables
* Deliverable: Predict the Air Quality Index (AQI) of City.
* Machine Learning Task: Regression
* Target Variable: air_pollution_index
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the RMSE score.
# Data Description
* The columns contains all the necessary information which might affect the air pollution index.
* The column Air Pollution Index is also present in the dataset which is a measure of the overall win percentage.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 27000 rows and 15 columns.
* The column air_pollution_index is the target variable.

## Test Set:
* The test set contains 6750 rows and 14 columns.
* The test set doesn’t contain the air_pollution_index column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **date_time**   | Date Time value of the sample.                     |
|02| **is_holiday** | Whether the date is a holiday. If yes, then specifies the name of the holiday.               |
|03| **humidity**   | Humidity value.                     |
|04| **wind_speed** | Wind Speed value.               |
|05| **wind_direction**   | Wind Direction value.                    |
|06| **visibility_in_miles** | Visibility in Miles value.               |
|07| **dew_point**   | Dew Point value.                     |
|08| **temperature** | Temperature value .               |
|09| **rain_p_h**   | Rain per hour value.                     |
|10| **snow_p_h** | Snow per hour value.               |
|11| **clouds_all**   | Clouds all value.                   |
|12| **weather_type** | Weather Type.               |
|13| **traffic_volume**   | Traffic Volume.                     |
|14| **air_pollution_index** | Air Pollution Index value.               |
