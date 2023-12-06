# DIY-Linear-Regression
Building Linear Regression models from scratch using python.

Linear Regression is an established method for predicting numerical outcomes - e.g. weight, sales.

In this project I develop by own models using python and compare their performance to sklearn. My key aim throughout is to improve the performance of models iteratively, so that their performance can be closer to sklearn's - in terms of accuracy and time to complete.

## Description
My motivation for this project stems from a broader interest in the mathematics that underpins machine learning. I wanted to see if I could use my coding and maths skills to create high-performing linear regression models from scratch. I also wanted to gain practical experience in iteratively improving a model to improve performance.

During this project I build three linear regression models, all of which use gradient descent methods that I have coded myself. I applied these models to two data sets, a TV advertising budget vs Sales dataset (ads), and a Height vs Weight data set(hw) [i.e. 1 continuous indepdent variable, 1 continuous dependent variable in both cases].

The first model uses unscaled data and a standard gradient descent method. Having tested this model on the ads dataset, I concluded that its performance (in terms of time to complete and accuracy) was insufficiently good across a range of tests.

The second model is similar to the first but uses scaled X data, and performed better with the ads dataset. However, it was highly sensitive to hyperparameters, meaning any gains in time taken to complete stand to be lost in time taken to find appropriate hyperparameters. 

The third model uses scaled X data and uses gradient descent with momentum. This model performed much better and was less sensitive to hyperparameters, as I demonstrated by applying to to both hw and ads datasets. 

## File Structure

- DIY_Gradient_Descent_for_Linear_Regression.ipynb (the main file for this project)
- tvmarketing.csv (the tv ads dataset)
- SOCR-HeightWeight.csv (the height weight dataset)


