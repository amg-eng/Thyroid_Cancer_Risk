# Thyroid Cancer Recurrence Prediction Using Ensemble Learning

## Overview
This project aims to predict the recurrence risk of thyroid cancer using various machine learning models combined into an ensemble. The ensemble model leverages the strengths of multiple algorithms to enhance prediction accuracy and reliability.

## Authors
- [Ziyad El-Fayoumy](https://github.com/Zoz-HF)
- [Mohamed Elsayed](https://github.com/melsayed8450)
- [Amgad Atef](https://github.com/amg-eng)
- [Abdelrahman Shawky](https://github.com/AbdulrahmanGhitani)

## Institution
Department of Systems and Biomedical Engineering, Faculty of Engineering, Cairo University

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Preprocessing](#preprocessing)
4. [Models Implemented](#models-implemented)
5. [Ensemble Method](#ensemble-method)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Dependencies](#dependencies)
9. [Documentation](#documentation)
## Introduction
The objective of this study was to train machine learning models to predict the likelihood of recurrence in patients diagnosed with well-differentiated thyroid cancer. Given the importance of accurate risk prediction in guiding patient management and follow-ups, this project seeks to improve prediction accuracy using ensemble learning techniques.

## Data Description
The dataset includes clinical and pathological features of 383 patients diagnosed with well-differentiated thyroid cancer over a 15-year period, with a minimum follow-up of 10 years. Key features include:
- Age
- Gender
- Smoking history
- Radiotherapy history
- Thyroid function
- Physical examination results
- Pathology
- Tumor focality
- ATA risk assessment
- TNM staging
- Initial treatment response
- Recurrence status

## Preprocessing
1. **Duplicate Removal**: Removed 19 duplicate records.
2. **Label Encoding**: Transformed categorical variables into numerical values.
3. **Feature Selection**: Selected features highly correlated with the target variable using a correlation matrix.

## Models Implemented
- **Support Vector Machine (SVM)**
- **Decision Tree (DT)**
- **Random Forest (RF)**
- **K-Nearest Neighbors (KNN)**
- **Artificial Neural Network (ANN)**

## Ensemble Method
The ensemble model combines predictions from multiple base models using:
- **Voting Classifier**: Aggregates predictions via majority voting.
- **Stacking Classifier**: Uses a meta-model to combine base model predictions for enhanced accuracy.

## Results
The ensemble model achieved the highest accuracy compared to individual models, effectively enhancing risk stratification for recurrence prediction. Key performance metrics include sensitivity, specificity, AUC, and accuracy.

## Conclusion
The project demonstrates the potential of ensemble learning in predicting thyroid cancer recurrence. The ensemble model outperformed individual models, providing a more accurate tool for clinical decision-making and personalized treatment planning.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- TensorFlow
- scikeras
- Pickle

## Documentation
For detailed information on the project, refer to the [Project_Paper](docs/Ensemble_learning_for_improved_%20prediction_of_Thyroid_Cancer_Recurrence.pdf)