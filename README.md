# Housing Price Prediction Kaggle

This repository contains the jupyter notebook for the housing prices prediction competition on Kaggle. The training data consists of 1460 houses and 79 features describing the houses in Ames, Iowa which is then used to predict house prices for the test data.

The notebook is divided into sections:
1) Exploratory Data analysis
2) Data preprocessing:
    a) Fill missing values
    b) Remove outliers
    c) Treating Skewness
    d) Convert categorical features into dummy variables
3) Modelling
    a) Random Forest Model
    b) Gradient Boosting
    
 Since we have a mix of categorical and numerical variables, I have used ensemble methods - Random Forest and Gradient Boosting for training the data. These are generally known to perform better than other methods. On this dataset, Gradient Boosting does slightly better than Random Forest model.
 
