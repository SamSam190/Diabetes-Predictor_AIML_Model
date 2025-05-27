# Diabetes-Predictor_AIML_Model

1. Introduction
 
As the prevalence of diabetes continues to rise, especially in developing nations, early
prediction through data-driven healthcare is becoming increasingly vital. This project
addresses the problem of predicting the likelihood of diabetes using supervised machine
learning techniques. Utilizing a dataset of diagnostic attributes such as glucose level, BMI,
age, and insulin levels, the model aims to support clinical decision-making through
predictive analysis.

2. Methodology
 
Data Collection: The user uploads a CSV file containing the dataset (Pima Indians Diabetes
Dataset).
Data Preprocessing:
 Handling missing values using mean imputation for columns with zero entries.
 Feature scaling using StandardScaler.
Model Building:
 Splitting the dataset into training and testing sets.
 Training a Logistic Regression classifier.
Model Evaluation:
 Evaluating accuracy, precision, recall, and F1-score.
 Generating a confusion matrix and visualizing it with a heatmap.
