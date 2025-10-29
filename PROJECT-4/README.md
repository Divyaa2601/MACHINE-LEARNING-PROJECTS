## ❤️ Heart Disease Prediction using Random Forest

### 📘 Overview

This project predicts the presence of heart disease using a **Random Forest Classifier**.
It analyzes medical data, preprocesses it, trains a model, and evaluates performance using accuracy and confusion matrix.

---

### ⚙️ Tools & Libraries

* Python
* Pandas, NumPy — Data processing
* Matplotlib, Seaborn — Visualization
* Scikit-learn — Machine learning
* Joblib — Model saving

---

### 📂 Dataset

**File:** `heart.csv`
**Target:** `HeartDisease` (1 = Yes, 0 = No)
**Features:** Age, Sex, ChestPainType, RestingBP, Cholesterol, MaxHR, etc.

---

### 🧩 Steps

1. Load and clean data (remove duplicates, handle outliers).
2. Encode categorical columns.
3. Split data into train/test sets.
4. Scale features.
5. Train Random Forest model.
6. Evaluate accuracy and confusion matrix.
7. Tune parameters with GridSearchCV.
8. Save model as `best_random_forest_model.joblib`.

---

### 📊 Model Results

* Accuracy: ~85–90%
* Evaluation: Confusion matrix & metrics (precision, sensitivity, specificity)

---

### 🚀 Run the Project

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
python heart_rf.ipynb
```

---

### 👩‍💻 Author

**Divya A** 
