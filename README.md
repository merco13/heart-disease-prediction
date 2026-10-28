# Heart Disease Prediction Using Machine Learning

## Overview
This project explores the application of machine learning classification algorithms to heart disease prediction using patient data. The objective is to train and evaluate classification models and compare their performance using metrics such as Accuracy, ROC-AUC, Precision, Recall, and F1-Score.

This project is intended for educational purposes and demonstrates a machine learning workflow, from data exploration to model evaluation.

---

## Objectives
* Explore and understand the dataset.
* Perform data inspection and preprocessing.
* Train multiple classification algorithms.
* Evaluate model performance using appropriate metrics.
* Compare classification accuracy and class discrimination.
* Analyze classification results and identify potential improvements.

---

## Project Workflow
1. Load and inspect the dataset.
2. Perform exploratory data analysis (EDA).
3. Prepare the features and target variable.
4. Split the dataset into training and testing sets.
5. Train classification models.
6. Evaluate the models using Accuracy and ROC-AUC.
7. Generate a classification report.
8. Interpret the results and discuss limitations.

---

## Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Models
The following classification algorithms were evaluated:
* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

---

## Model Evaluation

The classification models were evaluated using Accuracy and ROC-AUC to compare their predictive performance.

| Model | Accuracy | ROC-AUC |
| :--- | :---: | :---: |
| **Logistic Regression** | 0.8689 | 0.9102 |
| **Random Forest Classifier** | 0.8197 | 0.9167 |
| **Support Vector Machine (SVM)** | 0.8361 | 0.9102 |

### Results and Discussion
* **Logistic Regression** achieved the highest accuracy of **86.89%**, indicating the highest proportion of correct predictions among the evaluated models.
* **Random Forest Classifier** achieved the highest ROC-AUC score of **0.9167**, demonstrating the strongest ability to distinguish between the two classes according to this metric.
* **Support Vector Machine (SVM)** achieved an accuracy of 83.61% and a ROC-AUC score of 0.9102, showing competitive classification performance.

> *Overall, Logistic Regression achieved the highest accuracy, while Random Forest achieved the highest ROC-AUC.*

---

## Classification Report

The following classification report provides a detailed evaluation of the Logistic Regression's predictions on 61 samples.

| Class / Metric | Precision | Recall | F1-Score | Support |
| :--- | :---: | :---: | :---: | :---: |
| **Class 0** | 0.92 | 0.79 | 0.85 | 28 |
| **Class 1** | 0.84 | 0.94 | 0.89 | 33 |
| **Macro Average** | 0.88 | 0.86 | 0.87 | 61 |
| **Weighted Average** | 0.87 | 0.87 | 0.87 | 61 |

* **Accuracy:** 0.87 (approximately 86.89%)

### Classification Report Interpretation
* **Precision:** For class 1, the precision of 0.84 means that approximately 84% of samples predicted as class 1 were correctly classified.
* **Recall:** For class 1, the recall of 0.94 indicates that approximately 94% of actual class 1 samples were correctly identified.
* **F1-Score:** Class 1 achieved an F1-score of 0.89, reflecting the balance between precision and recall.
* **Macro Average:** The macro-average F1-score of 0.87 gives equal weight to both classes.
* **Weighted Average:** The weighted-average F1-score of 0.87 accounts for the number of samples in each class.

> * class 1 represents the presence of heart disease, its recall of 0.94 indicates that the model identified most positive cases in this evaluation set.*

---

## Evaluation Metrics Definitions
* **Accuracy:** The proportion of correctly classified observations among all observations.
* **ROC-AUC:** Measures the model's ability to distinguish between positive and negative classes across different classification thresholds.
* **Precision:** Measures the proportion of positive predictions that are correct.
* **Recall:** Measures the proportion of actual positive cases correctly identified.
* **F1-Score:** The harmonic mean of precision and recall.

---

## Dataset
The project uses a dataset containing patient-related features for heart disease classification.
You can access and download the original dataset on Kaggle

Kaggle Dataset Link: [Heart Attack Analysis & Prediction Dataset] [https://www.kaggle.com/datasets/sonialikhan/heart-attack-analysis-and-prediction-dataset]
