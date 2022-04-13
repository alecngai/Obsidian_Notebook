## Supervised Learning 

**Regression**: The output variable to be predicted is continuous in nature, e.g. scores of a studen, diamond prices, etc. 

**Classification**: The output variable to be predicted is categorical in nature, e.g. classifying incoming emails as spam or ham, Yes or No, True or False, 0 or 1. 

## Unspervised Learning 
**Clustering**: No predefined labesl are assigned to groups/clusters formed, e.g. customer segmentation. Linear Regression is a supeervised Learning algorithm in the machine learning that supports finding the linear correlation among variables. The result or output of the regression problem is a real or continous value. 

## Simple Linear Regression 

Linear regression shows the relation between independent (Predictor) variable i.e. X-axis and the dependent (output) variable i.e. Y-axis. 

Linear regression is called **simple linear regression** when there is only a single input variable and single output. 

![](https://editor.analyticsvidhya.com/uploads/945791.jpg)

The above graph presents the linear relation between the output(Y) variables and predictor(X) variables. The blue line is referred to as the best fit straight line. Based on the given data points, we attempt to plot aline that fits the points best. This line is created using a training set, and can be used to predict future values based on a test set of predictors. 

To calculate the best fit line linear regression uses astraditional slope-intercerpt form which is **Yi = B0 + B1Xi** 

![](https://editor.analyticsvidhya.com/uploads/375512.jpg)

Linear regression finds the best values for B0 and B1, by finding the values with the lowest error between predicted and actual values. 

## Random Error (Residuals)
In regression, the difference between the observed value of the depedent variable and predicted variable is called **residuals**. 

Best fit line is obtained by minimizing the **Residual Sum of Squares (RSS)** 

## Cost Function for Linear Regression

In Linear Regression, **Mean Squared Error (MSE)** is the average of squared error that occureed between the Ypredicted and Yi. 

**MSE** is calculated using a simple linear equation 

![](https://editor.analyticsvidhya.com/uploads/650733.jpg)

Using MSE function. the algorithm updates the values of B0 and B1, such taht MSE values settle at the minima.  These paramaeters can be determined using the gradient descent method such that the value for the cost function is minium. 


## Gradient Descent for Linear Regression 

Gradient descent is an optimization algorithm that optimizes the cost function to reach the optimal minimal solution. This is an iteratively function changing the values of B0, and B1 until a minimum MSE is reached. 



