# Machine Learning Classification Project

## Overview
This project focuses on binary classification using machine learning models
in Python. The goal was to maximize partial AUC performance on a Kaggle-style dataset.

## Models Used
- Logistic Regression
- Random Forest
- Extra Trees Classifier

## Techniques
- Stratified K-Fold Cross Validation
- Hyperparameter Tuning
- Ensemble Averaging
- Feature Engineering
- Class Balancing

## Tools
- Python
- scikit-learn
- pandas
- NumPy

## Evaluation
Models were evaluated using partial AUC at 1% false positive rate.

## Results
The final ensemble model achieved approximately 0.93 public leaderboard score.

## Files
- `analysis.ipynb` contains the full workflow and experiments.
- `submission.csv` contains final predictions.
