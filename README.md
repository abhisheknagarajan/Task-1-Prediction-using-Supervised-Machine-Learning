# Task-1-Prediction-using-Supervised-Machine-Learning

Predict the percentage of an student based on the number of study hours


# Problem Statement

Predict the percentage of an student based on the no. of study hours


# Feature Description
Hours: Number of hours student has studied in a day.(Independent Variable)

Scores: Percentage of marks obtained by the student corresponding to the number of study hours.(Target Variable)


# Implementation

Understanding the data

Building a model

Evaluationg the model

Predicting the score if a student studies for 9.25 hrs/ day?


# General Summary

The dataset has records of 25 students and their scores correspondong to their study hours.

Hours is of type 'Float' and Scores of type 'Integer'. Hence the datatypes assigned are correct as per the Analysis.

Since the maximum marks is 95, the student who has studied for the highest number of hours has not scored the Highest.

The student who has studied for the least number of hours is the one who scored the Least.

The student with the highest marks of 95 has put in 8.9 hours of study time which is 0.3 hours less than the student who has spent maximum of 9.2 hours.

Both the variables are normally distributed and their skew values are closer to 0.

heatmap shows that Scores and Hours are strongly related with a correlation of 0.98 hence indicating linear relationship between Dependent and Independent.


# Results

The r-squared value is 0.95.

This means that the the target variable is able explain 95% of the variance due to the independent variable.


Train/Test	
       MAPE  RMSE  MAE
      
Train	 0.11	 5.26	 4.77

Test	 0.16	 5.86  5.63


The predicted score if a student studies 9.25 hours in a day is: 93.43


