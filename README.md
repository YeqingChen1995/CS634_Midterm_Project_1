# House Prices Prediction Project
This is a python script used to solve the house price prediction problem provided by [https://www.kaggle.com/c/house-prices-advanced-regression-techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Required Packages
- numpy
- panadas
- seaborn
- scipy
- sklearn

## Files Explanation
- train.csv ：raw training data set
- test.csv ：raw test data set
- data_description.txt ：features description file
- Project1.ipynb ：main program
- sample_submission1.csv ：ridge regression result
- sample_submission2.csv ：lasso regression result
- sample_submission3.csv ：elastic network result

## Important Variables Explanation
- train : raw training set
- test : raw test set
- SalePrice : SalePrice 
- full : new data set combined with training set and test set
- skew_features : skewness values of all numeric features
- final_train : training set after preprocessing
- final_test : test set after preprocessing
- alphas_alt : Alternative parameter for ridge regression model
- alphas2 : Alternative parameter for lasso regression model
- e_alphas : Alternative parameter for elastic network model
- e_l1ratio : Alternative parameter for elastic network model
- result1 : prediction result calculated by ridge regression model
- result2 : prediction result calculated by lasso regression model
- result3 : prediction result calculated by elastic network model

## Partial Results Display

|Id   |SalePrice          |
|-----|-------------------|
|1461 |115230.71681995243 |
|1462 |153120.93123664297 |
|1463 |153120.93123664297 |
|1464 |153120.93123664297 |
|1465 |153120.93123664297 |
|1466 |153120.93123664297 |
|1467 |179566.05608812527 |
|1468 |160857.51704125153 |
|1469 |196507.14119826752 |
|1470 |119106.9144361396  |
|1471 |189141.67956958793 |
|1472 |97279.81891960099  |
|1473 |94360.46986528934  |
|1474 |143764.91615695073 |
|1475 |109120.15497533568 |
|1476 |352984.0614650302  |
|1477 |246213.34437531425 |
|1478 |301600.4487908311  |
|1479 |305541.21533308405 |
