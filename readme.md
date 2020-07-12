# Data Science and Machine Learning

This is a repository to save my data science and machine learning studies

# Model Evaluation

Accuracy - the number of correct predictions made by the model divided by the total number of predictions. 80/100 = .8.  Accuracy is useful when target classes are well balanced.

Recall - Ability of a model to find all the relevant cases within a dataset
TruePositives / (TruePositives + FalseNegatives)

Precision - Ability of a classification model to identify only the relevant data points.   
TruePositives / (TruePositives + FalsePositives)

F1 score - a combination of Recall and Precision

# Regression

Regression is a task when a model attempts to predict continuous values.  For example, attempting to predict the price of a house given its features is a regression task

Attempting to predict the country a house is in given its features would be a classification task

In statistics, regression toward (or to) the mean is the phenomenon that arises if a random variable is extreme on its first or first few measurements but closer to the mean or average on further measurements

Least squares method, which is fitted by minimizing the sum of squares of the residuals

## Regression Evaluation Metrics
Mean absolute error is the mean of the absolute value of the errors  
Mean squared error is the mean of the squared errors
Root Mean Squared Error is the square root of the mean of the squared errors

# Logistic Regression

## Confusion Matrix
True positive - Predicted true, actual is true  
True negative - Predicted false, actual is false  
False Positive - Predicted true, actual is false - type 1 error
False negative - Predcted false, actual is true - type 2 error  

Accuracy - How often is it correct? from 0-1  
Misclassification rate - How often is the model wrong
