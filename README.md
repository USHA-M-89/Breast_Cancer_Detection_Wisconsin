Breast Cancer Detection (Wisconsin Dataset)
Project Overview
-----------------
This project uses the Breast Cancer Wisconsin (Diagnostic) Dataset to build a machine learning model that predicts whether a tumor is benign or malignant.
The goal is to demonstrate a complete ML workflow — from data preprocessing, exploratory data analysis (EDA), to model building and evaluation.

Dataset
--------
Source: UCI Machine Learning Repository

Features: 30 numeric features describing cell nuclei (e.g., radius, texture, smoothness).

Target:

M = Malignant

B = Benign

Steps Involved
---------------
Import Libraries & Dataset
---------------------------
Used pandas, numpy, matplotlib, seaborn, sklearn.

Data Cleaning
-------------
Checked for missing values.

Dropped irrelevant columns (like id).

Exploratory Data Analysis (EDA)
-----------------------------------
Visualized distribution of features.

Correlation heatmap to identify important features.

Data Preprocessing
------------------
Converted categorical target into numeric labels (0/1).

Scaled features using StandardScaler.

Model Building
---------------
Logistic Regression

Random Forest Classifier

Evaluation
-----------
Accuracy, Precision, Recall, F1-score.

Confusion Matrix for better understanding.

Results
--------
Logistic Regression Accuracy: ~96%

Random Forest Accuracy: ~98%

Random Forest performed slightly better due to handling feature importance and non-linear relationships.

How to Run
-----------
Clone the repository:
---------------------
git clone https://github.com/USHA-M-89/Breast_Cancer_Detection_Wisconsin.git


Install dependencies:
---------------------
pip install -r requirements.txt


Open Jupyter Notebook and run:
-----------------------------
jupyter notebook Breast_Cancer_Detection.ipynb

Key Learnings
--------------
Importance of EDA in understanding data.

Feature scaling improves model performance.

Ensemble methods (Random Forest) outperform simpler models in this dataset.

Author
Usha M
LinkedIn
