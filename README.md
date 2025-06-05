# Comparing Classifiers

## Overview
The goal of this project is to compare the performance of various classifiers including:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Support Vector Machines (SVM)

Evaluating their performance, accuracy, and training efficiency.

## Objective
- Evaluate and compare different classification models.
- Identify the best-performing model based on accuracy, training time, and cross-validation scores.
- Visualize the tradeoff between training speed and model performance.

## Data
The dataset comes from the [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing).  
The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns.

## Methodology

**Model Selection:**
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Support Vector Machines (SVM)

**Model Evaluation:**
- Train-Test Split
- Cross-validation (5-fold)
- Accuracy scores

**Visualization:**
- Scatter plots for performance versus training time
- Annotated plots to clearly indicate model performance metrics

## Model Comparison Table

| Model                      | Train Time(s) | Train Accuracy | Test Accuracy | CV Accuracy (5-fold) |
|---------------------------|---------------|----------------|---------------|----------------------|
| Logistic Regression        | 9.5235        | 0.9001         | 0.9011        | 0.8992               |
| K-Nearest Neighbors        | 48.8159       | 0.9080         | 0.8958        | 0.8917               |
| Decision Trees             | 9.6011        | 0.9018         | 0.9012        | 0.8991               |
| Support Vector Machine     | 11.1644       | 0.8994         | 0.9012        | 0.8992               |

## Key Findings
- **Support Vector Machine (SVM):** Highest accuracy and most efficient training time.
- **Logistic Regression:** Good accuracy, moderate training time, beneficial for interpretability.
- **Decision Trees:** Comparable accuracy to Logistic Regression, suitable for modeling complex data relationships.
- **K-Nearest Neighbors (KNN):** Lower efficiency due to significantly longer training times despite reasonable accuracy.

**Overall**, SVM emerged as the best-performing model based on accuracy and efficiency.

## Usage
- Ensure dependencies like `scikit-learn`, `matplotlib`, and `pandas` are installed.
- Run the notebook sequentially to reproduce results and visualizations.

## Dependencies
- Python (>= 3.8)
- pandas
- matplotlib
- scikit-learn
"""
