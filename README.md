# DATA1030 Final Project: Predicting Distress Scores of US Communities
Final project for DATA1030 Fall 2022
<br/>
## Project Overview:

This data comes from the Economic Innovation Group, they are a bipartisan public policy organization and they conduct research on geographic and economic inequality and work with policymakers to propose policy that empowers communities.

This project aims to find the best model for predicting the distress score of a community given demographic, economic, and geographic features. This is important because the health of the US economy examined in aggregate terms fails to acknowledge the deeply uneven distribution of wealth across communities and erases the hardships of the residents who call the most affected communities home. The DCI’s collection of geographic, economic, and demographic features offers a comparative view of the spatial distribution of U.S. economic well-being and is a tool through which we can evaluate for where and for whom America’s promise of opportunity applies.

All exploratory sata analysis on the target feature and relationships can be found in the [EDA Notebook](https://github.com/arianaschindler/data1030_final/blob/main/src/EDA.ipynb).

To assess the models, the root mean squared error was used to measure within how many Distress Score points our model could predict given the remaining features. The models tested included: Lasso, Ridge, ElasticNet, RandomForestRegressor, KNeighborRegressor, and SVR. The ML Pipeline and all models can be found in [Methods](https://github.com/arianaschindler/data1030_final/blob/main/src/methods.ipynb). The RandomForestRegressor was found to be the best model, with an RMSE score of 3.14 compared to the baseline RMSE score of 28.97.

All feature importance analysis following model assessment can be accessed in [Feature Importance](https://github.com/arianaschindler/data1030_final/blob/main/src/feature_importance.ipynb).

## Packages and Versions:

Python version is 3.10.5
<br/>
numpy version 1.22.4
<br/>
matplotlib version
<br/>
sklearn version
<br/>
pandas version
<br/>
xgboost version
<br/>
shap version

For further package version, please reference the [yaml file](https://github.com/arianaschindler/data1030_final/blob/main/data1030.yml).
