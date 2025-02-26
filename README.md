# Boom Bikes Demand Analysis Linear Regression Model

This assignment is a programming assignment wherein we will build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Business Goal
To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Dataset
The dataset used for the analysis: [dataset](./day.csv)


## Conclusions
- The bike rental is highest in the fall, followed by summer, winter and spring.
- Weather plays an important role. Bike rental is highest in clear weather and decreases as the weather worsen.
- workingday seems to have very less impact.
- Business have grown significantly over the year from 2018 to 2019.
- Bike rental distribution in months is similar to seasons.
- Average temperature is highest in the fall and lowest in the spring. July having the highest temperature.
- Average number of rentals per day is also highest in the fall and least in the spring. This is displaying the high correlation between temp and cnt.
- For the final model, R-squared on train data: 0.8300; Adjusted R-squared on train data: 0.8269 and R-squared on test data: 0.8153; Adjusted R-squared on test data: 0.8063




## Technologies Used
- Python                    3.12.4
- pandas                    2.2.3
- numpy                     2.1.3
- matplotlib                3.9.3
- scipy                     1.14.1
- seaborn                   0.13.2
- scikit-learn              1.6.1
- statsmodels               0.14.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was created as a case study required for Executive PG Programme in Machine Learning & AI - IIIT, Bangalore
- This project was based on UpGrad tutorials on Linear Regression on the learning platform.


## Contact
Created by [@projeshMondal](https://github.com/projeshMondal) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->