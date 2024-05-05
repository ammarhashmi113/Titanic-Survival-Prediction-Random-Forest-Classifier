# Titanic-Survival-Prediction-Random-Forest-Classifier
Titanic passenger survival using random forest classifier

## Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The dataset used for this project is sourced from Kaggle's Titanic: Machine Learning from Disaster competition.

## Dataset
- `train.csv`: Raw dataset containing passenger information for training the model.
- `test.csv`: Raw dataset containing passenger information for evaluating the model's performance.
  
## Contents
- `train.csv`:** Raw dataset containing passenger information.
- `test.csv`:** Raw dataset containing passenger information.
- `Titanic_Survival_Prediction.ipynb`: Jupyter notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: Documentation providing an overview of the project.
- `Project_Report.pdf`: PDF file containing a detailed report about the project.

## Data Preprocessing
- Filled missing values in the "Age", "Cabin", and "Embarked" columns.
- Converted categorical variables into dummy variables.

## Model Training
- Used a Random Forest Classifier for training the model.
- Split the dataset into training and validation sets.
- Evaluated the model's performance using the ROC-AUC score on the validation set.

## Results
The model achieved an ROC-AUC score of 0.888 on the validation set
