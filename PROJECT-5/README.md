# 🩺 Diabetes Prediction using XGBoost

This project aims to predict whether a person is diabetic or not based on health parameters using the **XGBoost Classifier**. It uses the Diabetes Dataset from Kaggle for training and evaluation.

---

## 📂 Dataset Information

**Source:** [Diabetes Dataset – Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)  
**Attributes:**
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  
- Outcome (Target: 0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Project Workflow

1. **Data Loading & Preprocessing**
   - Handled missing and zero values
   - Normalized and cleaned data

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and correlations using Seaborn and Matplotlib

3. **Feature Engineering**
   - Scaled numeric columns using `StandardScaler`

4. **Model Building**
   - Implemented **XGBoost Classifier** for prediction

5. **Model Evaluation**
   - Evaluated model using accuracy, confusion matrix, and feature importance

---

## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  
- XGBoost  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction-xgboost.git
````

2. Navigate to the project folder:

   ```bash
   cd diabetes-prediction-xgboost
   ```

3. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

4. Run the notebook or Python script:

   ```bash
   jupyter notebook diabetes_xgboost.ipynb
   ```

   or

   ```bash
   python diabetes_xgboost.py
   ```

---

## 📈 Results

* **Model Accuracy:** ~80%
* **Key Predictors:** Glucose level and BMI
* **Observation:** Individuals with higher glucose and BMI values are more prone to diabetes.

---

## 👩‍💻 Author

**Divya A**
Would you like me to include a **sample output section** (with confusion matrix or accuracy screenshot placeholder) for GitHub display?
```
