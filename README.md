# Higgs Boson Signal Classification — Deep Learning Project

## Overview

This project is part of the Deep Learning Module (Cohort 11) and focuses on solving a real-world binary classification problem using tabular data. The goal is to classify whether a particle collision event corresponds to a Higgs boson signal or background noise.

## Dataset

- **Source**: [Kaggle Higgs Boson Machine Learning Challenge](https://www.kaggle.com/competitions/higgs-boson)
- **Features**: 30 anonymized real-valued features
- **Target**: Binary label indicating signal (`s`) or background (`b`)

## Tasks Completed

### 1. Data Preparation
- Handled missing values (`-999.0`) by replacing them with column means
- Normalized continuous features using `StandardScaler`
- Split the data into train (70%), validation (15%), and test (15%)

### 2. Model Building
- Built a deep neural network using TensorFlow/Keras
- Applied regularization techniques like Dropout and BatchNormalization
- Used callbacks: `EarlyStopping` and `ReduceLROnPlateau`
- Evaluated alternate optimizers and architecture depth

### 3. Model Evaluation
- Reported metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC
- Visualized confusion matrix and ROC curve
- Compared deep learning performance with XGBoost as a baseline

### 4. Reflection
Included insights on:
- Effects of model depth and activations
- Methods to mitigate overfitting
- Optimizer and learning rate impact
- Potential improvements with more resources

## File Structure

- `Higgs_Boson_DL_Assignment.ipynb` — Full project notebook
- `README.md` — This file

## Author

Ahmad Arslan  
Student & Co-Founder at Grynas Private Ltd
