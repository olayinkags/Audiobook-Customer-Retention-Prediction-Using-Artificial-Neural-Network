# Audiobook-Customer-Retention-Prediction-Using-Artificial-Neural-Network


## Problem Statement:

In this project, the goal is to develop a machine learning algorithm to predict whether a customer of an Audiobook app will make another purchase within the next 6 months. The dataset contains information related to audio book purchases, including customer engagement metrics over a 2-year period. The objective is to identify customers with a high probability of conversion, enabling the company to focus advertising efforts more efficiently and uncovering key factors influencing customer retention.

## Project Overview:

The Audiobook company aims to optimize its marketing strategy by predicting customer behavior. The primary challenge is to distinguish customers likely to make a future purchase from those who are not. This project involves creating a classification algorithm with two classes: "will buy" (1) and "won't buy" (0). By leveraging customer data such as average book length, total minutes listened, support requests, and other features, the algorithm will provide insights into the key metrics influencing customer retention.

## Business Impact:

1. **Cost Savings:** By focusing marketing efforts on customers with a high likelihood of conversion, the company can maximize return on investment and minimize advertising expenses.

2. **Growth Opportunities:** Efficient targeting of potential customers increases the chances of customer conversion, contributing to business growth and creating new opportunities.

## Data Description:

The dataset includes various customer-related features such as Customer ID, Book length overall (sum of the minute length of all purchases), Book length avg (average length in minutes of all purchases), Price paid_overall (sum of all purchases) ,Price Paid avg (average of all purchases), Review (a Boolean variable whether the customer left a review), Review out of 10 (if the customer left a review, his/her review out of 10), Total minutes listened, Completion (from 0 to 1), Support requests (number of support requests; everything from forgotten password to assistance for using the App), and Last visited minus purchase date (in days). The target variable is a Boolean indicating whether a customer will make another purchase within the next 6 months.

## Objective:

Build a robust machine learning algorithm capable of predicting customer behavior and aiding the Audiobook company in making informed decisions for customer retention.

## Approach:

Part 1. **Data Preprocessing:** Importing data, splitting the data into the training set and Test set, and feature scaling.

Part 2. **Building the Artificial Neural Network (ANN):** Initializing the ANN, adding the input layer and the first hidden layer, Adding the second hidden layer and adding the output layer.

Part 3. **Training the Artificial Neural Network (ANN):** Compiling the ANN, and training the ANN on the training set.

Part 4. **Making the Predictions and Evaluating the model:** Predicting the test set results, and making the confusion matrix.

## Expected Outcome:

The developed machine learning model will serve as a valuable tool for the Audiobook company, allowing them to focus resources on retaining customers likely to make future purchases. The project aims to contribute to cost savings, growth opportunities, and enhanced customer relationship management.
