# ❤️ Heart Disease Prediction

This project predicts the likelihood of heart disease using the [UCI Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).  
It applies data preprocessing, feature selection, clustering, and machine learning models to identify the most important predictors of heart disease.  

---

 📊 Project Structure
heart-disease-prediction/
│── data/ # Raw & processed datasets
│── notebooks/ # Step-by-step Colab notebooks
│── Models/ # Saved trained models (.pkl files)
│── results/ # Evaluation metrics and plots
│── app.py # Streamlit app for deployment
│── requirements.txt # Python dependencies
│── README.md # Project documentation
│── .gitignore # Files ignored by Git

📂 Dataset

Source: UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/45/heart+disease

Records: 303 patients

Features: 13 clinical attributes (age, sex, chest pain type, cholesterol, thal, etc.)

Target: Presence of heart disease (binary classification)

🔬 Methodology

Data Preprocessing

Handle missing values

Encode categorical variables (one-hot encoding)

Feature scaling

Feature Selection

Random Forest feature importance

Recursive Feature Elimination (RFE)

Chi-Square test

Modeling

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

Clustering (K-Means, Hierarchical)

Evaluation

Accuracy, Precision, Recall, F1-score

Confusion Matrix

ROC-AUC Curve

📈 Results

Selected key predictors: thalach, oldpeak, slope, thal, ca, exang, cp

Best performing model: Random Forest Classifier


Author: Mosaab Abdellah

📧 mosab.abdella2020@gmail.com

🔗 LinkedIn Profile : https://www.linkedin.com/in/mosaababdellah/

🐙 GitHub : https://github.com/Mosaab-Abdella
