# Heart_Disease_Project

# Heart Disease Prediction – Machine Learning Pipeline

This project aims to analyze, predict, and visualize heart disease risk using machine learning techniques.

---

## 🚀 Project Overview

- Dataset: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- Objective: Predict the presence of heart disease using classification models.
- Tools: Python, scikit-learn, pandas, matplotlib, Streamlit (bonus)
- Deployment: Ngrok (for demo), GitHub (for hosting)

---

## 📁 Folder Structure

Heart_Disease_Project/
│
├── data/
│ └── heart_disease.csv
├── notebooks/
│ ├── 01_data_preprocessing.ipynb
│ ├── 02_pca_analysis.ipynb
│ ├── 03_feature_selection.ipynb
│ ├── 04_supervised_learning.ipynb
│ ├── 05_unsupervised_learning.ipynb
│ ├── 06_hyperparameter_tuning.ipynb
│ └── 07_model_export.ipynb
│
├── models/
│ └── final_model.pkl
│
├── results/
│ └── evaluation_metrics.txt
│
├── README.md
├── requirements.txt
└── .gitignore


---

## 🛠️ How to Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run Jupyter notebooks (for training)
jupyter notebook

# 3. Run Streamlit app [optional]
streamlit run ui/app.py

