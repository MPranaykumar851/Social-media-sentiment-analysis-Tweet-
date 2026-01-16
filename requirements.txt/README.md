# Social Media Sentiment Analysis using Machine Learning

This project implements a machine learning-based sentiment analysis system to classify social media tweets into **Negative**, **Neutral**, and **Positive** sentiments.

---

## 📌 Project Overview

Social media platforms generate massive amounts of unstructured text data.  
This project focuses on analyzing tweet sentiment using classical NLP and machine learning techniques.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- Matplotlib

---

## 🔍 Workflow

1. Data Loading and Cleaning
2. Text Preprocessing  
   - Lowercasing  
   - Tokenization  
   - Stopword removal  
   - POS tagging  
   - Lemmatization  
3. Feature Extraction  
   - Count Vectorization  
   - TF-IDF Vectorization  
4. Model Training  
   - Logistic Regression  
5. Model Evaluation  
   - Accuracy  
   - Classification Report  
   - Confusion Matrix  
6. Comparison of Count Vectorizer vs TF-IDF

---

## 📊 Results Summary

| Feature Extraction | Accuracy |
|--------------------|----------|
| Count Vectorizer   | ~XX%     |
| TF-IDF Vectorizer  | ~XX%     |

TF-IDF performed better by reducing the influence of frequent but less informative words.

---

## 📈 Confusion Matrix

Confusion matrices are used to visualize the classification performance for each sentiment class.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
