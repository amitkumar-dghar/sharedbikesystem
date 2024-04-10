# Bike Sharing System
- This project focuses on constructing a linear regression model to forecast the demand for shared bikes from a US bike-sharing provider, BoomBikes. The goal is to navigate through the revenue dips caused by the Corona pandemic.

## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- The purpose of this project is to help BoomBikes understand the dynamics of shared bike demand after the Covid-19 pandemic. The project's primary objective includes identifying major variables influencing bike demand and predicting future demands with a high degree of accuracy.

- The need for this project emerged from significant revenue losses due to decreased mobility amidst the pandemic. The project aims to facilitate strategic business planning to accelerate revenue growth post-pandemic.

- The dataset used in this project consists of daily bike rental records. It includes variables such as weather conditions, seasonality, and user type (either casual or registered). The dataset covers the years 2018 and 2019.


## Technologies Used
- pandas - for data manipulation and analysis.
- numpy - for handling large, multi-dimensional arrays and matrices
- scikit-learn - for implementing various machine learning, preprocessing, cross-validation and visualization algorithms
- matplotlib - for data visualization and graphical plotting.


## Conclusions
- The linear regression model demonstrates a strong ability to predict bike rental demand, with an R-squared score of approximately 0.852 on the test set, suggesting that the chosen features strongly indicate demand.
- Seasonal and weather-related variables, along with the year of rental, significantly impact bike rental demand, thereby underscoring the importance of strategic planning around these factors.
- It is recommended to continuously monitor and adjust the model as more data becomes available, especially considering potential shifts in user behavior post-pandemic.


