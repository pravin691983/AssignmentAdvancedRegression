# Assignment Advanced Regression

> To build a model the price of houses with the available independent variables.

## Table of Contents

- [Overview Business Understanding](#overview-business-understanding)
- [Problem Statement Business Objectives](#problem-statement-business-objectives)
- [Data in depth](#data-in-depth)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Overview Business Understanding

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Problem Statement Business Objectives

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

### Want to

- Understand the driving factors (or driver variables) behind Sell price of hourses, i.e. the variables which are strong indicators of price of a house.
- To build a model the price of houses with the available independent variables using the optimal value of lambda for ridge and lasso regression.

## Data in depth

- We are going to analyze datasets,
- The datasets contains details information related of the houses prices sharing such as MSSubClass, BedroomAbvGr, PoolArea, YrSold etc.
- The dataset comprises of 1460 observations of 81 columns. Below is a table showing names of the few columns.

## Approach

#### Understanding the Dataset

- To gain insights from data we must look into each aspect of it very carefully. We will start with observing few rows and columns of data both from the starting and from the end.

#### Preprocessing

- We will deal with erroneous, missing and outliers values of columns.
- Correlation between different columns
- See how preprocessing have transformed our dataset.
- Derive new data from existing data to get more insite

#### Exploratory Data Analysis on Loan Dataset

- Try to find out answers of some set of questions

#### Build Model after Dataset split

- Build model & validate results after split dataset in train & test repsectiviey using multiple linear regression model using the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on our analysis and as per our final Model and with the references in changes in the coefficients after regularization, the top 10 predictor variables that influences the House sell price are:

- LotArea ----- Lot size in square feet
- OverallQual ----- Rates the overall material and finish of the house
- OverallCond ----- Rates the overall condition of the house
- YearBuilt ----- Original construction date
- BsmtFinSF1 ----- Type 1 finished square feet
- TotalBsmtSF ----- Total square feet of basement area
- GrLivArea ----- Above grade (ground) living area square feet
- TotRmsAbvGrd ----- Total rooms above grade (does not include bathrooms)
- Street_Pave ----- Pave road access to property
- RoofMatl_Metal ----- Roof material_Metal

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@pravin691983] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
