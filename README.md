# Predict-the-Introverts-from-the-Extroverts
This repository contains my solution for the 2025 Kaggle Playground Series competition: Predict the Introverts from the Extroverts.

## Overview
The task is to classify individuals as either Introvert or Extrovert based on features related to their personality traits and social behavior.

## Contents
Model Training.ipynb – Main notebook used to preprocess the data, build models, and generate submissions.

submissions/ – Contains all CSV submission files.

mlflow/ – MLflow experiment tracking logs.

data/ – Contains the data used in the competition.

## Methods Used
* Imputation of missing data (KNN Imputer)
* Encoding of categorical variables
* t-SNE visualization
* Random Forest Classifier with hyperparameter tuning
* Evaluation via accuracy
* MLflow for experiment tracking

## Result
Achieved the benchmark accuracy of 0.975708.
