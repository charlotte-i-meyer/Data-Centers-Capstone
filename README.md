**ReadMe for Data Centers Capstone** 

**By Charlotte Meyer**

**May 4, 2026**

This Github repository contains ipynb files and data for my Data Analytics Capstone. To run the code, you will need python, and the data that each file requires should be in the same folder as the ipynb file is in.


_Statsmodels Logistic Regression.ipynb_ conducts the logistic regression that the majority of the project is based upon. 

        Data needed: cejst_logistic_regression.csv


_KDE Plot.ipynb_ creates KDE plots for the predictors in the logistic regression.

        Data needed: cejst_logistic_regression.csv


_Atlas Dataframe.ipynb_ uses shapefile data to create a spatial join that merges the CEJST dataset with the Open Source Data Center Atlas dataset, into a dataframe that can be used for the logistic regression. It outputs cejst_logistic_regression.csv

        Data needed: all data found in _Data for "Atlas Dataframe.ipynb".zip_


_DA Capstone.ipynb_ conducts summary statistics of data centers in the US, including a map of proposed data centers in Ohio. It also includes a chi-squared test meant to determine the relationship between air quality and proposed data centers. This file was used for Early Results.

        Data needed: The CEJST dataset found in _Data for "Atlas Dataframe.ipynb".zip_, plus U.S. Data Centers - FracTracker.cs
