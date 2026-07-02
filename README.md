# 💳 Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using **Logistic Regression**. Since fraud cases are extremely rare compared to legitimate transactions, the dataset is highly imbalanced. To address this, the project creates a balanced dataset by randomly undersampling legitimate transactions before training the model. The trained classifier predicts whether a transaction is genuine or fraudulent, providing a simple yet effective baseline for fraud detection.

## 🧠 How It Works

The model follows a straightforward machine learning pipeline:

1. **Data Loading & Exploration** — loads the transaction dataset and analyzes its structure and class distribution.
2. **Data Balancing** — performs random undersampling to create an equal number of legitimate and fraudulent transactions.
3. **Train-Test Split** — divides the balanced dataset into training and testing sets.
4. **Logistic Regression** — trains a binary classification model to distinguish fraudulent transactions.
5. **Model Evaluation** — measures performance using accuracy on both training and test datasets.

## 🛠️ Tech Stack

Python · Pandas · NumPy · Scikit-learn · Jupyter Notebook

## 🚧 Known Limitations

* Random undersampling discards a large portion of legitimate transaction data.
* Accuracy alone is insufficient for evaluating fraud detection due to class imbalance.
* Future improvements include using SMOTE, ensemble models, and precision-recall metrics for more reliable performance.

## 👤 Author

**Ahad Ahmad**

- GitHub: [https://github.com/AhadAhmad0](url)

