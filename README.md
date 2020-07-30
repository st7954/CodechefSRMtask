 #### Steps-:
 Dataset-:<br />
-I have first loaded all the necessary libraries. <br />
-I have then loaded the dataset using the pandas module.<br />
-I have then checked and imputed all the missing values.<br />
-Dealt with categorical variables and drop the 'v.id' column for generalization.<br />
Using KNEIGHBORS REGRESSORS-:<br />
-I have created the train and test dataset and then printed it.<br />
-I have then preprocessed (or scaled) the features.<br />
-Created a list to look at the error rate for different K values.<br />
-Plotted the elbow curve for better understanding.<br />
RMSE Values-:<br />
-I have minimized the value of root mean squared to as low as possible on the given dataset , which it gives on K=7.<br />
-The rmse value has NOT been scaled in any form and is just the original value which the function gave.<br />
-All rmse values has been stored and rmse values along the way have been printed no values are Normalized.<br />
-I have also printed the R_2 value.<br />
Predictions on the test dataset-:<br />
-I have created a test dataframe.<br />
-I have then dropped the 'v.id' from the test dataframe.<br />
-Predicted the buying prices of cars and stored in 'results'.<br />
-Written the 'answers' file in the same format as of the sample file.<br />
#### About KNN Algorithm-:
 KNN algorithm can be used for both classification and regression problems. The KNN algorithm uses ‘feature similarity’ to predict the values of any new data points.<br />
 This means that the new point is assigned a value based on how closely it resembles the points in the training set. Here I have used it for regression problem.
