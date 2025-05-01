## 📚 Project Description
This machine learning project predicts whether a customer will churn based on various customer demographics and service usage data. It includes data exploration, feature engineering, model building, and performance evaluation.

## 📌 Problem Statement
Customer churn is a key business problem for telecom companies. This project uses the Telco Customer Churn dataset to predict whether a customer is likely to leave the company, helping stakeholders take proactive actions to improve retention.

## 📊 Dataset
- **Source**: IBM Sample Dataset (Telco Customer Churn)
- **Features**: gender, SeniorCitizen, tenure, Contract, MonthlyCharges, etc.
- **Target**: `Churn` (Yes = 1, No = 0)

## 📂 Project Structure
telco-churn-prediction/
├── telco_model.ipynb
├── Telco-Customer-Churn.csv
├── README.md
└── .gitignore (optional)


## ⚙️ Methods Used
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering (e.g., encoding categorical features)
- Model Building: Logistic Regression, Random Forest
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Feature Importance Analysis

## 📊 Exploratory Data Analysis
- Dataset contains 7043 entries and 21 columns.
- Churn rate is imbalanced: ~73% No, ~27% Yes.
- Issues like missing or incorrectly formatted `TotalCharges` were fixed.
- No duplicate records found.

## 🧹 Data Cleaning & Preprocessing
- Removed rows with missing or blank `TotalCharges`.
- Applied one-hot encoding for categorical variables.
- Converted `Churn` column to binary (Yes → 1, No → 0).
- Stratified train-test split for balanced class distribution.

## 🧠 Model 1: Logistic Regression
- Used default Scikit-Learn logistic regression model.
- Evaluated with accuracy and classification metrics.
- Solid baseline model with decent precision and recall.

## 🌲 Model 2: Random Forest
- Trained with 100 estimators, random state set for reproducibility.
- Solid overall accuracy and F1-score.
- Provided feature importance for business insight.

## ✅ Final Thoughts
- **Best Accuracy**: 84% using Logistic Regression
- **Top Features**: MonthlyCharges, tenure, Contract_Two year, OnlineSecurity, etc.
- **Business Insight**: Customers with high monthly bills, low tenure, and short contracts are more likely to churn.

## 🛠️ Technologies Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for machine learning)

## 🚀 How to Run
1. Clone this repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open telco_model.ipynb in Jupyter Notebook.
4. Run all cells sequentially to reproduce results.

## 📈 Results
| Model | Accuracy |
|:------|:---------|
| Logistic Regression | 80.38% |
| Random Forest | 78.53% |
- **Precision / Recall / F1-score**: Balanced performance across classes

## 🛠️ Future Work
- Try advanced ensemble models like LightGBM or XGBoost
- Hyperparameter tuning using GridSearchCV
- Add cross-validation for robustness
- Deploy using Streamlit or Flask web app

## 🙌 Author
Ankit Tiwari (https://github.com/ankitis32)

