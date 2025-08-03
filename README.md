# ❤️ Heart Disease Prediction using Machine Learning

This project predicts whether a patient is likely to have heart disease using clinical features such as age, cholesterol, chest pain, and more. Early prediction helps with preventive healthcare and timely treatment.

---

## 📁 Dataset Overview

- Source: UCI Heart Disease Dataset
- Total Records: ~300
- Columns:
  - `age`, `sex`, `cp` (chest pain type), `trestbps` (resting BP), `chol` (cholesterol),
  - `fbs` (fasting blood sugar), `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`, `target`

---

## 🎯 Project Objectives

- Explore clinical features and their correlation with heart disease
- Preprocess and clean the dataset
- Train multiple machine learning models
- Compare their performance and select the best one

---

## ✅ Tasks Performed

### 1. Data Cleaning & Preprocessing
- Checked for null values (none found)
- Normalized numerical features using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Plotted feature distributions, target imbalance, and correlation matrix
- Analyzed how age, chest pain, and cholesterol affect heart disease

### 3. Model Training
- Trained 3 classifiers:
  - Logistic Regression
  - Decision Tree
  - Random Forest

### 4. Model Evaluation
- Used accuracy scores and classification reports
- Random Forest showed the best performance

---

## 📊 Model Performance

| Model              | Accuracy (%) |
|--------------------|--------------|
| Logistic Regression| 82.42        |
| Decision Tree      | 82.42        |
| Random Forest      | **84.62** ✅ |

✅ **Random Forest** had the best accuracy and performed well on both precision and recall.

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 💡 Future Work

- Add GridSearchCV for hyperparameter tuning
- Try advanced models (e.g., XGBoost, LightGBM)
- Deploy as a web app using Streamlit
- Add a user form to accept input and predict on-the-fly

---

## 🙋‍♀️ About Me

**Wazifa Kapdi**  
Certified Data Science & AI Enthusiast  
📫 [wazifakapde39@gmail.com](mailto:wazifakapde39@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/wazifa-kapdi)  
🔗 [GitHub](https://github.com/Wazifak)  
🔗 [Portfolio](https://datascienceportfol.io/wazifakapde39)
