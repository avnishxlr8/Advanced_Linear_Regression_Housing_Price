# Advanced_Regression_Housing_Price
Predicting Boston Housing Prices using an Averaging Model
 
## Handling of data leakage
The model has not been exposed to the actual test data set before training. So the model has no prior information about the test set.      Similar strategy has been used on the test set created from the train set.

## Cross validation
 Cross validation approach has been used to fine tune the model after evaluation the rmse score.
 
## Averaging model
Here, I have created 3 models
1.Enet
2.Gradient Boosting
3.Lasso
The final prediction values are the mean values of the base model predictions.
 
