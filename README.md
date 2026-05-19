# formula1-dataset
Predicting Formula 1 podium finishes using machine learning. End-to-end data science project comparing Logistic Regression, Random Forest, and Gradient Boosting on the Kaggle F1 World Championship dataset (2000–2024).
# Formula 1 Podium Prediction 🏎️

A machine learning project that predicts whether a Formula 1 driver will 
finish on the podium using pre-race and qualifying data.

## Overview
This project applies supervised classification techniques to the Formula 1 
World Championship dataset (2000–2024) to predict podium finishes. Three 
models are compared — Logistic Regression, Random Forest, and Gradient 
Boosting — across multiple evaluation metrics.

## Dataset
- Source: Kaggle — Formula 1 World Championship Dataset
- Size: ~14,000 driver-race records (2000–present)
- Features: grid position, qualifying position, constructor, laps, year

## Tech Stack
- Python 3.12
- pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- Google Colab

## Key Findings
- Grid position and qualifying position are the strongest predictors
- Gradient Boosting achieved the highest ROC-AUC
- Constructor identity captures meaningful variance from team dominance eras

## Files
- `f1_podium_prediction.ipynb` — full analysis notebook
- `F1_Podium_Prediction_Report.pdf` — technical report (3500 words)

## Author
University coursework project — AI & Machine Learning module
