# Healthcare Disease Prediction using Machine Learning

An end-to-end machine learning project that predicts diabetes risk using real-world healthcare data.  
The system prioritizes **recall** to reduce false negatives, which is critical in medical decision-making.

---

## Domain

Healthcare | Machine Learning | Classification  

---

## Project Overview

This project predicts diabetes risk based on patient medical features and compares the performance of two classification models:

- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  

Special emphasis is placed on **recall** to ensure diabetic patients are correctly identified.

**Objectives:**  

- Predict diabetes risk from medical features  
- Minimize false negatives to reduce health risks  
- Compare KNN and Random Forest performance  
- Analyze model results from a healthcare perspective  

---

## Dataset Information

**Dataset:** Pima Indians Diabetes Dataset  
**Source:** Kaggle  

**Features include:**  

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

**Target:** Outcome (0 = No Diabetes, 1 = Diabetes)

---

## Methodology

1. Data loading and validation  
2. Exploratory Data Analysis (EDA) to understand feature distributions  
3. Correlation analysis to study relationships between medical variables  
4. Feature scaling for distance-based models  
5. Model training using KNN and Random Forest  
6. Model evaluation with emphasis on **recall**  
7. Analysis of false negatives from a healthcare perspective  

---

## Results

- **Random Forest** achieved higher recall than KNN  
- Reducing false negatives is crucial in healthcare applications  
- Recall is prioritized over overall accuracy to minimize missed diagnoses  

**Medical Insight:**  
False negatives in healthcare prediction represent missed diagnoses. Minimizing these is essential for timely treatment and patient safety.

---

## Project Structure

```bash
healthcare-disease-prediction-ml/
├── data/
│   └── diabetes.csv
├── notebooks/
│   └── Healthcare_Disease_Prediction.ipynb
├── images/
│   └── visualizations_and_plots/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/healthcare-disease-prediction-ml.git
cd healthcare-disease-prediction-ml
```

2. Create and activate a virtual environment (recommended):

**Windows:**

```bash
python -m venv venv
venv\Scripts\activate
```

**Mac/Linux:**

```bash
python -m venv venv
source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook notebooks/Healthcare_Disease_Prediction.ipynb
```

> Ensure `diabetes.csv` is placed inside the `data/` directory before running the notebook.

---

## Key Skills Demonstrated

- Healthcare data analysis  
- Feature evaluation and correlation analysis  
- Machine learning classification  
- Model comparison and evaluation  
- Recall and risk-based decision making  
- Professional project structuring  

---

## Future Improvements

- Experiment with additional classifiers (XGBoost, LightGBM)  
- Deploy a web app for real-time diabetes risk prediction  
- Add probability scores and visualization of predictions  
- Include more patient features to improve model performance  
- Store historical predictions in a database for longitudinal analysis  

---

## Author

Hassan Ali  
Data Scientist | Machine Learning Engineer

GitHub: https://github.com/hassan-ali786  

---

⭐ Feel free to fork this repository and explore further improvements!
