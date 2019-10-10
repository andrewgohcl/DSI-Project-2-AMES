# Project 2 - Ames Housing Data and Kaggle Challenge

1. Defining the Data Science problem here
This project's data science problem is to build a model that will predict the price of a house at sale in Ames, Iowa before a sale.
The final model selected here is a MLR with 3 features capturing: Area, Age and Quality datapoints.
Included in this notebook includes models built on:

- Single Linear Regression
- Lasso Regression
- Ridge Regression
- Elastic Net
Despite some of the other models offering better predictive powers, the MLR was selected because of it is easy to simple to understand and to explain to other stakeholders such as realtors or house owners that might have an interest in this problem. It is not easy to explain a model with 30 predictors.

The model created here is created using a regression model based on the Ames Housing Dataset.

The data dictionary for the dataset could be found here.

The limitation of the models created here include:

- will need to modify the age calculation used (2010 - year of remod)
- unable to accurately predict large houses
- houses with unique characteristics such as missing sewarage, no central aircon etc as there are not 
enough samples to predict accurartely
- like many models, this is not an evergreen model.. 

Steps in the notebook

2. Gathering the data
Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/cf68f4a276f44b59a3c6c843dbf9ed1e)) to **join** the competition (otherwise you will not be able to make submissions!)
Review the material on the [DSI-US-6 Regression Challenge](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge)
Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).


3. Exploring and cleaning the data

  - Filling of null data
  - Dropping of rows with lots of missing data

4. Exploratory Data Plots

  - Scatterplot
  - Histogram
  - Boxplot
  - dropping of big outliers
5. Baseline model creation

  - Plotting of heatmap 
  - Construction of SLR
6. Our simple 3 variable Multi Linear Regressor

  - Filtering of more variables
  - Construction of MLR
7. Embedded method of feature selection

  - Lasso Regression
  - Elastic Net
  - Ridge Regression
  - Feature selection based on Ridge
  - Ridge Regression on remaining features

8. Conclusion

  - Choice of model

9. Kaggle

  - Prediction
  - Submission        


## Project 2 - Ames Housing Data and Kaggle Challenge-v2(lasso & ridge).ipynb

Changelog from v1 in bold
Using heatmap to do advanced filtering first **NEW**

  - Using heatmap to do advanced filtering first
  - drop super correlated features

7. Embedded method of feature selection **Different results**

  - Lasso Regression
  - Ridge Regression
  - Feature selection
8. Conclusion

  - Choice of model      