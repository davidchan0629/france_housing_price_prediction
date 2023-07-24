# France Housing Price Prediction

## Overview
We will use the existing france housing data to create a model to predict the france housing price

Please go to the following tableau map or tableau workbook file in the repository to have an overview of the price:
https://public.tableau.com/app/profile/david7663/viz/FranceHousingPriceMap/HousingPriceMap

## Methodology
XGBoost regression model is adopted as a base model for training.
For the specific parameters, GridSearchCV is used to find out the best result among the possible choices of parameters

The result is fantastic as 99% of the housing price can be predicted and explained by the feature columns in the data.

<br>For further details, please take a look to the jupyter notebook <strong>(regression_model_training.ipynb)</strong> in the repository.

