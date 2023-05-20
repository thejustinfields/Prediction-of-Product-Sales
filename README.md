#Prediction of Product Sales

##What Affects the Sale of Products

####Justin Fields

###Business Problem:
What factors--such as, store size, type, age or item fat content, visibility, or price--affect the sale of products?

###Data:
The original data source is: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/

###Results:
####Fat Content to Sales in Outlet Type

![FatContentChart](https://github.com/thejustinfields/Prediction-of-Product-Sales/assets/128246388/8f219cbc-8728-479a-900a-b6aafcebf08e)

Fat content does not seem to dramatically affect sales but a secondary look at this data does reflect that Tier 3 stores have better sales of both products.

####Outlet Type Sales

![Unknown](https://github.com/thejustinfields/Prediction-of-Product-Sales/assets/128246388/ed952fce-062e-47d9-91e3-4ff790206b0d)

Supermarket Type 1 stores perform significantly better than all other store types.

##Summary
The Linear Regression Model gave the best score at: Model Training R2: 0.5615492662227797
Model Testing R2: 0.5669339858549667 and the RMSE score of: Model Training RMSE: 1139.1117264038899
Model Testing RMSE: 1093.077900767874
The Regression Tree model seems overfit on the dataset.
I would recommend using the Linear Regression model because the regression tree model is overfit
