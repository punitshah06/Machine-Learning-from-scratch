# Machine-Learning-from-scratch
This repository will serve as a way to collect my notes for machine learning.

[markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/)

### Topics
1. [Steps of a Machine Learning Project](https://www.analyticsvidhya.com/blog/2021/04/steps-to-complete-a-machine-learning-project/)
2. [Machine Learning Challenges](https://www.geeksforgeeks.org/7-major-challenges-faced-by-machine-learning-professionals/)
3. [Data Cleaning](https://towardsdatascience.com/what-is-data-cleaning-how-to-process-data-for-analytics-and-machine-learning-modeling-c2afcf4fbf45)
4. [Feature Scaling](https://www.geeksforgeeks.org/ml-feature-scaling-part-1/)
5. [Label Encoding](https://www.geeksforgeeks.org/ml-label-encoding-of-datasets-in-python/?ref=lbp)
6. [One Hot Encoding](https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/?ref=lbp)
7. [How to choose ML Model](https://towardsdatascience.com/considerations-when-choosing-a-machine-learning-model-aa31f52c27f3)
8. [Supervised learning Models](https://scikit-learn.org/stable/supervised_learning.html)
9. [Unsupervised Machine Learning Models](https://scikit-learn.org/stable/unsupervised_learning.html)
10. [Model Selection and Evaluation](https://scikit-learn.org/stable/model_selection.html)
11. [Model Evaluation Metrics](https://www.analyticsvidhya.com/blog/2019/08/11-important-model-evaluation-error-metrics/)

### Assumptions of Every Machine Learning Algorithm
<details>
  <summary>Linear Regression </summary>
  
### Regression Assumptions
For the simple and multiple regression model to hold there are some assumptions we need to make:
1. The chosen sample is representative of the population.
2. There is a linear relationship between the independent variable(s) and the dependent variable.
3. All the variables are normally distributed; to check, plot a histogram of the residuals.
4. There are no outliers, (if there are outliers they need to be removed); to check use a test for detecting outliers.
5. The independent variables are all linearly independent (no variable dependents of the other variables); to check plot the independent values against each other and look for a correlation.
6. For multiple regression there should be at least five times as many pairs of data than dependent variables.
#### Linear Assumptions
1. The mean of the distribution of errors is 0.
2. The variance of errors is constant across all levels of the independent variable, this is called homoscedasticity; to check plot the residuals versus the predicted values of y.
3. The distribution of errors is normal; to check this draw a histogram of the errors.
4. All the errors are independent; to check plot the residuals versus the time periods.

</details>

[Ridge Lasso Elastic Net](https://medium.com/@creatrohit9/lasso-ridge-elastic-net-regression-a-complete-understanding-2021-b335d9e8ca3)

<details>
  <summary>Logistic Regression </summary>
  
### Logistic Regression Assumptions
For the simple and multiple regression model to hold there are some assumptions we need to make:
1. The Response Variable is Binary
2. The Observations are Independent
3. There is No Multicollinearity Among Explanatory Variables
4. There are No Extreme Outliers
5. The Sample Size is Sufficiently Large
6. There is a Linear Relationship Between Explanatory Variables and the Logit of the Response Variable
  
#### Assumptions of Logistic Regression vs. Linear Regression
1. A linear relationship between the explanatory variable(s) and the response variable.
2. The residuals of the model to be normally distributed.
3. The residuals to have constant variance, also known as homoscedasticity.

</details>
