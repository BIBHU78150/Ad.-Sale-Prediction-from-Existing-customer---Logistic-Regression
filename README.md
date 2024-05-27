# Advertisement Sale Prediction from Existing Customers - Logistic Regression

## Project Overview

This project aims to predict whether a new customer will purchase a product based on their age and salary using a Logistic Regression model. The process involves data collection, preprocessing, model training, validation, and making predictions. The detailed steps are outlined below.

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Data Preprocessing](#data-preprocessing)
5. [Model Training](#model-training)
6. [Validation](#validation)
7. [Prediction](#prediction)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [License](#license)

## Project Description

The primary goal of this project is to develop a model that can accurately predict the purchase status of a customer based on their age and salary. The solution involves:

1. **Identifying the Problem**: Predicting whether a new customer will buy a product or not.
2. **Collecting Dataset**: Based on the age and salary of existing customers and their purchase status (Purchased or Not Purchased).
3. **Loading and Summarizing Dataset**: Loading the dataset from a CSV file and summarizing it.
4. **Data Segregation**: Splitting the dataset into features (X) and target (Y).
5. **Feature Scaling**: Standardizing or normalizing the feature values.
6. **Splitting the Dataset**: Dividing the dataset into training and testing sets.
7. **Training the Model**: Using Logistic Regression to train the model.
8. **Validation**: Evaluating the model using a confusion matrix.
9. **Making Predictions**: Predicting the purchase status of new customers.

## Installation

To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib (optional, for data visualization)

You can install these libraries using pip:

```sh
pip install pandas numpy scikit-learn matplotlib
