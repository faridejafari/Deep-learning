# Deep-learning

# Insurance Fraud Detection Using Deep Learning

## Project Overview
This project aims to detect fraudlent insurance claims using machine learning and deep learning techniques. 

## Dataset
The  dataset inclodes features such as customer demographics, policy information, incident details, and claim amounts. It contains 1000 records with 9 initial feature, Later expanded with feature engineering and one=hot encoding.

## Feature and Preprocessing
- Remove features with high cardinality or irrelevant to the task.
- categorical variables with few unique values were label-encoded.
- Other categorical variables were one-hot encoded
- The target variable is 'fraud-reported' indicating if a claimwas fraudulent.

## Models Used
- Random Forest Classifier
- Logistic Regression
- LightGBM
- Deep Neural Network (Keras Sequential Model)

## Results 
- Rondom Forest achieved around 80% accuracy with desent precision and recall.
- Logistic Regression showed issues with class imbalance and convergence.
- LightGBM was tuned with specific hyperparameters to optimize F1 score.
- DeepLearning model trained with 50 epochs and reached ~84% accuracy.

Future work 
- Address class class imbalance with oversampling or weighted loss.
- Hyperparameter tuning with cross-validation.
- Deploy the model as an API.

Author
 Faride Jafari





