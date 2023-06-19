# Cancer Prediction

#### This code is a Python script that performs machine learning (ML) tasks on a dataset called "Cancer.csv". The script uses several Python libraries such as NumPy, Pandas, Matplotlib, and Scikit-Learn (sklearn) to perform different tasks.

## Here's what the code  does step-by-step:

1)   imports the necessary libraries for the ML tasks.
2)   reads the "Cancer.csv" dataset into a pandas data frame (df).
3)   displays the first 5 rows of the dataset using the "head()" function.
4)   checks for nulls and data types in the dataset using the "info()" function.
5)   drops an unnamed column from the dataset as it doesn't provide any value using the "drop()" function.
6)   checks for duplicates in the dataset using the "duplicated()" and "sum()" functions.
7)   checks correlation between the features using the "corr()" function.
8)   removes outliers from the dataset using the Z-score method.
9)   splits the data into labels and features.
10)   normalizes the data using the Z-score method.
11)   changes string values to binary so that the classifiers can understand them.
12)   splits the data into training and testing sets using the "train_test_split()" function.
13)   trains several ML models on the training data and predicts the labels for the testing data using these models. The models used in this code are Linear
14)   Regression, Ridge, Grid Search with Decision Tree Regressor, Decision Tree, and Random Forest.
15)   calculates the r2_score and mean_squared_error for each of the models on the testing data.
16)   prints the r2_score and mean_squared_error for each of the models.
17)   Finally,  the code prints the best model based on the highest r2_score and lowest mean_squared_error.
### The best model in this code is the Random Forest model with an r2_score of 87% and a mean_squared_error of 3%.
