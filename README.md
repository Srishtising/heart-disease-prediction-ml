# Heart Disease Classification

## Project Overview

This project applies machine learning classification techniques to predict heart disease using patient data.

## Models Implemented

* Simple Decision Tree
* Tuned Decision Tree
* Rule-Based Classification
* kNN
* Random Forest
* AdaBoost

## Model Performance

| Model                 |   Accuracy |  Precision |     Recall | Specificity |
| --------------------- | ---------: | ---------: | ---------: | ----------: |
| Simple Decision Tree  |     78.80% |     79.44% |     83.33% |      73.17% |
| Tuned Decision Tree   |     81.52% |     83.33% |     83.33% |      79.27% |
| Rule-Based Classifier |     81.52% |     83.33% |     83.33% |      79.27% |
| kNN (k=5)             | **84.78%** |     83.64% | **90.20%** |      78.05% |
| Random Forest         |     84.24% |     83.49% |     89.22% |      78.05% |
| AdaBoost              |     82.61% | **84.31%** |     84.31% |  **80.49%** |

## Key Findings

* kNN with k=5 achieved the highest accuracy and recall.
* Random Forest provided competitive performance through ensemble learning.
* Rule-Based Classification provided interpretable IF-THEN rules.
* Feature scaling significantly improved kNN performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab
