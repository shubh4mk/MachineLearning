# MachineLearning
## Linear regression model from scratch
Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable.

![rep](https://github.com/shubh4mk/MachineLearning/blob/main/images/lR_rep.png)

## Dataset
I am using **Automobile Dataset** from Kaggle. This data set consists of three types of entities:
- The specification of an auto in terms of various characteristics
- Its assigned insurance risk rating
- Its normalized losses in use as compared to other cars

## OLS
![ols](https://github.com/shubh4mk/MachineLearning/blob/main/images/ols.png)

# Steps
1. We defined a function that will take x, b0, b1.
2. Then we defined functions for intercept and slope
3. We perform basic EDA on our dataset (Rows 205 columns 26)
4. We selected price as our dependent variable
5. Then we plot the correlation matrix and see for the maximum correlation with **price**, and we selected **engine-size**
6. Then we plot a scatter plot and try to fit a line
7. We evaluated our model
8. Then we calculated mse and rmse.
9. Finally we plot a gradient descent for lost and iteration ait 0.01 learning rate
10. Then we compared it to the Python sckit-learn library.

# Observation
We got same value of R² for our model from scratch and of scikit_learn

# Conclusion
In this kernel, I've created the simplest Linear Regression model from scratch, using Python. I have gone through mathematics working behind the model. Using one predictor variable and target variable we've implemented our Linear Regression model in a simple analytics use case, that is predicting the price of a car based on it's engine size. Evaluation of our model shows that our linear regression performs exactly the same as sklearn's Linear Regression model.

However, I conclude that my model from scratch is close to useless and it is no way near to python scikit-learn library.

Cheers😁😁
