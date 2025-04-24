# Titanic Survival Prediction

## Overview

This project aims to predict Titanic passenger survival based on various features using machine learning. The dataset includes details like age, sex, passenger class, and survival status. The project covers data preprocessing, model training, and evaluation.

## Data Source

[Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## Libraries Used

- `pandas`, `numpy`: Data manipulation
- `matplotlib`: Data visualization
- `sklearn`: Machine learning model and evaluation

## Steps

### 1. **Exploratory Data Analysis (EDA)**

- Inspect and clean the data (e.g., remove outliers, handle missing values).
- Visualize relationships using boxplots and heatmaps.

### 2. **Data Preprocessing**

- Fill missing values (`Age` with median, `Embarked` with mode).
- One-hot encode categorical variables (`Sex`, `Embarked`).
- Normalize numerical features (`Age`, `Fare`).

### 3. **Modeling**

- Train a **Random Forest Classifier** using the preprocessed data.

### 4. **Model Evaluation**

- **Accuracy**: 81%
- **Precision**: 74%
- **Recall**: 71%
- **F1 Score**: 72%
- **AUC**: 82%

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
