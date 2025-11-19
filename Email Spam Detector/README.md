# 📧 Email Spam Detector
### Machine Learning-Based Spam Classification

An end-to-end machine learning project that classifies emails as Spam or Not Spam using traditional NLP preprocessing and ML algorithms.
This project focuses on clarity, simplicity, and learning the fundamentals of text classification.

# 🚀 Project Overview

The Email Spam Detector is a supervised machine learning model trained on a labeled dataset of emails.
It transforms raw email text into numerical feature vectors using TF-IDF Vectorization, then trains a classifier to distinguish between spam and ham (non-spam).

This project is perfect for beginners to understand how machine learning is used in real-world text classification tasks.

# 🧠 Key Features

#### ✔️ Text preprocessing (cleaning, tokenization, stopword removal)

#### ✔️ TF-IDF vectorization for feature extraction

#### ✔️ ML model trained for spam classification

#### ✔️ Evaluation using accuracy, confusion matrix, and classification report

#### ✔️ Saved model & vectorizer using .pkl (optional)

# 📂 Project Structure
Email-Spam-Detector/
│
├── data/
│   └── spam.csv
│
├── notebooks/
│   └── spam_classifier.ipynb
│
├── models/
│   ├── tfidf_vectorizer.pkl     
│   └── spam_model.pkl           
│
├── README.md
└── requirements.txt (optional)

# 🛠️ Technologies Used

- Python

- NumPy

- Pandas

- Scikit-learn

- TF-IDF Vectorizer

- Train–test split

- Naive Bayes / Logistic Regression 

# 🔍 How It Works
## 1️⃣ Load Dataset

You use a spam dataset containing labeled examples of spam and ham emails.

## 2️⃣ Clean Text

Lowercasing, removing punctuation, removing numbers, removing special characters, etc.

## 3️⃣ Extract Features

Transform emails into numerical vectors using TfidfVectorizer.

## 4️⃣ Train Model

- Naive Bayes

- Logistic Regression

- SVM

## 5️⃣ Evaluate

- Accuracy

- Classification Report

- Confusion Matrix

## 6️⃣ Save Model 

- tfidf_vectorizer.pkl

- spam_model.pkl

If you want deployment later, saving is useful.
If not, you can skip saving these files.

# 📊 Model Performance

- **Accuracy:** 97.30%

## ▶️ How to Run

1. Clone the repository
   
```bash
git clone https://github.com/yourusername/Email-Spam-Detector.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook
   
```bash
jupyter notebook
