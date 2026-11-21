DS471 Machine Learning Project: Breast Cancer Classification

Classification of breast tumours as Malignant or Benign using the Breast Cancer Wisconsin (Diagnostic) dataset (569 samples, 30 numerical features). Models: Logistic Regression, Random Forest and a Neural Network.

Repository contents
File	Description
DS471_code.ipynb	Full workflow with outputs: cleaning, EDA, splitting, tuning, training, evaluation
traditional_results.csv	Test results of Logistic Regression and Random Forest
final_results.csv	Test results of all three models
Dataset

UCI Breast Cancer Wisconsin (Diagnostic), loaded in the notebook from Kaggle: uciml/breast-cancer-wisconsin-data (via kagglehub).

How to run
Open DS471_code.ipynb in Google Colab or Jupyter.
Run all cells in order. Required packages: kagglehub, pandas, numpy, scikit-learn, matplotlib, seaborn.
The random seed is 42 everywhere. Data split: 70% train / 15% validation / 15% test (stratified).
