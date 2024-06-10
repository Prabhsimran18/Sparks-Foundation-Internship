# Sparks-Foundation-Internship


**Project 1: Predicting Student Scores with Linear Regression**

This repository contains a Python implementation of a linear regression model to predict a student's score based on the number of hours studied.

**Dataset**

The dataset used in this example is a remote CSV file available at [http://bit.ly/w-data](http://bit.ly/w-data). It consists of two columns: `Hours` and `Scores`, representing the number of hours studied and the corresponding score out of 100.

**Model**

The model is a simple linear regression model implemented using scikit-learn's `LinearRegression` class. It is trained on the dataset and used to make predictions on new input data.

**Code**

1. **Data Import and Visualization**: The dataset is imported and visualized with a scatter plot to show the correlation between `Hours` and `Scores`.
2. **Data Preparation**: The dataset is split into training and testing sets using scikit-learn's `train_test_split` function.
3. **Model Training**: The linear regression model is defined and trained on the training data.
4. **Model Evaluation**: The model is evaluated using metrics like mean squared error (MSE), mean absolute error (MAE), and R-squared (R2).
5. **Prediction**: The model predicts a score for a new input array with `Hours=9.25`.
6. **Plotting**: The original data and the predicted line are plotted using scatter and line plots.

**Hyperparameter Tuning**

Hyperparameter tuning is not performed in this example due to the small dataset size. Common techniques for hyperparameter tuning include grid search, random search, Bayesian optimization, and gradient-based optimization.
