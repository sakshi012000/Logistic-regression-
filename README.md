# Logistic Regression


## Introduction
Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Some of the examples of classification problems are Email spam or not spam, Online transactions Fraud or not Fraud, Tumor Malignant or Benign. Logistic regression transforms its output using the logistic sigmoid function to return a probability value.
## What is Logistic Regression?
Logistic Regression is used for a different class of problems known as classification problems. Here the aim is to predict the group to which the current object under observation belongs to. It gives you a discrete binary outcome between 0 and 1.

Comparison to linear regression
-------------------------------

If we have given data on time spent studying and exam scores. Linear regression and Logistic regression can predict different things:

  - **Linear Regression** could help us predict the student's test score on a scale of 0 - 100. Linear regression predictions are continuous (numbers in a range).

  - **Logistic Regression** could help use predict whether the student passed or failed. Logistic regression predictions are discrete (only specific values or categories are allowed). We can also view probability scores underlying the model's classifications.
  ![Image1](https://github.com/sakshi012000/Logistic-regression-/blob/master/linearvslogistic.jpeg?raw=true)

Types of logistic regression
----------------------------

Binary (eg. Tumor Malignant or Benign)
Multi-linear functions failsClass (eg. Cats, dogs or Sheep's)

We can call a Logistic Regression a Linear Regression model but the Logistic Regression uses a more complex cost function, this cost function can be defined as the ‘Sigmoid function’ or also known as the ‘logistic function’ instead of a linear function.

## What is the Sigmoid Function?
In order to map predicted values to probabilities, we use the Sigmoid function. The function maps any real value into another value between 0 and 1. In machine learning, we use sigmoid to map predictions to probabilities.
![Image2](https://github.com/sakshi012000/Logistic-regression-/blob/master/image2.png?raw=true)

## Logistic Regression Equation:
The Logistic regression equation can be obtained from the Linear Regression equation. The mathematical steps to get Logistic Regression equations are given below:

We know the equation of the straight line can be written as:
![Image3](https://github.com/sakshi012000/Logistic-regression-/blob/master/image%203.png?raw=true)
Logistic Regression in Machine Learning
In Logistic Regression y can be between 0 and 1 only, so for this let's divide the above equation by (1-y):
![Image3](https://github.com/sakshi012000/Logistic-regression-/blob/master/image%204.png?raw=true)
Logistic Regression in Machine Learning
But we need range between -[infinity] to +[infinity], then take logarithm of the equation it will become:
![Image3](https://github.com/sakshi012000/Logistic-regression-/blob/master/image%205.png?raw=true)
Logistic Regression in Machine Learning
The above equation is the final equation for Logistic Regression.
