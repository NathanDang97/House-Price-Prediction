# House Price Prediction

## Overview

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

This Kaggle competition is a perfect practice for data science students who have completed an online course in machine learning and are looking to expand their skill set before trying a featured competition. 

## Data Files Description

Below is the description of each attached files in this project. The files can be found under the Data folder in this repository.

- train.csv - the training set
- test.csv - the test set
- data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
- sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

## Implementation

The chosen model was CatBoost Regressor which obtained an RMSE score of 0.13103, made about top 22% on the leaderboard. The full implementation with all the steps (EDA, Feature Engineering, Model Development, and Evaluation) can be found under the Main folder in this repository.
