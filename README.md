# Drug Classification Using Machine Learning

## Project Overview
This project applies Machine Learning classification algorithms to predict the correct drug type for a patient based on medical attributes such as Age, Sex, Blood Pressure, Cholesterol, and Na_to_K ratio.

The goal is to compare multiple machine learning models and identify the best-performing model for drug prediction.

---

## Dataset Information
The dataset contains the following features:

- Age (Numeric)
- Sex (Categorical)
- BP (Blood Pressure Level)
- Cholesterol (Level)
- Na_to_K (Sodium to Potassium Ratio)
- Drug (Target Variable)

---

## Machine Learning Models Used
The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

## Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Cross Validation
8. Hyperparameter Tuning
9. Prediction on New Data

---

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation Score

---

## Best Model
After evaluation, Random Forest Classifier performed the best due to:

- High accuracy
- Better F1-score
- Strong generalization ability
- Reduced overfitting

---

## Prediction Example

Input:
Age: 23  
Sex: F  
BP: HIGH  
Cholesterol: HIGH  
Na_to_K: 25.3  

Output:
Predicted Drug: drugY

---

## Key Insights

- Na_to_K ratio is the most important feature for prediction
- Blood Pressure and Cholesterol also significantly affect drug selection
- Ensemble models perform better than single models

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Author
Student Project for AI & Data Science Assignment
