# R-Stats-Analysis


In this repository, I have implemented three statistical analyses using R. Each analysis explores various statistical concepts and techniques to solve specific problems. The purpose of these implementations is to demonstrate the practical application of these concepts and techniques in real-world scenarios.

## PART 1: Non-constant Variance

I worked with a dataset of pipeline measurements collected by NIST. The objective was to develop a regression equation to correct in-field measurements using laboratory measurements. To achieve this, I fitted a regression model and checked for non-constant variance. I also explored different transformations, such as square root, log, and inverse, on the variables to establish a linear relationship with constant variance. The selection of the appropriate transformation method was aided by utilizing ggplot.

## PART 2: Box Cox Transformation

I used the ozone dataset from the faraway library. The goal was to create a model for the ozone concentration by considering temperature, humidity, and ibh (inversion base height) as predictors. To determine the best transformation for the response variable, I employed the Box-Cox plot.

## PART 3: Feature Selection Methods

I analyzed the Boston dataset from the ISLR2 package to predict the per capita crime rate. The analysis involved multiple tasks, such as creating scatterplot matrices and ggplot visualizations to gain insights into the dataset, fitting a multiple regression model, interpreting the coefficients of predictors, and identifying the most important predictors based on their coefficients. Additionally, I performed feature selection using various methods, such as forward stepwise with p-value threshold, backward stepwise with p-value threshold, forward stepwise with AIC, forward stepwise with BIC, and forward stepwise with Mallows CP. The performance of the reduced models on the test dataset was compared.


These implementations demonstrate different statistical techniques and methods for gaining insights and making predictions based on the provided datasets. You are welcome to explore the code and analysis in the respective files. Please note that the code and analysis provided here are for educational and illustrative purposes only.
