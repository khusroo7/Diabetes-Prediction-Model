# Diabetes-Prediction-Model
Project Overview
<br>

This project focuses on developing a predictive model for diabetes using Logistic Regression, a popular statistical method for binary classification problems. The primary objective is to leverage various health-related features to predict whether an individual is likely to develop diabetes. The model is built on a dataset sourced from Kaggle, which includes a range of medical and demographic variables that are commonly associated with diabetes risk.

<br>
Dataset Description:
<br>
The dataset used for this project contains several key features that are relevant to predicting diabetes:
<br>
Pregnancies: The number of times the patient has been pregnant.
<br>
Glucose: Plasma glucose concentration a few hours after a meal.
<br>
Blood Pressure: Diastolic blood pressure (mm Hg).
<br>
Skin Thickness: Thickness of the triceps skin fold (mm).
<br>
Insulin: 2-Hour serum insulin (mu U/ml).
<br>
BMI (Body Mass Index): Weight in kg/(height in m)^2.
<br>
Diabetes Pedigree Function: A function that scores the likelihood of diabetes based on family history.
<br>
Age: The age of the patient.
<br>
The target variable, Outcome, is binary and indicates whether the patient has diabetes (1) or not (0).
<br>

Model Development
<br>
Logistic Regression was chosen as the modeling technique due to its simplicity, interpretability, and effectiveness in binary classification problems. The model was trained on the dataset with the goal of identifying patterns in the features that correlate with the onset of diabetes.
<br>

Key Steps in the Model Development:
<br>
Data Preprocessing:
<br>
1. Handling missing values.
2. Normalizing and scaling features where necessary.
<br>

Splitting the data into training and testing sets.
<br>

3. Model Training:
<br>
Applying Logistic Regression to the training data.
<br>

4. Model Evaluation:
<br>
Testing the model on unseen data.
Evaluating performance using metrics such as accuracy, precision, recall, confusion matrix, and classification report.
<br>

Model Evaluation
<br>
The performance of the model was rigorously evaluated to ensure its predictive capability:
<br>
Accuracy: The proportion of correctly predicted instances out of the total instances. This metric provides an overall sense of how well the model is performing.
<br>
Precision: The proportion of true positive predictions to the total positive predictions made by the model. High precision indicates a low false positive rate.
<br>
Recall: The proportion of true positive predictions to the actual positive cases in the dataset. High recall indicates that the model is good at identifying actual positive cases.
<br>
Confusion Matrix: A table that summarizes the performance of the model by showing the correct and incorrect predictions broken down by each class.
<br>
Classification Report: A comprehensive summary that includes precision, recall, and F1-score.
<br>
This model serves as a baseline for predicting diabetes, with potential for further enhancement through hyperparameter tuning, feature engineering, or exploring alternative machine learning algorithms.
