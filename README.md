# ❤️ Heart Disease Prediction using Machine Learning

This project aims to predict whether a person is likely to have heart disease based on medical attributes using machine learning models. Early prediction can help reduce risk and guide early interventions.

---

## 📁 Dataset Overview

- File: `heart_disease.csv`
- Source: UCI Heart Disease Dataset
- Records: ~300 patients
- Features:
  - `age`: Age of the patient
  - `sex`: Gender (1 = male, 0 = female)
  - `cp`: Chest pain type (0–3)
  - `trestbps`: Resting blood pressure
  - `chol`: Serum cholesterol (mg/dl)
  - `fbs`: Fasting blood sugar (>120 mg/dl)
  - `restecg`: Resting ECG results (0–2)
  - `thalach`: Maximum heart rate
  - `exang`: Exercise induced angina
  - `oldpeak`: ST depression during exercise
  - `slope`: Slope of ST segment (0–2)
  - `ca`: No. of major vessels (0–3)
  - `thal`: Thalassemia (1 = normal, 2 = fixed defect, 3 = reversible defect)
  - `target`: Heart disease (1 = Yes, 0 = No)

---

## 🎯 Project Objectives

- Load and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Train and evaluate classification models
- Compare accuracy, precision, recall, and F1-score
- Predict likelihood of heart disease

---

## ✅ Steps Performed

### 1. Data Preprocessing
- Checked for null or missing values
- Converted categorical variables if needed
- Feature scaling applied using `StandardScaler`

### 2. Exploratory Data Analysis
- Distribution plots, correlation heatmaps
- Insights on age, gender, and symptom relationships

### 3. Model Training
- Trained:
  - Logistic Regression
  - Decision Tree
  - Random Forest

### 4. Model Evaluation
- Used accuracy, precision, recall, and F1-score
- Plotted confusion matrix
- (Optional) Plotted ROC Curve

---

## 📊 Results

| Model            | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Logistic Reg.    | XX%      | XX%       | XX%    | XX%      |
| Decision Tree    | XX%      | XX%       | XX%    | XX%      |
| Random Forest    | **YY%**  | **YY%**   | **YY%**| **YY%**  |

✅ Random Forest generally performs best on clinical data due to its robustness and ability to handle mixed features.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

---

## 💡 Future Improvements

- Apply GridSearchCV for hyperparameter tuning
- Use XGBoost or LightGBM for improved performance
- Integrate with Streamlit for web-based prediction app
- Add live input form for real-time prediction

---

## 🙋‍♀️ About Me

**Wazifa Kapdi**  
Certified Data Science & AI Enthusiast  
📫 [wazifakapde39@gmail.com](mailto:wazifakapde39@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/wazifa-kapdi)  
🔗 [GitHub](https://github.com/Wazifak)  
🔗 [Portfolio](https://datascienceportfol.io/wazifakapde39)
