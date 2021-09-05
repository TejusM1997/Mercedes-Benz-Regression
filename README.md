# Mercedes-Benz-Regression 
Regression problem with dimensionality reduction

### Problem Statement
Mercedes-Benz in order to ensure the safety,reliability and performance before the car hits the road subjects its manufactured cars to numerous safety tests for which the company has designed a robust testing system, however their engineers are facing difficulty optimizing the testing speed for so many feature combinations which highlightened the need for an algorithmic approach. 

There are in total 366 features therefore the company explicitly stated in its kaggle competition requirements that the problem of 'Curse of Dimensionality' be addressed

### Methodology

Here I have taken regression algorithms like:

1) Multiple Linear Regression
2) RandomForest Regressor
3) Support Vector Regressor
4) Gradient Boosting Regressor

Specifically I only chose these four algorithms because each of them belong to a paricular class of algorithms

Multiple Linear regression is linear model that which creates a line of best fit to find the residuals, RandomForest is an ensemble bagging technique which creates multiple parallel decision trees to find the residual values and chooses the model which has the least amount of residuals, whereas Gradient Boosting regressor builds sequntial decision trees to calculate residuals which are termed as pseudo residuals. 
Finally Support Vector Regressor uses hyperplane & decision boundaries distant to it, for ensuring that data points lie within that boundary line so as to minimize error 

Dimensionality Techniques used are

1) Principal Components Analysis (PCA)
2) Truncated Singular Value Decomposition 
3) Kernel PCA 
