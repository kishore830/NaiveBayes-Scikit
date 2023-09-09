Naive Bayes Classifier with scikit-learn

This project demonstrates the implementation of a Naive Bayes classifier using scikit-learn, a popular Python library for machine learning and data analysis. The Naive Bayes algorithm is a simple yet effective classification method that is widely used for various tasks, including text classification, spam detection, and more.

Overview
This project provides a step-by-step guide on how to:

Load a dataset for classification.
Preprocess the dataset and split it into training and testing sets.
Create a Naive Bayes classifier using scikit-learn.
Train the classifier on the training data.
Make predictions on the testing data.
Evaluate the classifier's performance using relevant metrics.

Prerequisites

pip install scikit-learn


Usage Instructions:

Ensure you have the required libraries (numpy, scikit-learn) installed.
Place your dataset in a CSV file named 'kish.csv' with the specified column structure.
Run the code in a Python environment.
Note:

This code uses random data for demonstration purposes. Replace the random data with your own dataset by modifying the 'X' and 'y' variables.


Code Description:

This Python code is an example of using the Gaussian Naive Bayes classifier from scikit-learn to perform classification on a dataset. It loads data from a CSV file, splits it into training and testing sets, and evaluates the classifier's performance.

Dataset:

File Name: kish.csv
Format: CSV (Comma-Separated Values)
Columns:
x1: Feature 1
x2: Feature 2
y: Target Variable (Class Label)

Code Steps:

Import necessary libraries, including numpy, scikit-learn's functions, and Gaussian Naive Bayes.
Load the dataset 'kish.csv' using numpy.
Split the dataset into features (X) and labels (y).
Further split the data into training and testing sets.
Create a Gaussian Naive Bayes classifier (gnb).
Train the classifier using the training data.
Make predictions on the test data.
Evaluate the classifier's accuracy and print it.
Generate a classification report for a more detailed evaluation.
