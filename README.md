# Linear-Regression-with-Gradient-Descent

This project demonstrates the implementation of a simple linear regression model using the concept of gradient descent for optimization. The model aims to predict the value of a target variable (Y) based on a given feature (X). The dataset consists of known data points, and the goal is to find the optimal linear relationship between X and Y using the linear equation:

y = wx+b

where:

𝑦 is the predicted value,
𝑤 is the weight (slope),
b is the bias (intercept).
 
The steps of the project include:

Data Plotting: Visualizing the given data points and plotting the actual vs predicted values to analyze the model's performance.
Model Initialization: The weight w is initialized randomly, and predictions are made for the input data points using the linear equation.
Prediction Calculation: A forward pass function calculates the predicted output based on the current weight and bias values.
Loss Calculation: The Mean Squared Error (MSE) is used as the loss function to measure the difference between the predicted and actual values, guiding the optimization process.
Optimization: The weight and bias are adjusted using gradient descent (though this part is outlined, further steps can be added to improve the optimization process).
