# House-Price-Prediction

This data set is an active [Kaggle Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview) in which the sale price of house has to be predicted by using all the features given.


## Dataset Description
	price_train.csv - the training set
	price_test.csv - the test set
	data_description.txt - full description of each column
	sample_submission.csv 
The data set contains two files test and train\
Train file is of the shape 1460 X 81\
Test file is of the shape 1459 X 80 ( Does not contain Sale price column which needs to be predicted).


## Workflow 

1) Data Visualisation : plotted various graphs and charts using Seaborn and Matplotlib to get an overview of the information in the dataset 
2) Data pre-processing : preprocessing involves handling the numerical and categorical data.
	* Splitting the data into numerical and categorical features
	* some of the missing values are not meant to be missing values but rather a 'None' value for categorical features and '0' value for 					numerical features.Filling those columns with their respective values
	* filling categorical na values using mode
	* filling numerical na values using median
	* converting (object) dtypes features into (int32) dtypes using labelencoder
	* Merging the numerical and categorical features
				
3) Data Modelling : training regression models by using linear regression , decision tree regressor, random forest regressor, xgb regressor and predicting the sale price on the test dataset provided
4) The evaluation of the dataset is based on RMSE ( root mean squared error) 


## Results 

|  ML Algorithims   |  r2 score |
| ----------------- | --------- |
| Linear Regression |  0.83     |
| Random Forests    |  0.90 	| 
| Decision Trees    |  0.81	|
|    XGB Boost      |  0.92	|
