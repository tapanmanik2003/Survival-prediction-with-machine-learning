# Titanic Survival Prediction

This project focuses on predicting the survival of passengers on the Titanic using machine learning models.

## Introduction

In this project, we explore the Titanic dataset, perform data preprocessing, and build machine learning models to predict passenger survival. The primary goal is to demonstrate the end-to-end process of data analysis, cleaning, modeling, and evaluation.

## Data Exploration and Preprocessing

- Loaded the Titanic dataset using Pandas.
- Dropped unnecessary columns (`'PassengerId', 'Name', 'Cabin', 'Ticket', 'Embarked'`).
- Replaced gender values in the 'Sex' column with numerical values.
- Handled missing values in the 'Age' column by filling with the median.
- Checked and visualized the distribution of 'Fare' and 'Age'.
- Handled outliers in the 'Age' column.

## Data Visualization

- Plotted a count plot for the 'Survived' variable based on gender.
- Visualized the distribution of 'Fare' and 'Age' using distplots and boxplots.

## Model Building and Evaluation

Trained and evaluated several machine learning models:

- Logistic Regression
- Support Vector Machine (SVM)
- k-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Naive Bayes (GaussianNB)

Evaluated models using confusion matrices, classification reports, and accuracy scores on both training and testing sets.

## Requirements

- Python
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
