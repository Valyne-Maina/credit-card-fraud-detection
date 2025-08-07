# 💳 Credit Card Fraud Detection Project

This project aims to detect fraudulent credit card transactions using machine learning techniques.  
It includes data preprocessing, exploratory data analysis, model training, evaluation, and saving the models for later use.

---

## 📁 Project Overview

Credit card fraud is a serious issue in financial systems.  
In this project, we use a real-world dataset of credit card transactions and build two different models:

- **Isolation Forest** (unsupervised learning)  
- **Random Forest Classifier** (supervised learning)

---

## 📌 Key Features

- Exploratory Data Analysis (EDA)  
- Class imbalance handling  
- Feature scaling  
- Model training & evaluation  
- Visualization of performance metrics  
- Saving trained models using `joblib`

---

## 🧰 Libraries Used

- `pandas`: Data manipulation & analysis  
- `numpy`: Numerical operations  
- `matplotlib` & `seaborn`: Data visualization  
- `scikit-learn`: Machine learning models & evaluation  
- `joblib`: Saving and loading models  
- `collections`: Counting elements

---

## 🗂️ Project Structure by Week

### Week 1: Project Setup & Data Import  
- Installed libraries  
- Loaded dataset using `pandas`  
- Displayed basic info  

### Week 2: Data Exploration & Visualization  
- Checked dataset shape and class imbalance  
- Visualized fraud vs. non-fraud transactions  
- Analyzed correlations  

### Week 3: Data Preprocessing  
- Removed irrelevant columns  
- Applied `StandardScaler`  
- Split data into train/test sets  

### Week 4: Modeling  
- Built Isolation Forest and Random Forest models  
- Calculated accuracy, recall, precision, and F1-score  
- Compared model results  

### Week 5: Model Saving  
- Saved trained models using `joblib`

---

## 📊 Results

- **Isolation Forest**: Detected anomalies without labels  
- **Random Forest**: High accuracy and recall  
- **Conclusion**: Random Forest performed better overall

---

## 🚀 How to Run the Project

1. Clone the repo or download the notebook  
2. Install required libraries  
3. Open in Jupyter Notebook or VS Code  
4. Run the cells step-by-step

---

## 📦 Requirements

```bash
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
joblib
```

---

## 🧠 Future Improvements

- Use SMOTE for better class balance  
- Experiment with deep learning models  
- Deploy the best model as a web application

---

## 👩‍💻 Author

**Valyne Maina**  
_Data Science & Analytics Student | Virtual Assistant_

---

## 📜 License

This project is open-source and free to use under the **MIT License**.
