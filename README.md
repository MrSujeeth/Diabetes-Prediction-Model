🩺 Diabetes Prediction Model using Machine Learning

This project is a Machine Learning-based Diabetes Prediction System** developed using Python and Support Vector Machine (SVM).  
The model predicts whether a person is diabetic or non-diabetic based on medical diagnostic parameters.

---

📌 Project Overview

Diabetes is a chronic disease that requires early detection for effective management.  
This project uses the Diabetes Dataset and applies data preprocessing, feature standardization, and SVM classification to build an accurate prediction system.

---

🧠 Machine Learning Algorithm Used

- Support Vector Machine (SVM)
  - Kernel: `Linear`
  - Reason: Works well for binary classification problems and high-dimensional data

---

📂 Dataset Details

- Source: Diabetes Dataset
- Target Variable: `Outcome`
  - `0` → Non-Diabetic
  - `1` → Diabetic

 Features Used: 
- Glucose  
- BloodPressure  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  

---

 ⚙️ Technologies & Libraries

- Python 🐍
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

 🔄 Project Workflow

1. **Data Collection**
   - Load dataset using Pandas
2. **Data Analysis**
   - Statistical summary & class distribution
3. **Data Preprocessing**
   - Feature scaling using `StandardScaler`
4. **Train-Test Split**
   - 80% Training, 20% Testing
5. **Model Training**
   - SVM with linear kernel
6. **Model Evaluation**
   - Accuracy score on training & test data
7. **Prediction System**
   - Predicts diabetes for new user input

---

 📊 Model Performance

- Training Accuracy:** ~78–80%
- Testing Accuracy:** ~75–78%

(Accuracy may vary slightly due to random state and dataset variations)
