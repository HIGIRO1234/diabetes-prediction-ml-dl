# Diabetes Prediction Using Machine Learning and Deep Learning

## Project Overview

This project focuses on predicting diabetes using Machine Learning and Deep Learning techniques. The goal is to identify individuals who may be at risk of diabetes based on demographic and clinical health information. The project explores multiple machine learning and neural network models, evaluates their performance, and identifies the most effective approach for diabetes prediction.

## Problem Statement

Diabetes is a major public health concern worldwide. Early detection can help reduce complications and improve patient outcomes. This project aims to develop predictive models that can accurately classify individuals as diabetic or non-diabetic using healthcare-related features.

## Dataset

The dataset contains patient demographic and clinical information, including:

* Gender
* Age
* Hypertension
* Heart Disease
* Smoking History
* Body Mass Index (BMI)
* HbA1c Level
* Blood Glucose Level

### Target Variable

* **0** = No Diabetes
* **1** = Diabetes

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* TensorFlow / Keras
* XGBoost
* Jupyter Notebook

## Project Workflow

1. Data Loading and Exploration
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Scaling
5. Machine Learning Model Development
6. Deep Learning Model Development
7. Model Evaluation
8. Results Visualization
9. Error Analysis
10. Conclusion

## Models Implemented

### Machine Learning Models

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

### Deep Learning Models

* Basic Sequential Neural Network
* Sequential Neural Network with Dropout and Batch Normalization
* Functional API Neural Network with L2 Regularization
* Neural Network using TensorFlow tf.data Pipeline

## Results Summary

| Model                | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
| -------------------- | -------: | --------: | -----: | -------: | ------: |
| Logistic Regression  |   0.9608 |    0.8700 | 0.6335 |   0.7332 |  0.9612 |
| Random Forest        |   0.9723 |    1.0000 | 0.6741 |   0.8053 |  0.9686 |
| SVM                  |   0.9616 |    0.9236 | 0.5976 |   0.7257 |  0.9594 |
| XGBoost              |   0.9729 |    0.9940 | 0.6853 |   0.8113 |  0.9791 |
| Basic Neural Network |   0.9605 |    0.8587 | 0.6400 |   0.7334 |  0.9595 |
| Dropout + BatchNorm  |   0.9605 |    0.9026 | 0.5994 |   0.7204 |  0.9595 |
| Functional API + L2  |   0.9598 |    0.8856 | 0.6059 |   0.7195 |  0.9566 |
| tf.data Pipeline     |   0.9597 |    0.8621 | 0.6253 |   0.7249 |  0.9590 |

## Best Performing Model

The XGBoost model achieved the best overall performance:

* Accuracy: 97.29%
* Precision: 99.40%
* Recall: 68.53%
* F1 Score: 81.13%
* ROC-AUC: 97.91%

These results indicate that XGBoost is highly effective for diabetes prediction on structured healthcare data.

## Visualizations Included

* Learning Curves
* Confusion Matrix
* ROC Curve
* Model Comparison Table

## Future Improvements

Future work may include:

* Hyperparameter Optimization
* Advanced Feature Engineering
* Explainable AI Techniques
* Larger Healthcare Datasets
* Deployment as a Web Application

## Author

Loic Higiro

