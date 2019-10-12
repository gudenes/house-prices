# House Prices

The Dataset

We are going to use the House Prices available on Kagle on the link below:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Objective:
We are going to apply a ML model to predict the sales price for the houses.

- Our Dataset consist in 1460 rows and 81 columns
- Variable target: Sales Price
- Model to predict: Linear Regression
- Distribution of data types: float64(3), int64(35), object(43)
- 5 variables have more than 20% NaN values, we will check the veracity of this information.


ONGOING TASKS

 - Dealing with NaN Values (Gustavo)
   -- Checking the columns with NaN values, in this case we indentified that was "false" NaN and in fact the missing values is the result from don't have this characteristic, we change those values to "None" and for the Numeric values I use the interpolate function to fill the missing values.
   
 - Data change (Peter)
   -- Analyse which categorical variables to turn into dummies based on crosstab and frequency
   
 - Variables correlation (Martín)
   --a function was created to check correlations. For each pair of columns highly correlated we check the correlation with the target column and the qty of nulls. After that, we decide which one we drop, in this case we Drop "GarageCars","GarageYrBlt", "TotRmsAbvGrd", "1stFlrSF". 
 
 
TO DO TASKS

  **EDA**
- TARGET
- CATEGORICAL
- NUMERCIAL

  **FEATURE ENGINEERING**
- FEATURE CREATION
- FEATURE SELECTION
- FEATURE TRANSFORMATION

  **MODEL CREATION**
 - Cross validation
 - Evaluation
 - Algorithm Paraments
 - Algorithm Selection
 

 
 
 






