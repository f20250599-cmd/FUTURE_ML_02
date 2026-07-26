# Support Ticket Classification Project

# Overview

This project uses Machine Learning and Natural Language Processing (NLP) techniques to automatically classify customer support tickets into different ticket categories based on the ticket description.

The dataset was cleaned, analyzed, and transformed into numerical features using TF-IDF Vectorization before building a Logistic Regression classification model.

# Objectives

* Analyze customer support ticket data
* Clean and preprocess text data
* Convert text into numerical features using TF-IDF
* Build a ticket classification model
* Evaluate model performance
* Predict ticket categories from new ticket descriptions

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook
* Logistic Regression
* TF-IDF Vectorizer

# Dataset

* Support Tickets Dataset
* 8,469 Records
* 17 Columns

# Project Workflow

## 1. Data Cleaning

* Loaded dataset
* Checked dataset dimensions
* Verified column names
* Checked data types
* Identified missing values

## 2. Feature Selection

* Selected the following columns:

* Ticket Description
* Ticket Type
* Ticket Priority

## 3. Text Preprocessing

* Selected Ticket Description as the feature
* Selected Ticket Type as the target variable
* Converted text into numerical vectors using TF-IDF Vectorizer

## 4. Machine Learning Model

* Split data into training and testing datasets
* Trained a Logistic Regression classifier
* Predicted ticket categories

## 5. Model Evaluation

* Evaluation Metrics:

* Classification Report
* Confusion Matrix
* Accuracy Score

# Results

The model successfully classified customer support tickets into different ticket categories using Natural Language Processing techniques.

The project demonstrates the complete workflow of a text classification problem using Scikit-learn.

# Repository Contents

* Support_Ticket_Classification.ipynb
* support_tickets.csv
* Confusion_Matrix.png
* Classification_Report.png
* README.md


# How to Run

1. Clone the repository
2. Install required libraries
```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the Jupyter Notebook
```bash
jupyter notebook Support_Ticket_Classification.ipynb
```
4. Run all cells to reproduce the results


### This project was completed as part of the Future Interns Machine Learning Internship Program.

# Author

Roshini Varanat Rajesh

BE Mathematics & Computing
