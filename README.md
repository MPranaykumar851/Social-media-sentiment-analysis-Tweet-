
---

## 🔍 Data Preprocessing
The following preprocessing steps were applied:
- Text cleaning (lowercasing, punctuation removal)
- Tokenization
- Stopword removal
- POS tagging
- Lemmatization using WordNet
- Rare word analysis

---

## 📊 Exploratory Data Analysis (EDA)
The EDA phase includes:
- Class distribution analysis
- Word frequency analysis
- Rare vs frequent word identification
- Histogram of cumulative word frequencies
- Long-tail distribution analysis (Zipf’s Law)
- Outlier detection (very short and very long tweets)

---

## 🔑 Feature Extraction
Two feature extraction techniques were implemented and compared:

### 1️⃣ Count Vectorization
- Converts text into a sparse matrix of word counts
- Captures raw frequency information

### 2️⃣ TF-IDF Vectorization
- Weighs words based on importance
- Reduces the impact of common words
- Improves generalization

---

## 🤖 Model Training
- **Algorithm Used:** Logistic Regression
- **Reason:** Efficient baseline model for text classification
- Trained separately using:
  - Count Vectorizer features
  - TF-IDF features

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix (visualized using Matplotlib)

### Comparison Performed:
- Count Vectorizer vs TF-IDF
- Per-class performance analysis
- Misclassification trends across sentiments

---

## 🧪 Results Summary
- TF-IDF outperformed Count Vectorization
- Neutral sentiment showed higher confusion with other classes
- Logistic Regression handled noisy social media text reasonably well
- Class imbalance impacted recall for minority classes

---

## ⚠️ Limitations
- Sensitive to sarcasm and slang
- Cannot capture context or word order
- Performance depends heavily on preprocessing quality

---

## 🚀 Future Improvements
- Use advanced models (Naive Bayes, SVM)
- Apply deep learning models (LSTM, Transformers)
- Handle sarcasm and emojis
- Use word embeddings (Word2Vec, GloVe, BERT)

---

## 📌 Conclusion
This project demonstrates an end-to-end **NLP pipeline** for sentiment analysis, covering:
- Data preprocessing
- Exploratory analysis
- Feature extraction
- Model training
- Evaluation and comparison

It provides a strong baseline system and a foundation for more advanced sentiment analysis research.

---

## 👨‍💻 Author
**Pranay**  
Computer Science Undergraduate  
Interest Areas: Machine Learning, NLP, Data Science
