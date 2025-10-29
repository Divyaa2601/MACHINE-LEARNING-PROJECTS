# 🛍️ Mall Customers Segmentation using K-Means Clustering

This project aims to segment mall customers into distinct groups based on their **Annual Income** and **Spending Score** using the **K-Means Clustering algorithm**.  
Such segmentation helps businesses identify target customer groups for marketing and strategy planning.

---

## 📂 Dataset Information

**Source:** [Mall Customers Dataset – Kaggle](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

**Attributes:**
- **CustomerID** – Unique ID for each customer  
- **Gender** – Male / Female  
- **Age** – Age of the customer  
- **Annual Income (k$)** – Annual income of the customer  
- **Spending Score (1-100)** – Score assigned based on customer spending behavior  

---

## ⚙️ Project Workflow

1. **Data Loading & Cleaning**
   - Imported and inspected the dataset
   - Checked for null values and duplicates

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions and relationships between features
   - Identified income and spending score as the most impactful features

3. **Data Preprocessing**
   - Scaled numerical features using `StandardScaler`

4. **Model Building**
   - Applied **K-Means Clustering** with different K values (1–10)
   - Determined optimal K using the **Elbow Method**

5. **Model Evaluation**
   - Evaluated clustering performance using **Silhouette Score**
   - Visualized final clusters with scatter plots

---

## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  

---

## 🚀 How to Run

1. Clone this repository:
  ````
   git clone https://github.com/your-username/mall-customers-kmeans.git
 ````

2. Navigate to the project folder:

   ```
   cd mall-customers-kmeans
   ```

3. Install dependencies:

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

4. Run the notebook:

   ```
   jupyter notebook mall_customers_kmeans.ipynb
   ```

---

## 📈 Results

* **Optimal Clusters (K):**  5
* **Silhouette Score:**  ~0.55
* **Observation:**
  

  * Cluster 1: High income, high spenders
  * Cluster 2: High income, low spenders
  * Cluster 3: Medium income, average spenders
  * Cluster 4: Low income, high spenders
  * Cluster 5: Low income, low spenders

---

## 👩‍💻 Author

**Divya A**

B.Tech – Artificial Intelligence and Machine Learning
