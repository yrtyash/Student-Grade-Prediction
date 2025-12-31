# Student Grade Prediction (Regression)

## Overview
This project predicts a student's final grade using early academic indicators such as study time, past failures, and previous grades.

## Dataset
- Source: Student Performance dataset (Kaggle / UCI)
- Samples: 395 students
- Target: Final grade(G3)

## Approach
- Framed as a regression problem
- Baseline: Mean grade predictor
- Model: Linear Regression
- Evaluation metric: RMSE

## Key Insights
- Previous grades are strong predictors of final performance
- Linear Regression significantly outperforms a no-skill baseline
- Errors are higher for mid-range grades, indicating unobserved factors

## Dataset Access
The dataset is not included in this repository.
Please download 'student-mat.csv' and place it inside a 'data/' folder before running the notebook.

## Limitations
- Assumes linear relationships
- Does not capture personal or contextual factors
