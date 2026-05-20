# Counterfeit Currency Detection 💵

Evaluation of Machine Learning algorithms to detect fake banknotes using Python.

## What it does
Compares 7 ML classification algorithms on a real banknote authentication 
dataset and identifies the best-performing model.

## Algorithms Evaluated
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)
- Random Forest
- Logistic Regression
- LightGBM (Extension)

## Results
Each algorithm evaluated on Accuracy, Precision, Recall, and F1-Score.
Best accuracy achieved: 99%+

## Dataset
- 1,372 banknote samples
- Features extracted from images using wavelet transform

## Tech Stack
Python, scikit-learn, pandas, numpy, matplotlib, seaborn, LightGBM, tkinter

## How to run
pip install scikit-learn pandas numpy matplotlib seaborn lightgbm
python Main.py
