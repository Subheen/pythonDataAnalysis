# pythonDataAnalysis
Portfolio Purpose
# Customer Churn Prediction

## 📌 Overview
This project analyzes customer churn using machine learning techniques. The goal is to identify key factors contributing to customer churn and build a predictive model to help businesses retain customers.

## 📊 Dataset
- The dataset contains customer information, contract details, and payment methods.
- Key categorical and numerical features were analyzed.
- The target variable is `Churn` (0: No, 1: Yes).

## 🔍 Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing (handling missing values, encoding categorical features).
- Correlation analysis using heatmaps.
- Chi-square tests to check dependency of categorical variables on churn.
- Statistical analysis to identify patterns in numerical data.

### Key Findings:
✅ Higher churn among:
- Customers without partners or dependents.
- Month-to-month contract holders.
- Customers using electronic checks.
- Senior citizens.

## 📈 Model Building
### Logistic Regression
- Initial model trained to understand feature importance.
- Key predictors: Contract type, payment method, senior citizen status, monthly charges.

### Random Forest Classifier
- Improved model performance.
- Feature importance analysis showed `Contract Type` as the most significant predictor.

## 🏆 Results & Evaluation
- **Accuracy:** 80%
- **Precision & Recall:**
  - Churned customers (1): 68% precision, 48% recall.
  - Non-churned customers (0): 83% precision, 92% recall.
- The model effectively predicts churn but struggles with recall for actual churned customers.

## 🚀 Next Steps
- Tune hyperparameters for better recall.
- Try advanced models like XGBoost.
- Deploy as a web app for real-time predictions.

## 📂 Repository Structure
```
📁 Churn Prediction
 ├── 📜 Churn Prediction.ipynb  # Jupyter Notebook with full analysis
 ├── 📜 README.md               # Project documentation
 ├── 📊 data/                   # Dataset 
 ├── 📂 models/                 # Trained model files
 └── 📈 plots/                   # Visualizations
```

## 🛠️ Tech Stack
- Python (pandas, numpy, scikit-learn, seaborn, matplotlib)
- Machine Learning: Logistic Regression, Random Forest

## 👥 Contributors
- Sabheen Gull

## 📢 Feedback
Have suggestions? Feel free to open an issue or contribute!

---
🚀 **Star this repository if you found it helpful!** ⭐

