# Covid19_FeatureImportance #
Regression modelling to find measures important in controlling infection 

## Overview ##
Since the outbreak of COVID-19 in Wuhan, China, the infection has spread around the world. On the 11th of March, 2020, the World Health Organisation has declared it as a pandemic. This project is to examine the imposed measures in countries around the world, and which measures played significant roles in controlling the target variable (i.e the shape of the curves of 7-day rolling average of daily cases). Our study focusses on the countries where the number of confirmed cases are higher compared to Australia. As of today i.e 28-Aug-2020, the total number of such countries used in this study is 67 and the total number of measures is 33.

## Data ##
The datasets are downloaded from https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases. They are time series data tracking the number of people affected by COVID-19 worldwide and include cases of confirmed data. The measures data acaps_covid19_government_measures_dataset.xlsx is also sourced from the same site.

## Analysis and Modelling ##
Create feature vector using the imposed measures applicable for respective countries. Different regression models, for ex, Lasso, 
XGBoost and LightGBM are used to predict target variable. An aggregated output using XGBoost and LightGBM is used for our final insight.

## Ongoing ##

## Credit ##
The above concept and work is done by me (Gita Das) and Catherine Lopes. For any code related issue, please contact me directly 
at das_gita@hotmail.com
