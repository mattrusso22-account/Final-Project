# Final-Project Instructions

This project involves Machine Learning Techniques on a College Basketball dataset. The dataset contains data from the past five seasons (2015-2020). We are using college basketball team statistics to predict which team attributes were most influential to the number of wins a team had. Select an appropriate feature selection algorithm/method and use it to identify patterns in this dataset. We are looking to identify the top seven features. It is important to remember this is a regression type problem rather than classification. 

Step 1 - import any library needed to run the neccessary steps

Step 2 - load the data into a dataframe (link to the dataset in phase 1 of project). Input features and labels (X and y). Keep only numerical features since we are going to run f_regression for our feature selection method.

Step 3 - View the dataframe and also find the a summary of statistics pertaining to the DataFrame columns (use data.describe())

Step 4 - The label encoder is now going to be applied to the data.

Step 5 - Delete categorical columns (goes back to step 2 as we are only going to run f_regression on numerical columns)

Step 6 - Use attribute to get array of data: has the number of elements in our data. X will have the 17 numerical columns while y will be isolated to just "W" since we are trying to accurately predict the number of wins the teams had. 

Step 7 - Scale and fit the data

Step 8 - Use feature selection (SelectKBest to find 7 most relevant futures). Display the features after running this line of code.

Step 9 - Create two dataframes: one with the data that only contains the top 7 features and another that just has the column "W" data.

Step 10 - Create a training and test data set (80% training, 20% test) and find a suitable random state value

Step 11 - Apply Support Vector Regression (SVR) with kernel set to 'linear'. Find suitable values for the parameters within the SVR technique. Run this line of code and display the accuracy of the model.

Step 12 - Time to use the model to make predictions: display an array of the predictions after running code.

Step 13 - Optional/Not required: plot the predictions. 

Step 14 - Print Mean Absolute Error (MAE) as this is a valuable stastical measurement. Helps us draw inisghts and conclusions on how effective our model is.

Step 15 - Create a dataframe of the actual number of wins the teams had vs our predictions. Make a third a column that shows the difference (how close we are). Show the top 20 most accurate predictions.

Step 16 - Create another dataframe of the actual number of wins the teams had vs our predictions. Make a third a column that shows the difference (how close we are). This time show the top 20 least accurate predictions.
