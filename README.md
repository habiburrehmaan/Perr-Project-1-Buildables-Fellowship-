Credit Card Fraud Detection
📌 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The dataset is highly imbalanced, as fraudulent transactions are much rarer compared to legitimate ones. The aim is to build a model that can accurately identify fraudulent activity while minimizing false positives.

📂 Project Structure
├── credit-card-fraud-detection.ipynb   # Main Jupyter Notebook
├── README.md                           # Project Documentation
├── requirements.txt                    # Dependencies (to be added)
└── data/                               # Dataset (not included here)

📊 Dataset

Source: Commonly from Kaggle - Credit Card Fraud Detection Dataset
.

Size: 284,807 transactions with 492 fraud cases (highly imbalanced).

Features: 30 features (including anonymized PCA components + Time & Amount).

Target: Class (0 = Legitimate, 1 = Fraud).

⚙️ Methodology

Data Preprocessing

Handle imbalance using undersampling/oversampling (SMOTE, ADASYN).

Feature scaling (StandardScaler/MinMaxScaler).

Train-test split.

Model Training

Machine Learning models: Logistic Regression, Decision Tree, Random Forest, XGBoost, etc.

Deep Learning approach (optional): Simple Neural Network.

Evaluation Metrics

Accuracy is misleading → Use:

Precision, Recall, F1-Score

ROC-AUC curve

Confusion Matrix

🚀 Installation & Usage

Clone the repository:

git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook credit-card-fraud-detection.ipynb

📈 Results

Models are evaluated on recall and precision due to the importance of correctly identifying fraud.

Example (to be updated):

Logistic Regression: 92% Recall, 95% Precision

Random Forest: 96% Recall, 98% Precision
