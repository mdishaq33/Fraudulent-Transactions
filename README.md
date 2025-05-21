# Fraudulent-Transactions
# 💳 Credit Card Fraud Detection Project

This project uses machine learning to detect fraudulent credit card transactions. It is trained on an imbalanced dataset and uses various techniques to improve model performance.

## 📊 Dataset
- Based on anonymized credit card transactions (Kaggle dataset).
- Contains normal and fraudulent transaction records.
- Highly imbalanced: frauds are very rare.

## 🧠 What’s Done
- Exploratory Data Analysis (EDA)
- Feature scaling & preprocessing
- Resampling to balance classes
- Model training (Logistic Regression, Random Forest)
- Model evaluation using metrics like Accuracy, Precision, ROC-AUC

## 🛠️ Technologies Used
- Python
- NumPy, pandas.
- scikit-learn
- matplotlib, seaborn
- imblearn (for SMOTE)

## 🧪 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/mdishaq33/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
Install dependencies:
pip install -r requirements.txt
Run the notebook:
Open Credit_Card_Fraud_Detection.ipynb in Jupyter Notebook or Colab.

📈 Results
High accuracy with balanced precision/recall

ROC-AUC score to evaluate model effectiveness.
