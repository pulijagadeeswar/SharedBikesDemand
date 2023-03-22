# Project Name
> Demand Prediction of shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people   to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- Goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
     The company wants to know:

        Which variables are significant in predicting the demand for shared bikes.
        How well those variables describe the bike demands  

- Historical bookings data set of BoomBikes is used for model

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The top 3 features contributing significantly towards explaining the demand of the shared bikes are ‘temp’, ‘windspeed’ and , ‘yr’
- There is a pattern categorical variable count of the booking for an instant. The variables like ‘season’, ‘yr’, ‘weathersit’, ‘month’, ‘holiday’ show much significance.
- Residual analysis using distribution plot and Q-Q plot show that residuals have normal distribution. Which show linear relationship between the dependent and independent variables


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - version 3.0
- library - numpy, Pandas, matplotlib, seaborne, sklearn, statsmodels


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by BoomBikes - A bike-sharing provider
- References : https://www.kaggle.com/competitions/bike-sharing-demand




## Contact
Created by [@pulijagadeeswar] - feel free to contact me!

