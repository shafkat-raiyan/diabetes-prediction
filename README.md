# 🎓 Diabetes Prediction Model

This project implements a **Diabetes Prediction Model** using **Logistic Regression**.  
The model predicts whether a person is diabetic or not based on input features such as glucose levels, BMI, and age.

---

## 📂 Project Structure
- `diabetes.csv` → Dataset (from Kaggle)  
- `Diabetes Prediction.ipynb` → Jupyter Notebook containing data preprocessing, model training, evaluation, and predictions

---

## ⚙️ Technologies Used
- Python 3  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook

---

## 🧠 Model
This is a **Logistic Regression** model:

y = 1 / (1 + e^(-z))

where **z** is the linear combination of features:

z = w₁x₁ + w₂x₂ + w₃x₃ + ... + b

The model was trained using **gradient descent** to minimize the cost function.  
Before training, **feature normalization** was applied to ensure that each input feature contributes proportionally and to help with faster convergence. To tackle overfitting, **regularization** was used.

---

## 📊 Results
- **Accuracy**: ~74%  
- **Precision**: ~0.75  
- **Recall**: ~0.85  
- **F1-Score**: ~0.79  
- **ROC-AUC**: ~0.84  

✅ The model predicts whether a person is diabetic with good accuracy, and shows strong recall to identify potential diabetic cases (especially important in a medical context).

---
