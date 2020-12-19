# Neural_Network_Charity_Analysis

## Overview of the analysis

The purpose of this project is to use machine learning and neural networks for this dataset in order to tell a customer if the applicants will be successful using alphabet soup. The data contains over 34,000 organizations that have been funded by alphabet soup. This project is comprised of 3 steps: 1. Preprocessing the data for the neural network; 2. To compile,train and evaluate the model; and 3. To optimize the model.

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model?

- The variable we are targeting in this module is the IS_SUCCESSFUL column.

What variable(s) are considered to be the features for your model?

- The variables we are featuring that we are using are every column except the ones that we will drop ("EIN" and "NAME").

What variable(s) are neither targets nor features were removed?

- The first features we drop are the 'EIN' & 'NAME' because we expect both features to have very little impact on our outcome.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

My model is made with an input feature & two hidden layers. The first hidden layer has 50 neurons, the second has 25. I also included an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".

Were you able to achieve the target model performance?

The target model performance was 75% but I was unable to meet the target model performance.

What steps did you take to try and increase model performance?

Some of the steps I took were to add additional neurons and hidden layers and changing the activation functions as well to see if different functions would perform better.

## Summary

The best model accuracy ended up being 69.2%. I dropped two features from the original dataset that I deteremined wouldn't have an impact on determining success in the model. While I wasn't able to get to 75% I believe if we had more data we could improve the accuracy of our model.
