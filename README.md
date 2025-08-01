# 📱 SMS Spam Classifier (Logistic Regression)

This project is a **basic machine learning application** that detects whether a given SMS message is **spam or not spam** (ham) using **Logistic Regression**.

---

## 🧠 What I Learned

- Concepts like:
  - Data preprocessing
  - Feature extraction (TF-IDF)
  - Train-test split
  - Model training with logistic regression
  - Evaluation (accuracy, confusion matrix, precision, recall)
- Saving & loading models using `joblib`

---

## 🛠️ What This Repository Contains

| File / Folder         | Description                                         |
|-----------------------|-----------------------------------------------------|
| `SMS_spam_model.ipynb`| Jupyter Notebook with full project implementation   |
| `spam.csv`            | Dataset of labeled SMS messages (spam or ham)      |
| `model.pkl`           | Trained logistic regression model                   |
| `vectorizer.pkl`      | TF-IDF vectorizer used to transform input text      |
| `requirements.txt`    | Required Python libraries for running the project   |

---

## 💡 How to Use

1. Clone the repo
2. Install requirements:  
   ```bash
   pip install -r requirements.txt
