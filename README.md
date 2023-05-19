# R-Stats-Analysis


This repository contains the implementation of three statistical questions using R. Each question explores different statistical concepts and techniques. The solutions provided aim to showcase the application of these concepts and techniques in real-world scenarios. 

## PART 1: Non-constant Variance

In this PART, the dataset consists of pipeline measurements collected by the National Institutes of Standards and Technology (NIST). The objective is to develop a regression equation for correcting in-field measurements using laboratory measurements. The analysis includes the following tasks:

Fit a regression model and check for non-constant variance. 
Explore transformations (such as square root, log, and inverse) on the variables to achieve a linear relationship with constant variance. Utilize ggplot to assist in selecting the appropriate transformation method.

## PART 2: Box Cox Transformation

The ozone dataset from the faraway library is used in this PART. The goal is to fit a model for the ozone (O3) concentration using temperature, humidity, and ibh (inversion base height) as predictors. The Box-Cox plot is utilized to determine the best transformation for the response variable.

## PART 3: Feature Selection Methods

The dataset used in this question is the Boston dataset from the ISLR2 package. The objective is to predict the per capita crime rate. The analysis is divided into the following tasks:

1. Read the dataset into an R dataframe and create scatterplot matrices (using pairs) and ggplot visualizations to gain insights into the dataset. Describe the dataset and comment on the correlations between predictors.
2. Fit a multiple regression model between the response variable (crime rate) and the other predictors. Evaluate the coefficients using summary() and summarize the findings. Analyze the significance of p-values.
3. Interpret the coefficients of the predictors and identify the most important predictors based on their coefficients.
4. Perform feature selection using various methods (forward stepwise with p-value threshold, backward stepwise with p-value threshold, forward stepwise with AIC, forward stepwise with BIC, forward stepwise with Mallows CP) by splitting the dataset into training and test sets. Compare the performance of the reduced models on the test dataset.

The implementation of these statistical analyses showcases different techniques and methods to gain insights and make predictions based on the given datasets. Feel free to explore the code and analysis in the respective files.

Please note that the code and analysis provided here are for educational and illustrative purposes.
