# Kidney Disease Prediction

This repository contains a machine learning project that predicts the presence of chronic kidney disease (CKD) based on patient health indicators. The dataset is preprocessed, analyzed, and used to train multiple models for classification.

# Dataset

The dataset used in this project is kidney_disease.csv, which contains patient information such as blood pressure, glucose levels, red blood cell count, and other vital health indicators. The target variable is class, which indicates whether a patient has CKD (1) or not (0).

# Features

The dataset includes the following features:

Numerical Features: Age, blood pressure, blood glucose random, blood urea, serum creatinine, sodium, potassium, hemoglobin, packed cell volume, white blood cell count, red blood cell count, etc.

Categorical Features: Red blood cells, pus cell, pus cell clumps, bacteria, hypertension, diabetes mellitus, coronary artery disease, appetite, pedal edema, anemia, etc.

# Data Preprocessing

Handled missing values by imputing mean for numerical columns and mode for categorical columns.

Converted text-based numerical values into proper numerical format.

Fixed inconsistent categorical values.

Encoded categorical variables into numeric representations.

# Model Training

The following machine learning models were trained:

Naïve Bayes

K-Nearest Neighbors (KNN)

Random Forest Classifier

Decision Tree Classifier

Support Vector Machine (SVM)

Performance Evaluation

Each model was evaluated using:

Confusion Matrix

Accuracy Score

Precision

Recall

F1 Score
