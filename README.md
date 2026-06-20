# Task 1: ML Classification Project

## Project Title

Breast Cancer Classification using Machine Learning

## Objective

The objective of this project is to build and evaluate machine learning models for breast cancer classification. The models are trained to predict whether a tumor is malignant or benign based on medical features.

## Dataset

Dataset: Breast Cancer Wisconsin Dataset (from scikit-learn)

* Total Samples: 569
* Features: 30
* Target Classes:

  * 0 = Malignant
  * 1 = Benign

## Tools and Libraries Used

* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Project Workflow

### 1. Data Loading

The dataset was loaded using the scikit-learn library and converted into a Pandas DataFrame.

### 2. Data Preprocessing

* Checked dataset information using df.info()
* Verified missing values
* Separated features and target variable

### 3. Train-Test Split

The dataset was split into:

* Training Data: 80%
* Testing Data: 20%

### 4. Model Training

Two machine learning algorithms were implemented:

#### Logistic Regression

Used as a baseline classification model.

#### Random Forest Classifier

Used to improve classification performance and compare results.

### 5. Model Evaluation

The following evaluation metrics were used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

### 6. Visualization

A bar chart was created to compare the performance of Logistic Regression and Random Forest models.

## Results

### Random Forest Performance

* Accuracy: 96.49%
* ROC-AUC Score: 99.53%

The Random Forest model achieved excellent classification performance and outperformed the baseline model.

## Conclusion

This project successfully implemented and evaluated machine learning classification models for breast cancer prediction. Among the tested algorithms, Random Forest provided the best performance with high accuracy and ROC-AUC score, making it a reliable model for classification tasks.

## How to Run

1. Install required libraries:

pip install pandas numpy scikit-learn matplotlib

2. Open Jupyter Notebook:

jupyter notebook

3. Run all cells in the notebook.

## Files Included

* Task1_ML_Classification.ipynb
* README.md
* Screenshots of results and graphs
* Project Report
