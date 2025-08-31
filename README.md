❤️ Heart Disease Prediction
📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction of heart disease can help in timely diagnosis and preventive care.
This project applies machine learning models to predict the likelihood of heart disease based on patient health indicators.

📂 Dataset

Source: UCI Heart Disease Dataset
 (also available on Kaggle)

Features include:

age – Age of the patient

sex – Gender (1 = male, 0 = female)

cp – Chest pain type

trestbps – Resting blood pressure

chol – Serum cholesterol level

fbs – Fasting blood sugar

restecg – Resting ECG results

thalach – Maximum heart rate achieved

exang – Exercise-induced angina

oldpeak – ST depression induced by exercise

slope – Slope of peak exercise ST segment

ca – Number of major vessels colored by fluoroscopy

thal – Thalassemia condition

target – Presence of heart disease (1 = yes, 0 = no)

⚙️ Methodology

Data Preprocessing

Handled missing values

Encoded categorical features

Feature scaling

Exploratory Data Analysis (EDA)

Age vs. Heart Disease probability

Gender impact on heart disease

Correlation heatmap

Model Building

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Model Evaluation

Accuracy

Precision, Recall, F1-score

ROC-AUC Curve

📊 Results

Logistic Regression and Random Forest gave the best results.

Achieved accuracy ~85% (update with your actual score).

Key insight: Features like cp, thalach, and oldpeak have the highest impact on prediction.

🚀 How to Run the Project

Clone the repository

Install requirements:

pip install -r requirements.txt


Run the notebook in Jupyter

📌 Tech Stack

Python, Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🙌 Acknowledgements

Dataset: UCI / Kaggle Heart Disease Dataset

✨ Author: Diwakar Kumar
