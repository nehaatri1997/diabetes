# diabetes
 It provides an overview of the purpose, setup, and usage of the code for predicting diabetes using a Random Forest classifier.

 # Diabetes Prediction Using Random Forest Classifier

This project implements a machine learning model to predict diabetes based on medical data, using the Pima Indians Diabetes dataset. The model utilizes a Random Forest Classifier and various preprocessing techniques to provide a classification between diabetic (1) and non-diabetic (0) individuals.

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
5. `Insulin` - 2-hour serum insulin (mu U/ml)
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


