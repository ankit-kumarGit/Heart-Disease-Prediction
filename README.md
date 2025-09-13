# ❤️ Heart Disease Prediction Model  

## 📌 Overview  
This project predicts the likelihood of a person having **heart disease** based on clinical features such as age, chest pain type, cholesterol level, ECG results, and more.  
The model is trained using the **UCI Heart Disease Dataset** and deployed in a simple interface where users can input their health data to get predictions.  

---

## 📊 Dataset  
- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)  
- **Features Used:**  
  - Age  
  - Sex  
  - Chest Pain Type (TA, ATA, NAP, ASY)  
  - Resting Blood Pressure  
  - Cholesterol  
  - Fasting Blood Sugar  
  - Resting ECG  
  - Maximum Heart Rate  
  - Exercise-Induced Angina  
  - Oldpeak (ST depression)  
  - ST Slope (Up, Flat, Down)  
  - Number of Major Vessels  
  - Thalassemia  

- **Target Variable:**  
  - `0` → No/Low Risk of Heart Disease  
  - `1` → High Risk of Heart Disease  

---

## ⚙️ Technologies Used  
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn (for visualization)  
- Pickle / Joblib (for saving model)  
- Flask / Streamlit (for deployment)  

---

## 🚀 How to Run  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
