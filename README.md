# 🧠 Twitter Sentiment Analysis using Machine Learning

This project performs **Sentiment Analysis on Tweets** to classify them into **Positive** and **Negative** categories using Machine Learning techniques.  
A real-world Twitter dataset with 1.6 million tweets is used to train and evaluate sentiment classification models.

---

## 🚀 Features
- Large dataset with real tweets
- Text preprocessing (cleaning + normalization)
- TF-IDF Vectorization
- Machine learning model training and evaluation
- Sentiment visualization
- Classification performance results

---

## 📂 Dataset
Dataset used: **Sentiment140 (training.1600000.processed.noemoticon.csv)**

| Column | Description |
|--------|-------------|
| `sentiment` | 0 = Negative, 4 = Positive |
| `text` | Actual tweet text |

---

## 🧼 Data Preprocessing Steps
- Text cleanup (remove URLs, mentions, hashtags)
- Remove numbers, punctuation, and extra spaces
- Convert text to lowercase
- Remove stopwords
- Tokenization & TF-IDF vectorization

---

## 🧠 Machine Learning Models
| Model | Description |
|-------|-------------|
| **Multinomial Naive Bayes** | Fast probabilistic classifier for text |
| **Logistic Regression** | Linear model for binary sentiment classification |

Evaluation Metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

