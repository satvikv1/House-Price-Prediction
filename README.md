# House-Price-Prediction
Machine Learning
This data set is an active Kaggle Competition in which the sale price of house has to be predicted by using all the features given.

## Dataset Description
	•	train.csv - the training set
	•	test.csv - the test set
	•	data_description.txt - full description of each column,
	•	sample_submission.csv 
The data set contains two files test and train
Train file is of the shape 80 X 1460 excluding the ID column
Test file is of the shape 79 X 1459 ( Does not contain Sale price column which needs to be predicted)


## Link to the competition
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview


## Workflow 

1) Data Visualisation : plotted various graphs and charts using Seaborn and Matplotlib to get an overview of the information in the dataset 
2) Data pre-processing : preprocessing includes handling numerical and categorical variables with the help of label encoding , filling na values and removing outliers 
3) Data Modelling : training regression models by using linear regression , decision tree and random forest regressors and predicting the sale price on the test dataset provided
4) The evaluation of the dataset is based on RMSE ( root mean squared error) 


Results 	     Accuracy

Linear Regression : 81
Random Forests    : 90
Decision Tree     : 83
XG Boost          : 91

## Kaggle leaderboard positions
1) 2019
2) 1980
3) 1507