# Intrusion Detection System (IDS) using Machine Learning
This repository contains a research project focused on detecting web application attacks using machine learning techniques. The goal is to evaluate and compare the performance of multiple supervised learning models for intrusion detection, highlighting their effectiveness in improving web security over traditional rule-based methods.

## Overview
Web applications are common targets for cyberattacks, making intrusion detection a critical task. This project explores how machine learning can automatically identify malicious requests by learning from data, reducing the need for manual rule updates and improving adaptability to new threats.

The study trains and compares three different models:

* Random Forest

* K-Nearest Neighbours (KNN)

* Support Vector Machine (SVM)

Each model is evaluated using multiple performance metrics to understand its strengths and limitations in detecting various types of attacks.

## Methodology

### 1. Data Preprocessing

* Cleaned and normalized the dataset.

* Encoded categorical features and handled missing values.

* Applied feature scaling to improve model performance.

### 2. Feature Engineering

* Extracted relevant features from network and HTTP request data.

* Conducted correlation analysis to remove redundant attributes.

### 3. Model Training

* Trained multiple supervised models.

* Tuned hyperparameters using cross-validation to optimize accuracy and reduce overfitting.

### 4. Evaluation

* Compared model performance using:

Accuracy, Precision, Recall, F1-score and Confusion matrix

* Visualized results for easier comparison and interpretation.

## Tech Stack

Language: Python

Libraries: scikit-learn, pandas, numpy, matplotlib, Jupyter Notebook
