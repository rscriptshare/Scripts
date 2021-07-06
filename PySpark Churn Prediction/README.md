# PySpark Project: Sparkify
This is a Churn Prediction Project within Udacity Data Scientist Nanodegree. 
<br>In this project, I will show how to use Pyspark for EDA, aggregation and feature engineering.
<br> It will be involving some visualizations by seaborn during the process.
<br> At the end I will be using Random Forest Classification and Logistic Regression model for prediction.
<br> Beside calculating the accuracy, I'll be using Precision and Recall score as the evaluation metrics as it's an imbalanced dataset. 
<br> **Definition of Precision and Recall**
<br> Precision: for those predicted at True, how many of them are actually True
<br> Recall: for those which are actually True, how many of them can be correctly predicted

<br> Although the goal of the project is to predict whether a customer will churn or not, I would place more weight on churn than non-churn as it's more important.
<br> The best accuracy = 85% but with a poor recall score on predicting churn. 
<br> The best recall score on predicting churn = 82% and with an accuracy = 65% which is not bad as it's vital to predict churn than non-churn.



Main **libraries** were used for this project.

`pandas version 0.23.3`
<br> `matplotlib version 2.1.0`
<br> `sklearn version 0.19.0`
<br> `numpy version 1.12.1`
<br> `pyspark version 2.4.3`
<br> `seaborn version 0.8.1`
<br> `numpy version 1.12.1`
<br> `sklearn version 0.19.1`


## Data understanding and preparation
There is only 1 datasets in json format: mini_sparkify_event_data
<br> Its size is ~128MB and has 286,500 rows and 18 columns which comprises of 12 columns in string-type, 5 in long-type and 1 in double-type.


## Files Details
It records the Name, location and gender of the user. Also the artist and song that each user listens to and the actions on the app.



## Acknowledgement 
A big thanks to Udacity for the knowledge provided in Data Scientist Nanodegree.
