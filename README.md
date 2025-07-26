# ANN-for-Pytorch-Salary-Prediction-
(ANN) using PyTorch to predict data science salaries. It uses the ds_salaries.csv dataset, focusing on features like experience level, employment type, remote work ratio, and company size to predict salaries in USD. T
The notebook covers data preprocessing with pandas and scikit-learn, including label encoding of categorical variables and normalization, followed by training a basic ANN with two linear layers.
# Data Science Salary Prediction with PyTorch

## Description
This project implements a simple Artificial Neural Network (ANN) using PyTorch to predict data science salaries based on features such as experience level, employment type, remote work ratio, and company size. The dataset (`ds_salaries.csv`) is preprocessed using pandas and scikit-learn, and the model is trained to predict salaries in USD. The notebook includes data loading, encoding categorical variables, normalization, and training a neural network with a basic architecture.

Usage
The notebook loads and preprocesses the dataset, converting categorical variables to numerical values and normalizing features and target.
A PyTorch neural network with two linear layers is defined and trained using Mean Squared Error loss and Stochastic Gradient Descent.
Training runs for 10 epochs, with loss printed per epoch.
