# SSE-TERM-PROJECT (CS6570 course project)
# AI-Based Malware Detection

## Overview
This project focuses on malware detection using machine learning techniques. It employs various classifiers to identify obfuscated malware and evaluates their performance through different metrics.

## Dataset
The dataset used for this project is [Obfuscated-MalMem2022](https://www.unb.ca/cic/datasets/malmem-2022.html).

## Research Paper
For more detailed information, refer to the research paper: [AI-Based Malware Detection](https://pdfs.semanticscholar.org/b2e2/0dc7a34753311472a5f2314fbf866d7eddd0.pdf).

## Libraries Used
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## Features
- **Data Preprocessing**: Cleans and prepares the dataset for modeling.
- **Exploratory Data Analysis (EDA)**: Analyzes malware distribution.
- **Model Training**: Implements and evaluates various classifiers:
  - Random Forest
  - Naive Bayes
  - Decision Tree
  - SVM
  - Logistic Regression
  - KNN
- **Ensemble Models**: Combines multiple classifiers using stacking techniques.

## Evaluation
Models are evaluated using:
- F1 Score
- Precision
- Recall
- Accuracy
- Confusion Matrix
