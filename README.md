# Concept-Note
I have used Sequential from tensorflow and dense from tensorflow . A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.

### DATA-: 
1-Loaded in the dataset using pandas module.<br />
2-X and y columns were separated respectively.<br />
3-Train test split was used to split the dataset.<br />

### Data MODEL-:
1-Sequential model was used.<br />
2-Model had adam optimizer with the loss set to mse and the metrics were mse.<br />
3-Model has 2 layers with 32 and 64 filters respectively.<br />
4-All activation functions were relu.<br />
5-The output layer as an activation function as linear.<br />

### RMSE Values-:
1-I have minimized the value of root mean squared to as low as possible on the given dataset.<br />
2-The rmse value have been scaled using minmaxscalar with a feature range from 0 to a 100.<br />
3-History has been stored and rmse values along the way have been printed no values.<br />

### PREDICTIONS-:
Predictions were stored in a csv file in the same format as given in the sample.csv file in the answers.csv file.<br />
 


