# Data1030Project
Solving for Happiness 

This repository holds the source code and final results of the project I created for Data1030, an introductory course to Data Science. This project encompassed the complete development and implementation fo a machine learning pipeline. The purpose of this pipeline was to use economic and social data to predict the happiness index of 47 countries overtime. 

The figures directory holds the various graphs and tables that were produced during my exploratory data analysis and hyperparameter tuning excersies. Through a comprehensive review of my data I found the most and least correlated features with the happiness variable. This analysis helped to tune my approach for developing models that would attempt to predict a current year's happiness index using historical data. 

The results directory stores the predictions calculated by each of my models for the test years of 2018-2020. Overall, I determined that the best model for predicting future happiness was the Ridge Regressor. This model produced predictions with the lowest root mean squared error (RMSE) of 0.251. These results indicate that my model, using historical economic and social data, can predict the happiness of a country within +/- 0.251 of its true index. 

Software used throughout project:

- Python version is 3.10.5
- numpy version 1.22.4 
- matplotlib version 3.5.2 
- sklearn version 1.1.1 
- pandas version 1.4.2 
- xgboost version 1.5.1 
- shap version 0.40.0 
