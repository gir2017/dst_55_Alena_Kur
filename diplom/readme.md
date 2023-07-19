# Project: Property price prediction
##### Done by Alena Kurylchyk


## Project objective ##
Need to built the model to predict property price by its features.

## Project features ##
1. The data have a lot of outliers, mistakes, input errors, slang abbreviations


## What has been done ##
0. Data cleaning
   
1. Data enrichment.
+ Parsing of relevant data using uszipcode library.
+ Finding coordinates of the city center using geopy.
+ Distance calculation using geopy.

2. EDA
+ Quick dataset overview using profile report and dtale.
+ Handling of duplicates.
+ Handling of missing values.
+ Visualisation of features distribution and relationship with a target value.
+ Outlier analysis.
+ Dividing features into categories.
+ Analysis of relation between features categories and with a target value.

3. Feature Engineering

4. ML
+ Selecting the encoder and encoding of all binary and categorical features.
+ Outlier removal using different models: IsolationForest, EllipticEnvelope, LocalOutlierFactor
+ Feature selection using different methods: RFE, SelectFromModel, FeatureImportance
+ Testing of linear models. Baseline.
+ Testing of 5 different advanced models: Random Forest, CatBoost, Gradient Boosting, XGBoost, LightGBM. Bagging and stacking have also been tested.

## Results ##
+ The best result was shown by RandomForestRegression model.


## What could be improved ##
+ Perfoming of feature engineering.
+ Trying some NLP methods to extract useful data.
+ Better hyperparameters tuning.
+ More deep analysis of the data and the results to understand what impacts MAPE and R2 score the most.
+ The data could be divided into property for rent and for sale and separate models could be trained.
+ More precise outlier removal, trying different parameters;

