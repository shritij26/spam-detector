# 📱 SMS Spam Classifier (Logistic Regression)

This project is a **basic machine learning application** that detects whether a given SMS message is **spam or not spam** (ham) using **Logistic Regression**.

---

## 🧠 What I Learned

- **Data Preprocessing**
  - Handling missing values
  - Removing duplicates
  - Text normalization (lowercasing, punctuation removal, etc.)

- **Feature Extraction**
  - Tokenization
  - TF-IDF (Term Frequency–Inverse Document Frequency) vectorization

- **Data Splitting**
  - Train-Test split to evaluate model performance on unseen data

- **Model Training**
  - Logistic Regression for binary classification (spam vs. ham)
  - Use of scikit-learn's `LogisticRegression` model

- **Model Evaluation**
  - Accuracy score
  - Confusion matrix
  - Precision, recall, and F1-score
  - Classification report
    
- Saving & loading models using `joblib`

---

## 🛠️ What This Repository Contains

| File / Folder              | Description                                         |
|----------------------------|-----------------------------------------------------|
| `detection.ipynb`          | Jupyter Notebook with full project implementation   |
| `spam.csv`                 | Dataset of labeled SMS messages (spam or ham)       |
| `spam_classifier_model.pkl`| Trained Logistic Regression model                   |
| `tfidf_vectorizer.pkl`     | TF-IDF vectorizer used to transform input text      |
| `requirements.txt`         | Required Python libraries for running the project   |

---

## 💡 How to Use

1. Clone the repo
2. Install requirements:  
   ```bash
   pip install -r requirements.txt
