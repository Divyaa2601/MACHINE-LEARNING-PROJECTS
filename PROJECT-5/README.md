# 🩺 Diabetes Prediction using XGBoost

This project predicts whether a person is diabetic based on health-related attributes using the **XGBoost Classifier**.

---

## 📊 Dataset
- **Source:** [Kaggle – Diabetes Dataset](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)
- **Attributes:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Age, etc.
- **Target:** `Outcome` (0 = No Diabetes, 1 = Diabetes)

---

## ⚙️ Steps Involved
1. **Data Loading & Cleaning**
   - Handled missing and zero values.
   - Removed or replaced invalid entries.
2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap and boxplots.
3. **Feature Engineering**
   - Scaling numeric data using `StandardScaler`.
4. **Model Training**
   - Applied **XGBoost Classifier** for prediction.
5. **Evaluation**
   - Achieved ~80% accuracy on test data.
   - Visualized confusion matrix and feature importance.

---

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost

---

## 🚀 How to Run
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
````

3. Run the notebook:

   ```bash
   jupyter notebook diabetes_xgboost.ipynb
   ```

---

## 📈 Results

* **Accuracy:** ~80%
* **Key Insights:** Glucose level and BMI are the most influential predictors for diabetes.

---

**Author:** Divya A
