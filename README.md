
# 🛡️ Credit Card Fraud Detection using Machine Learning

## 📌 Objective
This project aims to detect fraudulent credit card transactions using machine learning techniques. Given the rarity and hidden nature of fraud in large datasets, the project applies both **supervised** and **unsupervised** learning models to improve detection accuracy and reduce false positives.

## 🧩 Problem Statement
Credit card fraud detection is a critical issue for banks and financial institutions. The dataset is **highly imbalanced**, with very few fraudulent cases hidden within massive normal transaction data. Therefore, this is both a **classification** and **anomaly detection** challenge.

## 📊 Dataset Overview
The dataset includes:
- Features: `Time`, `V1` to `V28`, `Amount`
- Label: `Class` (0 = Legitimate, 1 = Fraud)

Sample (first 5 rows):
```
Time      V1      V2   ...  V28  Amount  Class
0.0  -1.36  -0.07  ... -0.02  149.62   0
0.0   1.19   0.26  ...  0.01    2.69   0
1.0  -1.35  -1.34  ... -0.05  378.66   0
```

## 🛠️ Methods Used
- **Data Preprocessing**: Scaling, handling imbalance
- **Unsupervised Learning**: Isolation Forest for anomaly detection
- **Supervised Learning**: Random Forest Classifier for fraud classification
- **Evaluation Metrics**: Confusion matrix, precision, recall, F1-score

## 🚀 How to Run

1. Clone the repo or download the notebook:  
```bash
git clone https://github.com/your-username/creditcard-fraud-detection.git
```

2. Install required libraries:  
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:  
```bash
jupyter notebook creditcardFD.ipynb
```

## 📈 Model Performance
The project evaluates both models based on:
- Precision
- Recall (very important for fraud)
- F1-score
- Confusion matrix visualization

## 📁 Files Included
- `creditcardFD.ipynb`: Main notebook
- `creditcard.csv`: Input dataset (not included due to size/privacy)
- `README.md`: Project documentation

## 📬 Contact
For questions, reach out via:
- 📧 your.email@example.com
- 🌐 [Your LinkedIn/GitHub profile]
