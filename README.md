# House Prices

[https://www.kaggle.com/c/house-prices-advanced-regression-techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

This Kaggle competition is aimed at predicting the final price of houses with 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa.

# Dataset info

* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here
* sample_submission.csv - a benchmark submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

# Using:

* Data preprocessing
* Feature engineering
* Models training: RidgeCV, LassoCV, GradientBoostingRegressor

# Result

I get best results from blending 2 models: RidgeCV and LassoCV in a ratio of 90/10.

<img scr='additionally/leaderboard_photo.jpg'/>