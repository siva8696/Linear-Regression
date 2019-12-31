# Linear-Regression

Linear regression is an regression technique where the target values will be a real value. The main objective is we have to find the plan that best fits our data. 

![Linear Regression](https://miro.medium.com/max/1200/1*87aMm1RRoaxS4Sy8Q-XMDg.png)

In statistics, linear regression is a linear approach to modelling the relationship between a dependent variable(y) and one or more independent variables(X). In linear regression, the relationships are modeled using linear predictor functions whose unknown model parameters are estimated from the data. Linear Regression is one of the most popular algorithms in Machine Learning. That’s due to its relative simplicity and well known properties.

<h3>Simple Linear Regression</h3>

Linear Regression is called simple if you are only working with one independent variable.

Formula: f(x)=mx+b

<h3>Cost Function</h3>

We can measure the accuracy of our linear regression algorithm using the mean squared error (mse) cost function. MSE measures the average squared distance between the predicted output and the actual output (label).

![Mean Sqaured Error](https://miro.medium.com/max/643/1*1g7XNjpxE92xo-jKxS4uow.png)

So we have to find the plane that reduces our mean sqaured error. Eventually we have to find the optimal "W" (Weight vector) and "b" (Intercept term) to reduce the mean  squared error. For achieving this optiaml values we will use stochastic gradient descent algorithm. The code for Implementation of SGD is available in python notebook. Please go through it.

<h3>Credits:</h3>

https://medium.com/@gilberttanner/linear-regression-explained-8e45f234dc55
