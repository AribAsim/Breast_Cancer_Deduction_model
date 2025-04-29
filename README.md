# Breast Cancer Prediction Using Logistic Regression

This project uses machine learning techniques to classify breast cancer tumors as malignant or benign based on features extracted from cell nuclei images. The data is preprocessed, normalized, and used to train a simple logistic regression model from scratch using NumPy.

## Dataset

The dataset used is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) which contains 569 instances and 30 numeric features.

### Features

- Radius, texture, perimeter, area, smoothness, etc. (mean, standard error, and worst)
- Diagnosis: M = malignant, B = benign

## Dependencies

- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Install dependencies using:

```bash
pip install numpy pandas matplotlib scikit-learn