Student Score Prediction Using Linear Regression
This repository contains a simple machine learning project that predicts a student's exam score based on the number of hours they study. It's implemented in Python using scikit-learn for supervised learning, specifically linear regression. This was developed as part of The Sparks Foundation GRIP internship in Data Science and Business Analytics.

Project Overview
The goal is to build a model that can forecast academic performance from study time. Using a small dataset of 25 student records, we train a linear regression model to establish a relationship between study hours (independent variable) and scores (dependent variable). This serves as an introductory example of regression tasks in machine learning.

Key features:

Data loading and exploration

Visualization of data distribution

Model training and evaluation

Prediction for new inputs

Objective
Predict the percentage score a student is likely to achieve based on their daily study hours. For instance, what score would a student get if they studied for 9.25 hours a day?

Dataset
The dataset is sourced from a public CSV file (included as student_scores.csv). It consists of two columns:

Hours: Number of hours studied per day (float values ranging from 1.1 to 9.2)

Scores: Corresponding exam scores (integers from 17 to 95)
