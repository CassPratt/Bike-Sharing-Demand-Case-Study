# Bike Sharing Demand Case Study
> Linear Regression to model the demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- **BoomBikes** is a US bike-sharing provider that wants to understand the factors affecting the demand for these shared bikes in the American market. 
- The company wants to know **which variables are significant in predicting the demand for shared bikes**.
- The dataset being used has daily bike demands across the American market from 2018 and 2019.
- **Using Linear regression** we will model the demand for shared bikes with the available independent variables.

## Technologies Used
- Python version:  3.9.7
- Pandas version:  1.3.4
- Seaborn version:  0.11.2
- Matplotlib version:  3.4.3
- scipy version:  1.7.1
- SKLearn version:  0.24.2
- statsmodels version:  0.12.2

## Conclusions
- It is possible to model the demand for shared bikes with provided variables.
- When the business team is planning the bikes supply, they need to take in account all **variables found to be significant** but give **most consideration to the 3 variables indicated below**:
  - temp (positive relation)
  - yr (positive relation)
  - weathersit_light_snowandrain (negative relation)
- The **best time to increase the supply** is during the Summer, when there are high temperatures but not high windspeed or rain.
  - It is also great to know that **they will have bike rentals no matter the time**!

## Contact
Created by [@CassPratt] - feel free to contact me!
