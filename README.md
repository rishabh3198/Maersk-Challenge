# Maersk-Challenge
In this project, we are trying to forecast Sourcing costs based on the ProductType, Manufacturer, Area_Code, Sourcing_Channel, Product_Size, Product_Type and Month_of_Sourcing as dependent variables.

This is DS/ML Challenge from MAERSK Group called "Sourcing Costs Forecast" where the task is to predict Sourcing cost for Jun-21 and Training set was from Jul-20 to May-21. We were suppose to iterate over Different ML models and come up closest possible to testing dataset using training dataset and feature engineering.

For this particular problem my approach was as follows:

* Get Some EDA (Exploratory Data Analysis) on the data set EDA.ipynb will help in finding that.
* Do some feature engineering after getting better understanding from EDA (Exploratory Data Analysis).
* Train, Test and Validation split (Train- 10 months, Test- 1 month, Validation- 1 month).
* Do some modelling over the Dataset.
* Select one best model on the basis of RMSE score and R-squared Value.
* Calculate Feature importance and check whether the engineered feature were important or not.
