# 🚢 Titanic Survival Prediction - Machine Learning Project

## 📚 Project Description
A machine learning project that predicts survival of passengers on the Titanic disaster using supervised learning algorithms. It covers data exploration, feature engineering, model building, and evaluation.

## 📌 Problem Statement
This project uses the Titanic dataset to predict whether a passenger survived or not based on features like age, sex, ticket class, etc.

## 📊 Dataset
- Source: Kaggle Titanic Dataset (https://www.kaggle.com/c/titanic)
- Features: Pclass, Sex, Age, Fare, Embarked, etc.
- Target: Survived (0 = No, 1 = Yes)

## 📂 Project Structure
titanic-survival-prediction/

│

├── README.md

├── titanic_model.ipynb

├── data/

│   └── train.csv

├── images/

│   └── (plots and graphs will be saved here later)

└── requirements.txt (optional - list of Python libraries)

## 📊 Methods Used
- Exploratory Data Analysis (EDA)
- Feature Engineering (Title extraction, encoding, etc.)
- Data Cleaning
- Machine Learning Modeling
- Model Evaluation: accuracy, precision, recall, F1-score

## 🛠️ Technologies Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn (for visualizations)
- Scikit-Learn (for ML algorithms)

## 🚀 How to Run
1. Clone this repository.
2. Install requirements using:
  pip install -r requirements.txt
3. Open the titanic_model.ipynb notebook.
4. Run all cells to see the results.

## 📈 Results
| Model | Accuracy |
|:------|:---------|
| Logistic Regression | 79.88% |
| Random Forest | 83.79% |
- **Precision / Recall / F1-score**: Balanced performance across classes

The Random Forest model outperformed Logistic Regression by capturing complex patterns in the data. Its ensemble nature makes it more robust and suitable for production use in similar classification problems.

## 🛠️ Future Work
- Try advanced ensemble models like LightGBM or XGBoost
- Perform hyperparameter tuning
- Use cross-validation for more reliable performance
- Build a small web app using Streamlit

## 🙌 Author
Ankit Tiwari (https://github.com/ankitis32)

