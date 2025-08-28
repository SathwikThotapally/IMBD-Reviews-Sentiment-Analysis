# IMDB Reviews Sentiment Analysis

## 📖 Project Overview

This project focuses on **sentiment analysis** of IMDB movie reviews, aiming to classify reviews as **positive** or **negative**. The project demonstrates a complete machine learning workflow for text classification, including **text preprocessing, feature extraction, model training, evaluation, and comparison**.

---

## 🗂 Dataset

- The dataset consists of **IMDB movie reviews** labeled as positive or negative.
- Each review is a piece of raw text.
- The target variable is `sentiment` (positive/negative).

---

## ✨ Text Preprocessing

Text data was preprocessed using **NLTK** and Python libraries. Key steps include:

- **Tokenization** – Splitting text into individual words.  
- **Lowercasing** – Converting all text to lowercase.  
- **Stopwords Removal** – Removing common words that do not contribute to sentiment.  
- **Lemmatization** – Reducing words to their base form (e.g., “running” → “run”).  

These steps ensure that the model focuses on meaningful features and reduces noise in the data.

---

## 🛠 Feature Extraction

- **TF-IDF Vectorization** was used to convert text into numerical features.  
- TF-IDF captures the importance of words in a document relative to the entire corpus.  
- Parameters like **n-grams** and **maximum features** can be adjusted to improve performance.

---

## 🤖 Models Used

Three machine learning models were trained and evaluated:

1. **Logistic Regression** – A linear model suitable for high-dimensional, sparse text data.  
2. **Multinomial Naive Bayes** – A probabilistic model commonly used for text classification.  
3. **Random Forest Classifier** – An ensemble method capable of handling complex patterns in the data.

---

## 📊 Evaluation Metrics

Models were evaluated using:

- **Accuracy** – Overall correctness of predictions.  
- **Precision** – Correctness of positive predictions.  
- **Recall** – Ability to identify all positive samples.  
- **F1-score** – Balance between precision and recall.  

**Result Summary:**  
- Logistic Regression achieved the **highest accuracy and F1-score**, outperforming the other models.  
- Multinomial Naive Bayes performed well but slightly lower than Logistic Regression.  
- Random Forest, while capable, showed lower performance due to high-dimensional sparse features.

---

## 🏁 Conclusion

- Logistic Regression is the **best-performing model** for this problem, highlighting the effectiveness of linear models for sparse text data.  
- Naive Bayes remains competitive for text classification tasks.  
- Random Forest works but may require additional feature engineering or dimensionality reduction.  

**Future Improvements:**  
- Hyperparameter tuning for all models.  
- Experimenting with **n-grams** or **word embeddings** (e.g., Word2Vec, GloVe).  
- Exploring **deep learning models** like LSTM or BERT for better semantic understanding.  

---

👤 Author: Sathwik Thotapally
📧 Email: sathwikthotapally@gmail.com

