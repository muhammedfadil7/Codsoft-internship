# 🚢 Titanic Survival Prediction

## 📌 Project Overview

This project analyzes the famous Titanic dataset and builds machine learning models to predict whether a passenger survived or not. The notebook covers **data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling**.

## 📂 Dataset

* **Source:** [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
* **Key Columns:** PassengerId, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Survived
* **Target Variable:** `Survived` (0 = No, 1 = Yes)

## 🔑 Features of Analysis

1. **Data Preprocessing**

   * Handling missing values (Age, Cabin, Embarked)
   * Encoding categorical features (Sex, Embarked)
   * Feature scaling for numerical columns

2. **Exploratory Data Analysis (EDA)**

   * Survival distribution by gender, passenger class, and age
   * Correlation heatmap
   * Visualizations using `matplotlib` and `seaborn`

3. **Feature Engineering**

   * Creating new features such as Family Size, Title extraction from Name
   * Binning continuous features like Age and Fare

4. **Machine Learning Models**

   * Logistic Regression
   * Decision Tree Classifier
   * Random Forest Classifier
   * Support Vector Machine (SVM)
   * Model evaluation using accuracy, precision, recall, F1-score

## 📊 Results

* **Random Forest Classifier** and **Logistic Regression** achieved strong performance.
* Gender and passenger class were the most significant predictors of survival.
* Feature engineering improved model accuracy.

## ⚙️ Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/your-username/titanic-prediction.git
cd titanic-prediction
pip install -r requirements.txt
```

## ▶️ Usage

Run the Jupyter notebook:

```bash
jupyter notebook "titanic pred.ipynb"
```

## 📦 Dependencies

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

Install them with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📌 Future Improvements

* Apply hyperparameter tuning with GridSearchCV/RandomizedSearchCV
* Test ensemble models like XGBoost and Gradient Boosting
* Deploy as a web app using Streamlit or Flask

## 📝 Author

Developed by Muhammed fadil ✨

---

⭐ If you like this project, don’t forget to star the repo!
