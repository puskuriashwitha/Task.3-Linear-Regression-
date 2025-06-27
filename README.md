# Task.3-Linear-Regression.
About this Task:
Hey! In this task, I worked on the StudentsPerformance.csv dataset to build a simple linear regression model. The main idea was to predict a student’s math score based on their reading and writing scores.

 What I did in this task:
1 Imported the dataset using Pandas and had a quick look at the shape, columns, and first few rows.

2 Checked for missing values — luckily, this dataset didn’t have any.

3 Converted categorical columns to numbers using Label Encoding for safety (though we didn’t use them in regression this time).

4 Selected numeric columns (math score, reading score, writing score) for regression.

5 Split the data into train and test sets (80% training, 20% testing) using train_test_split().

6 Fitted a Linear Regression model using sklearn.linear_model.LinearRegression().

7 Predicted math scores on the test data.

8 Evaluated model performance by calculating:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

9 Plotted a scatter plot of actual vs predicted math scores and added a reference line to visualize how close our predictions were.
