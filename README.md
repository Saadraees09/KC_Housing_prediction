**Overview**

This project will utilize multiple regression analysis to predict housing prices using data of homes sold in King County, WA, during 2014 and 2015. This dataset will be explored for completeness and integrity, relationships between attributes and target variable, and for feature engineering. Several models will be built and trained by SciKit python library to generate predictions on unseen data. A final model will be chosen based on its Root Mean Squared Error (RMSE) value. The data and project scope was provide by Flatiron School for Data Science Immersive program phase 2 final project.

![alt text](https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.nwrealtor.com%2Fwp-content%2Fuploads%2F2020%2F06%2FMy-Post-2020-06-19T111622.407.png&imgrefurl=https%3A%2F%2Fwww.nwrealtor.com%2F2020%2F06%2F19%2Fking-county-now-in-phase-2-of-covid-19-re-opening%2F&tbnid=m4H7IYUHZzyDmM&vet=10CIQBEDMoiQJqFwoTCKCXoK7Vwe4CFQAAAAAdAAAAABAD..i&docid=4moSuOnN8LLorM&w=1200&h=628&q=king%20county&ved=0CIQBEDMoiQJqFwoTCKCXoK7Vwe4CFQAAAAAdAAAAABAD)


**Repository Structure**:
This repository consists of:

King County Housing Price Predictions.pynb for final notebook

Predictions Notebook.pynb for holdout predictions

housing_preds_saad_raees.csv for predicted prices

A data folder for all the data required for this project

and a README.md


**Business Problem**


A Seattle real estate company seeks to increase porfolio in King County Seattle and wants to accurately predict the sales price of a property. Having an accurate sales prediction will aid in strategizing the investment options to maximize their profit. A multiple linaer regression model will be built base on provided property data for this task.

During the exploratory phase following questions will also be focused on:

What location in the county has the highest property value?

What aspects of the property brings value?

Do renovations have effect on property value?

**Approach**

Check for data completeness and integrity

Perform EDA with statistical analysis to determine statistically significant features

Visualize statistically significant features

Engineer new features based on stastistical findings

Model Linear Regression models and evaluate each model for final implementation

Implement feature engineering and final model to the data set.

**Modeling**

Using Scikit-learn package 4 linear regression models were created.


Model 1 : Linear Regression

Model 2 : Linear Regression with Kbest feature selection

Model 3 : Linear Regression with Recursive Feature Elminiation and Cross Valdiation

Model 4 : Linear Regression with Kbest feature selection with Ridge regression

It was determined that the simple Linear Regression with model perfromed the best and was utilized for the final implementation.

**Summary**

Basic linear Regression with 51 features had the lowest Root Mean Square Error (RMSE) error value. These means that Model number 1 was better than the other models at prediction home prices on useen data. From the data set analysis and model coefficients, the features the have the highest impact on home prices are square foot living, number of bathrooms, number of bedrooms, grade, and condition.

**Author**: SAAD RAEES
