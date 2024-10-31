# diabetes
 It provides an overview of the purpose, setup, and usage of the code for predicting diabetes using a Random Forest classifier.

 # Diabetes Prediction Using Random Forest Classifier

This project implements a machine learning model to predict diabetes based on medical data, using the Pima Indians Diabetes dataset. The model utilizes a Random Forest Classifier and various preprocessing techniques to provide a classification between diabetic (1) and non-diabetic (0) individuals.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction

The project is designed to predict the likelihood of diabetes in patients based on specific health metrics like glucose level, blood pressure, BMI, and more. It uses a Random Forest Classifier to provide high accuracy and stability in predictions.

## Dataset

The dataset used is the **Pima Indians Diabetes Dataset**, available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Pima+Indians+Diabetes).

### Features
The dataset includes 8 medical predictors:
1. `Pregnancies` - Number of times pregnant
2. `Glucose` - Plasma glucose concentration
3. `BloodPressure` - Diastolic blood pressure (mm Hg)
4. `SkinThickness` - Triceps skinfold thickness (mm)
5. `Insulin` - 2-Hour serum insulin (mu U/ml)
6. `BMI` - Body mass index (weight in kg/(height in m)^2)
7. `DiabetesPedigreeFunction` - Diabetes pedigree function
8. `Age` - Age (years)

**Target Variable**:
- `Outcome` - Binary indicator of diabetes (1 = diabetic, 0 = non-diabetic)

## Installation

1. Clone the repository or download the file.
   ```bash
   git clone https://github.com/nehaatri1997/diabete.git
   cd diabetes-prediction

Install the required libraries:
pip install numpy pandas scikit-learn

Model
The Random Forest Classifier is used due to its efficiency with tabular data and high interpretability. The model leverages 80% of the data for training and 20% for testing.

Preprocessing
The data is standardized using StandardScaler to improve model performance and convergence.
Evaluation
After training, the model’s performance is evaluated using:

Accuracy - Percentage of correct predictions.
Confusion Matrix - Provides insight into the types of classification errors.
Classification Report - Displays precision, recall, and F1-score for each class.

Model Accuracy: 77.92%
Confusion Matrix:
 [[87 13]
 [21 33]]
Classification Report:
               precision    recall  f1-score   support
           0       0.81      0.87      0.84       100
           1       0.72      0.61      0.66        54
    accuracy                           0.78       154
   macro avg       0.76      0.74      0.75       154
weighted avg       0.77      0.78      0.77       154

