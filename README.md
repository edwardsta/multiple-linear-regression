# Linear Regression with Multiple Variables
Predict the market value of a house based on the size (sqr footage), and number of bedrooms.

## Overview
We will implement linear regression with multiple variables to predict the prices of houses. Suppose you are selling your house and you want to know what a good market price would be. One way to do this is to ﬁrst collect information on recent houses sold and make a model of housing prices. The ﬁle ex1data2.txt contains a training set of housing prices in Portland, Oregon. The ﬁrst column is the size of the house (in square feet), the second column is the number of bedrooms, and the third column is the price of the house. The ex1_multi.m script will determine the market value.

## Feature Normalization
The ex1_multi.m script will start by loading and displaying some values from this dataset. By looking at the values, note that house sizes are about 1000 times the number of bedrooms. When features diﬀer by orders of magnitude, ﬁrst performing feature scaling can make gradient descent converge much more quickly. This is what featureNormalize.m performs.

## Gradient Descent
The code in computeCostMulti.m and gradientDescentMulti.m is used to implement the cost function and gradient descent for linear regression with multiple variables.
