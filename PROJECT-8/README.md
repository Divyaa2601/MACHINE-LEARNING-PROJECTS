# 🎬 Sentiment Analysis with NLTK

This project demonstrates **Sentiment Analysis** on movie reviews using **Natural Language Toolkit (NLTK)**.  
It showcases how natural language processing (NLP) can classify text as **positive** or **negative** based on word usage patterns.

---

## 📘 Overview
Sentiment analysis is a key application of NLP, helping determine whether a given text expresses a **positive** or **negative** sentiment.  
Here, we use the **Movie Reviews** dataset included in NLTK and apply the **Naive Bayes Classifier**, one of the most efficient algorithms for text classification.

---

## 📂 Dataset

**Name:** Movie Reviews Corpus  
**Source:** Built-in with `nltk.corpus`  
**Total Reviews:** 2000  
- 1000 Positive  
- 1000 Negative  

Each review is already labeled, making it ideal for supervised learning.

---

## ⚙️ Project Workflow

1. Import and download the `movie_reviews` corpus  
2. Tokenize text using NLTK’s `word_tokenize`  
3. Build Bag-of-Words features  
4. Remove stopwords and punctuation  
5. Analyze word frequency distribution  
6. Train and test the **Naive Bayes Classifier**  
7. Evaluate model performance  

---

## 🧠 Algorithm Used

### 🧩 Naive Bayes Classifier
A probabilistic classifier based on **Bayes’ Theorem**, assuming independence between features.  
It works exceptionally well for text classification problems like sentiment analysis.

---

## 📊 Results

| Model | Training Accuracy | Testing Accuracy |
|--------|-------------------|------------------|
| Naive Bayes | ~95% | ~70% |

*(Accuracy may vary slightly depending on random splits.)*

---

## 💻 Technologies Used

- **Python**  
- **NLTK** (Natural Language Toolkit)  
- **Matplotlib** (for visualization)  
- **Collections.Counter** (for word frequency analysis)

---

## 🧾 File Structure

```

Sentiment-Analysis-with-NLTK/
│
├── nltk_movie_reviews_sentiment.ipynb
├── README.md
└── requirements.txt

```

---

## 🚀 How to Run the Project

1. **Clone the repository**

   ```
   git clone https://github.com/yourusername/Sentiment-Analysis-with-NLTK.git
   cd Sentiment-Analysis-with-NLTK
   ```

2. **Install dependencies**

   ```
   pip install nltk matplotlib
   ```

3. **Run the Jupyter Notebook**

   ```
   jupyter notebook nltk_movie_reviews_sentiment.ipynb
   ```

---

## 🔍 Sample Output

* Displays the most informative words distinguishing positive and negative reviews
* Shows top word frequencies
* Plots log-log frequency distribution
* Evaluates classifier accuracy

---

## 🧩 Future Enhancements

* Compare results using Logistic Regression, SVM, or Random Forest
* Implement TF-IDF vectorization or Word2Vec embeddings
* Create a Streamlit or Flask web app for real-time sentiment detection
* Integrate with Twitter API for live tweet sentiment analysis

---

## 👩‍💻 Author

**Divya A**
