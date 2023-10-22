# Surprise_Housing_Case_Study
Linear Regression model case study for Boom Bikes

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
Surprise Housing is US based housing Company. It uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. Company has now decided to enter Australian market. It is looking at prospective properties to buy to enter the market.

Business Goal

Surprise Housing requires a model that can be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Aim of the case study

To understand the factors affecting the price of houses in Australian market. The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
To create regression model using regularisation in order to predict the actual value of the prospective properties:
determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
Optimal value of lambda for Ridge Regression = 2.0
Optimal value of lambda for Lasso Regression = 0.0001

Variables significant in predicting the price of a house are:
OverallQual_9, OverallQual_8 , MSZoning_FV, MSZoning_FV, MSZoning_RH, MSZoning_RM, GrLivArea, Exterior1st_BrkFace, GarageYrBlt_2008,OverallQual_7,Functional_Typ

How well those variables describe the price of a house

- OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.24 to 1.27 times
- GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.13 times
- MSZoning: If general zoning classification of house is Floating Village Residential and Residential High Density , Residential Low Density and Residential Medium Density then price will increase from 1.15 times to 1.4 times
- Exterior1st_BrkFace : If exterior covering of house is Brickface then price will increase by 1.1 times

## Technologies Used
python 3.0
Acknowledgements
This project was a problem statement given by IIIT-B for the cohort course of ML-AI.

## Contact
Created by [@IshaSukhija] - feel free to contact me!
