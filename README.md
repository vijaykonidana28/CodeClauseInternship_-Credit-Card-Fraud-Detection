
# 💳 Credit Card Fraud Detection (Advanced)

This project focuses on detecting fraudulent credit card transactions using advanced machine learning techniques.

## 🚀 Aim
To detect fraudulent credit card transactions using robust classification algorithms and handle real-world data imbalance effectively.

## 📝 Description
- Applies advanced classification techniques (XGBoost)
- Handles highly imbalanced datasets using SMOTE
- Evaluates performance with multiple metrics and ROC-AUC curve

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- imbalanced-learn
- XGBoost
- Google Colab

## 📂 Dataset
- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The dataset contains anonymized features (V1–V28), `Amount`, `Time`, and `Class` (fraud = 1, not fraud = 0).

## ⚙️ How to Run
1. Open the notebook in Google Colab.
2. Upload the `creditcard.csv` dataset when prompted.
3. Run the cells in order to preprocess, train, and evaluate the model.

## 📈 Model Used
- **XGBoost Classifier** with hyperparameters for performance and efficiency.
- SMOTE for handling class imbalance in the target variable.

## 📊 Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC-AUC Score
- ROC Curve Visualization

## 🎓 What You Learn
- How to detect anomalies in transactional datasets
- Applying SMOTE for class balancing
- Using XGBoost for classification
- Performance evaluation of imbalanced classification models

## 👨‍💻 Internship Provider
This project was completed as part of an internship at **CodeClause**.

---

### 📎 License
This project is for educational purposes only. Dataset is available publicly from Kaggle under their terms of use.
