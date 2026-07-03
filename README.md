# 💳 Credit Card Fraud Detection

A machine learning-based credit card fraud detection system that classifies transactions as legitimate or fraudulent using transaction features. The project demonstrates the complete ML workflow, from data preprocessing and model training to evaluation and prediction.

## 🔴 Project Overview

This project aims to identify fraudulent credit card transactions by analyzing transaction data and learning patterns associated with fraud. The dataset contains **984 transactions** with **30 features**, which were split into **787 training samples** and **197 testing samples**. The trained model achieved **94.28% training accuracy** and **91.88% testing accuracy**, indicating strong performance on unseen data.

## 🧠 How It Works

The fraud detection pipeline follows these steps:

1. **Data Preprocessing** – Cleaning the dataset and handling missing values.
2. **Feature Engineering** – Preparing transaction features for model training.
3. **Train-Test Split** – Dividing the dataset into training and testing sets.
4. **Model Training** – Training a machine learning classifier to detect fraudulent transactions.
5. **Model Evaluation** – Measuring performance using accuracy on both training and testing datasets.

## 🛠️ Tech Stack

Python · NumPy · Pandas · Scikit-learn · Matplotlib · Seaborn · Jupyter Notebook

## 📁 Repository Structure

```text
├── notebook/                  # Model training notebook
├── dataset/                   # Credit card transaction dataset
├── Credit_Card_Fraud_Detection.ipynb
├── requirements.txt
└── README.md
```

## 📊 Results

- **Dataset Size:** 984 Transactions
- **Features:** 30
- **Training Samples:** 787
- **Testing Samples:** 197
- **Training Accuracy:** **94.28%**
- **Testing Accuracy:** **91.88%**

## 🚀 Future Improvements

- Evaluate additional metrics such as Precision, Recall, F1-Score, and ROC-AUC.
- Address class imbalance using techniques like SMOTE or undersampling.
- Compare multiple machine learning algorithms and ensemble methods.
- Deploy the model as an interactive web application using Flask or Streamlit.

## 👤 Author

**Ahad Ahmad**

- GitHub: [@AhadAhmad0](https://github.com/AhadAhmad0)
