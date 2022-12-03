# House_Price_Prediction
House Price Prediction using RandomForest and Linear Regression

Here, we are provided with a dataset with house features and its price. We are using 2 models to predict the price and confirm the best model

## Why Random Forest

1. Random forest is an ensemble of decision trees. 
2. This is to say that many trees, constructed in a certain “random” way form a Random Forest.
3. Each tree is created from a different sample of rows and at each node, a different sample of features is selected for splitting. 
4. Each of the trees makes its own individual prediction. 
5. These predictions are then averaged to produce a single result, hence improving its accuracy and reducing overfitting
Here, practically we can see that the MSE(Mean Square Error) for Random forest is low compared to Linear Regression.

## Steps Followed:
1. Load and View the dataset
2. Perform EDA(statistics, missing values, duplicates, covariance and correlation, relationship between variables)
3. Choose the regression model (Random Forest and Linear Regression)
4. Build a pipeline for automating the flow of data 
5. Save the model using pickle

## Streamlit
1. I have used streamlite to deploy the model.
2. Follow this tutorial to do the same in colab- https://faun.dev/c/stories/neji_14/how-to-create-and-launch-a-streamlit-app-directly-from-google-colab/

