# Advanced-Regression


Business problem :
A US Based Housing company Surprise Housing wants to enter Australian market. They want to make profit by purchasing 
houses at low prices and flip it for higher prices.  

Objective : 
To create a model to find out the best predictor variables which describes the dependent variables, so that
based on these variables we can predict the cost of houses.

Analysis from the model when trained on Linear and Lasso regression :

OverallQual, OverallCond, MSZoning_RH, PoolArea, 1stFlrSF, LotArea, LotFrontage are some of the variables which describes dependent variable in Lasso regression.
OverallQual, OverallCond, YearBuilt, MasVnrArea, 1stFlrSF, 2ndFlrSF ,GrLivArea, ExterQual_TA, SaleType_New are some of the variables which describes dependent variable in Ridge regression
Alpha for lasso is 620.99
Alpha for ridge is 4.070
Lasso score for train data and test data is 0.847 and 0.842 respectively
Ridge score for train data and test data is respectively 0.855 and 0.866 respectively	


I will use Ridge regression since the scores are slightly better when compared to Lasso. 
Ridge performs better on the test data set, as the Rsquare value in test data is higher than train data.	
 	
