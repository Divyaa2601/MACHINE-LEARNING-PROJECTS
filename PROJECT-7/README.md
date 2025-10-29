# 🧠 KNN and Naive Bayes Breast Cancer Classification

This project focuses on classifying breast cancer tumors as **Malignant** or **Benign** using two supervised machine learning algorithms — **K-Nearest Neighbors (KNN)** and **Naive Bayes**.  
The model is trained and evaluated on the **Breast Cancer Wisconsin Dataset**, a popular benchmark dataset for medical diagnostics.

---

## 📂 Dataset
**Dataset Name:** Breast Cancer Wisconsin (Diagnostic)  
**Source:** [Kaggle - Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

The dataset contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.  
Each instance describes cell nuclei characteristics, such as radius, texture, smoothness, and concavity.

---

## ⚙️ Project Workflow

1. **Import Libraries**  
2. **Load Dataset**  
3. **Data Preprocessing**  
4. **Feature Selection and Splitting**  
5. **Model Building**  
   - K-Nearest Neighbors (KNN)  
   - Naive Bayes  
6. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

---

## 🧩 Algorithms Used

- **K-Nearest Neighbors (KNN)**  
  Classifies data based on the majority label among its *k* nearest neighbors.  

- **Naive Bayes Classifier**  
  A probabilistic model based on Bayes’ theorem assuming feature independence.  

---

## 📊 Results

| Model | Accuracy |
|--------|-----------|
| KNN | 96% (approx.) |
| Naive Bayes | 94% (approx.) |

*(Accuracy may vary slightly based on train-test split.)*

---

## 💻 Technologies Used
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  

---

## 📁 File Structure
```

KNN-and-NaiveBayes-BreastCancer-Classification/
│
├── breast_cancer_dataset.csv
├── breast_cancer_classification.ipynb
├── README.md
└── requirements.txt

````

---

## 🚀 How to Run
1. Clone this repository  
   ```
   git clone https://github.com/yourusername/KNN-and-NaiveBayes-BreastCancer-Classification.git
   cd KNN-and-NaiveBayes-BreastCancer-Classification
````

2. Install dependencies

   ```
   pip install -r requirements.txt
   ```
3. Run the notebook

   ```
   jupyter notebook breast_cancer_classification.ipynb
   ```

---

## 🧠 Future Improvements

* Add other ML models (SVM, Random Forest) for comparison
* Hyperparameter tuning for better accuracy
* Deploy model as a web app using Flask or Streamlit

---

## 👩‍💻 Author

**Divya A**

Would you like me to also generate a **short `requirements.txt`** file for you (listing only the needed libraries)?
```
