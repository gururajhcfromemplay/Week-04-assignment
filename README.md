# Week-04-assignment
House Price Prediction

Goal:
It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 

Metric:
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. (Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.)

Steps involved in the project:

1. Loading the dataset

2. Checking for Null values and Value distribution

3. Fixing the Null values using the information shared in data description

4. Fixing the outliers using Outliers using IQR

5. Scaling the Features to a common scale using StandardScaler

6. Applying PCA for dimensionality reduction

7. Perform Grid search to identify the best performing models and hyper parameters

8. Apply cross validation to train the model on the entire dataset 

9. Using the trained model predict the SalePrice for test dateset

10. Write the results to sample_submission.csv


