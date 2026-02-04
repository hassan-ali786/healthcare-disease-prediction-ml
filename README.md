Healthcare Disease Prediction using Machine Learning
Overview

This project presents an end-to-end machine learning solution for predicting diabetes risk using real-world healthcare data. The system applies classification techniques with a strong focus on recall to reduce false negatives, which is critical in medical decision-making.

Domain

Healthcare | Machine Learning | Classification

Dataset

Pima Indians Diabetes Dataset
Source: Kaggle

This dataset contains medical diagnostic measurements for patients and a binary outcome indicating the presence or absence of diabetes.

Objective

The objective of this project is to predict diabetes risk based on medical features and to compare the performance of K-Nearest Neighbors (KNN) and Random Forest classifiers. Special emphasis is placed on recall, as failing to identify a diabetic patient can have serious health consequences.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Methodology

Data loading and validation

Exploratory Data Analysis (EDA) to understand feature distributions

Correlation analysis to study relationships between medical variables

Feature scaling for distance-based models

Model training using KNN and Random Forest

Model evaluation with emphasis on recall

Analysis of false negatives from a healthcare perspective

Results

The Random Forest classifier achieved a higher recall score than the KNN model. This makes Random Forest more suitable for healthcare applications where minimizing false negatives is more important than maximizing overall accuracy.

Medical Insight

In healthcare prediction systems, false negatives represent missed diagnoses. Reducing false negatives is essential to ensure timely treatment and to minimize health risks. Therefore, recall is prioritized over accuracy in this project.

Installation and Setup

Follow the steps below to run the project locally:

1. Clone the repository
git clone https://github.com/hassan-ali786/healthcare-disease-prediction-ml.git
cd healthcare-disease-prediction-ml

2. Create and activate a virtual environment (recommended)
python -m venv venv


Windows

venv\Scripts\activate


Mac/Linux

source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Run the notebook
jupyter notebook notebooks/Healthcare_Disease_Prediction.ipynb


Ensure the dataset file diabetes.csv is placed inside the data/ directory before running the notebook.

Project Structure
healthcare-disease-prediction-ml/
│
├── data/
│   └── diabetes.csv
│
├── notebooks/
│   └── Healthcare_Disease_Prediction.ipynb
│
├── images/
│   └── visualizations and plots
│
├── models/
│   └── saved trained models
│
├── README.md
├── requirements.txt
└── .gitignore

Key Skills Demonstrated

Healthcare data analysis

Feature evaluation and correlation analysis

Machine learning classification

Model comparison and evaluation

Recall and risk-based decision making

Professional project structuring

Author

Hassan Ali
Data Science | Machine Learning | Healthcare Analytics

