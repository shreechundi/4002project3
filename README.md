# AMIRA Modeling of Consumer Price Index Values
## Goal 
The goal of this project was to utilize time series data pertaining to consumer price indices for urban consumers in order to examine inflation levels over time in urban areas in the United states. We also aim to predict inflation levels to assess future economic performance and conditions. 
## Contents
This repository contains original data collected by the Federal Reserve Bank of St. Louis of CPI values (not including food or energy) of urban areas in the United States. These values were collected on the first of every month from 1957 through October 2023. It contains the code used to map the CPI data to observe inflation trends over the decades. It also contains the code necessary to implement the ARIMA model, used to implement a forecasting model to predict future inflation. 
 
## SRC 
### Installing/Building Code
To begin analyzing the data, we imported the numpy, pandas, and matplotlib packages to conduct statistical analysis on and create visual representations of our data. We also imported DateOffset derived from the pandas package, which we utilized to implement forecasting. From there, we derived the coefficients necessary of p - the order of the autoregressive model, d - the degree of differencing, and q- the order of the moving average model to establish our ARIMA model. 
### Usage 
We used the ARIMA model to implement a forecasting model to predict future inflation. We created a trend forecast for the next 10 years which gave us a good estimate of what inflation could look like in the next decade. 

## Data Dictionary
| Column| Description| Potential Reponses|                   
|-------|------------|-------------------|
|Observation Date | First day of every month since 1957.|A date in YYYY-MM-DD format.|
|CPI| Consumer Price Index value for urban consumers not accounting for food and energy.| An integer that represents the consumer price index.| 

## References 
https://fred.stlouisfed.org/series/CPILFESL 

https://www.analyticsvidhya.com/blog/2020/10/how-to-create-an-arima-model-for-time-series-forecasting-in-python/

Project 3 MI 1: https://docs.google.com/document/d/16S0hADJYHsNCGHE4ZbJgelS6yxIPei9wmL-6-RPb5RY/edit?usp=sharing

Project 3 MI 2: https://docs.google.com/document/d/14mgFQv46I2Qkf8qxf0K2p79RAlZnR2WwTVQKa20C3wE/edit?usp=sharing
