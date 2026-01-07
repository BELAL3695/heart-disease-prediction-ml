# Heart Disease Prediction using Machine Learning

This project predicts whether a person has heart disease using a Machine Learning classification model trained on clinical patient data.

## 📌 Project Overview
Heart disease is a major health concern worldwide.  
In this project, a **Logistic Regression** model is built to classify patients as having heart disease or not based on medical attributes.

The dataset consists of **303 patient records** with **13 medical features** and **1 target variable**.

---

## 🧠 Machine Learning Details
- Algorithm: Logistic Regression
- Problem Type: Binary Classification
- Target Variable:
  - `0` → No Heart Disease
  - `1` → Heart Disease

---

## 🗂 Dataset Information
Total Records: **303**  
Total Columns: **14**

### 🔹 Features:
- `age` – Age of the patient
- `sex` – Gender (1 = male, 0 = female)
- `cp` – Chest pain type
- `trestbps` – Resting blood pressure
- `chol` – Serum cholesterol (mg/dl)
- `fbs` – Fasting blood sugar (>120 mg/dl)
- `restecg` – Resting electrocardiographic results
- `thalach` – Maximum heart rate achieved
- `exang` – Exercise-induced angina
- `oldpeak` – ST depression induced by exercise
- `slope` – Slope of the peak exercise ST segment
- `ca` – Number of major vessels colored by fluoroscopy
- `thal` – Thalassemia type

### 🔹 Target:
- `target` – Heart disease presence (0 or 1)

---

## 🛠 Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Workflow
1. Data loading using Pandas
2. Data analysis and preprocessing
3. Feature and target separation
4. Train-test split with stratification
5. Model training using Logistic Regression
6. Model evaluation using accuracy score
7. Prediction on new patient data

---

## 📊 Model Evaluation
- Training and testing accuracy calculated using `accuracy_score`
- Model tested on unseen data to evaluate generalization

---

## 🚀 How to Run the Project
1. Open the `.ipynb` file in **Jupyter Notebook** or **Google Colab**
2. Run all cells sequentially
3. Modify input values to test predictions on new data

---

## 📌 Conclusion
The Logistic Regression model effectively predicts the presence of heart disease based on clinical parameters and can assist in early risk assessment.

