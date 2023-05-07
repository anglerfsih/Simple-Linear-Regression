# Simple-Linear-Regression

Data set: https://www.kaggle.com/datasets/karthickveerakumar/salary-data-simple-linear-regression?resource=download
The code is runned in Google Colab
Packages used:
1. pandas
2. matplotlib
3. plotly
4. Scikit-learn


Simple Linear Regression:
Simple linear regression is a statistical technique used to study the relationship between two variables. It is called "simple" because it involves only two variables: the dependent variable and the independent variable.

In this technique, the dependent variable is modeled as a linear function of the independent variable, with the objective of finding the line of best fit that can be used to predict the value of the dependent variable for a given value of the independent variable. 

The line of best fit is determined by minimizing the sum of squared errors between the observed values of the dependent variable and the predicted values. Simple linear regression is a widely used technique in various fields such as economics, finance, and social sciences.


The equation for simple linear regression is:

y = b0 + b1*x

where:
y is the dependent variable (also called the response variable)

x is the independent variable (also called the predictor variable)

b0 is the y-intercept (also called the constant term), which represents the value of y when x is equal to 0

b1 is the slope coefficient, which represents the change in y for a unit increase in x

The equation for simple linear regression shows how the dependent variable y varies with respect to the independent variable x. 

The slope coefficient b1 indicates the direction and magnitude of the relationship between x and y.

A positive value of b1 indicates a positive relationship between x and y, which means that as x increases, y also increases. 

A negative value of b1 indicates a negative relationship between x and y, which means that as x increases, y decreases. 

The y-intercept b0 is the value of y when x is equal to 0, which is often not a meaningful value in the context of the problem, but is included to provide a starting point for the line of best fit.

Result:
By comparing the actual and predicted numbers, we can see that the regression is positive linear relation and has a 49 percent inaccuracy and can improve by adding more data into the model to reduce the inaccurancy.
