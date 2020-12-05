# Seattle Housing Price Prediction Model
![seattle](https://seattlemag.com/sites/default/files/field/image/cityliving.jpg)

## Overview

This project uses SciKit and Python to run multiple regression analysis to predict housing prices in the Kings County, Seatle market. After performing explorataory data analysis and data cleaning on a training set, we generate relevant features and build a prediction model for a test set.

## Business Problem
When clients seek the services of a real estate agent, either as prospective buyers or sellers, it is important that the agent is able to provide estimates for what a home would sell for. The generated model in this project can output an estimate for a home given a list of parameters about the property.

## Approach
- ***Start with explatory data analysis*** to check for missing values, familiarize with features, and perform statistical analysis to understand interaction between paramenters

- ***Feature Engineer*** to help better predict the model than just running regression on the given parameters

- ***Generate regression model*** using *train-test split* method to check for effectivenss of features

- ***Prediciton*** of housing prices in the test dataset using model built from training dataset. 

## Outcome
Through the data exploration and modeling process, it could be determined that location (through zipcode grouping), condition of the building/quality of construction, and size of the property were the largest influencers on the price of Kings County houses. See the model notebook for a more detailed look at the process and outcome.

## Repository Structure
    .
    ├── modeling process                    # folder containing process notebooks
    ├── pickle_jar                          # folder contains pickled model and scaler 
    ├── provided_data                       # folder contains training and test csv files 
    ├── Kings_County_Model                  # final prediciton notebook, model implementation
    └── README.md                           # the very thing you're reading 👀 
