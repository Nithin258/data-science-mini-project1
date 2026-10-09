# Data Science Mini Project: Breast Cancer Diagnosis Analysis

A beginner-friendly end-to-end data science project (Module 5, Day 17–20).

## Dataset
Breast Cancer Wisconsin (Diagnostic), a public UCI Machine Learning Repository dataset (also on Kaggle):
569 patients, 30 cell-nucleus measurements, labelled malignant or benign.

## What this project does
- Cleans and checks the data (no missing values or duplicates)
- Explores and visualizes patterns: histograms, box plots, scatter plot, correlation heatmap
- Finds the strongest indicators of malignancy
- Trains Logistic Regression and Random Forest models (about 96% accuracy on unseen data)
- Summarizes findings and limitations

## Key findings
- Malignant tumours have a clearly larger radius, perimeter and area.
- Concavity and concave points are among the strongest indicators.
- Many size features are highly correlated with each other.

## Run it
Open `Module5_Data_Science_Mini_Project.ipynb` in Google Colab (or Jupyter) and run all cells. No download is needed, as the dataset loads through scikit-learn.

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

> Educational project only, not medical advice.
