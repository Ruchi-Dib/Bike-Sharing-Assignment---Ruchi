# Project Name
> Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This assignment is a programming assignment wherein I am building a multiple linear regression model for the prediction of demand for shared bikes.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
#### The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
#### Dataset used here is play.csv

## Conclusions
- Final Train model r2 = 83.5%
- Final Test model r2 = 79.61%
- Since the variance between train and test model is not very significant and also the y_test & y_pred regplot provides a good linear regression, the above derived model looks ok.

#### Significant Variables in predicting the demand for shared bikes and how well these variables describe the bike demands are as below:
- Temperature: temp has the highest coefficient and thus, it means that a unit increase in temp, demand for shared bikes increases by it's coefficient.
- Year 2019: There is YoY growth
- Season (Summer & Winter): Demand for shared bike increases in Summer and Winter season where winter has the higher coefficient.
- Year: September month sees highest demand in all the months.
- Weekday: In all days of the week, Saturday has the highest demand for shared bikes.
- Working days
- Weathersit: Weather - Mist & Cloudy and Light Snow, have adverse impact on the shared bike demand. Both have negative coefficients with light snow weather has higher negative coefficient.
- Windspeed: This variable too indicates adverse impact on shared bike demand with negative coefficient.

## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.13.2
- statsmodels - version 0.14.0
- sklearn - version 1.2.2

## Acknowledgements
- This project is based on Upgrad assignment [https://learn.upgrad.com/course/5800/segment/52631/312290/946791/4725024]

## Contact
Created by agl.vinay@gmail.com - feel free to contact me.
