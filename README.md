# Bike-sharing system
> Brief description of our project:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Table of Contents
* General Information
* Technologies Used
    * Linear Regression
    * RFE
* Conclusions
    * Top 3 variables are: temperature, year and season



## General Information
The company wants to understand the factors affecting the demand, particulary:
* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands
Dataset that was used: day.csv

Steps performed:
* Problem Statement
* Reading, understanding and visualising data
* Preparing the data for modelling
* Training the model
* Residual Analysis
* Prediction and Evaluation


## Technologies/Libraries Used:
- Jupyter Notebook
- Python 3.8
- seaborn - version 0.11.2
- matplotlib - version 3.4.3
- pandas - version 1.2.3
- numpy - version 1.20.1
- sklearn -version 0.24.2
- statsmodels -version 0.11.0


## Conclusions
- Conclusion from the analysis:
* All the positive coefficients like temp, yr, season_winter, mnth_sept, season_Summer, weekday_sat and workingday indicate that these are positively correlated to the target variable, cnt.
* And all the negative coefficients indicate that an increase in these values will lead to an decrease in the value of cnt.
* Temp is the most significant with the largest coefficient of 0.549892.
* Followed by Year and Season.
* Bike sharing is more during the month of September.
* There is a decrease in the demand when the Weather situation is bad (Snow).

* Therefore as per our final Model, below are the top 3 variables that influence the demand:
1. Temperature
2. Year
3. Season


## Contact
Created by [@ShruthiNandakumar] - feel free to contact me!
