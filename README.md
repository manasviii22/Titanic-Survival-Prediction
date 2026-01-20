# Titanic-Survival-Prediction
Predict whether a passenger survived the Titanic disaster using Machine Learning in Python.

# Project Overview

Dataset: Titanic passenger information (age, sex, fare, class, etc.)

Goal: Predict survival (Survived column)

Model Used: Logistic Regression

Tools & Libraries: Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

# Steps Performed

Data Cleaning

Dropped columns with too many missing values (Cabin)

Filled missing Age values with the mean

Filled missing Embarked values with mode

Converted categorical variables (Sex, Embarked) into numeric

Exploratory Data Analysis (EDA)

Count plots for survival, gender, and class

Visual analysis of features vs survival

# Feature Selection

Dropped irrelevant columns (PassengerId, Name, Ticket)

Selected relevant features for prediction

# Train-Test Split

Split data into training (80%) and testing (20%) sets

# Model Training

Logistic Regression trained on the training set

Increased max_iter to ensure convergence

# Model Evaluation

Training Accuracy: 0.8075842696629213

Testing Accuracy: 0.7821229050279329

Confusion matrix and classification report

Predictions for individual passengers

# Results

Example Prediction: “Passenger Did Not Survive”

# How to Run

Clone this repository

Open Titanic-ML-Project.ipynb in Jupyter Notebook

Run all cells from top to bottom

The final cell predicts survival for a sample passenger

# Libraries Used

pandas

numpy

matplotlib

seaborn

scikit-learn
