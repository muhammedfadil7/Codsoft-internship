# 🎬 Movie Rating Analysis

## 📌 Project Overview

This project analyzes Indian movie data from IMDb to uncover insights about ratings, votes, and trends across different years. The notebook includes **data cleaning, preprocessing, visualization, and machine learning models** to evaluate and predict movie ratings.

## 📂 Dataset

* **Source:** IMDb Movies India dataset (`IMDb_Movies_India.csv`)
* **Key Columns:** Title, Year, Duration, Genre, Rating, Votes, Director, Cast
* **Cleaning Performed:**

  * Replaced missing/invalid values
  * Removed/handled outliers in `Duration`, `Rating`, and `Votes`
  * Converted data types for proper analysis

## 🔑 Features of Analysis

1. **Data Preprocessing**

   * Handling null values
   * Encoding categorical features
   * Outlier detection and treatment

2. **Exploratory Data Analysis (EDA)**

   * Year-wise movie releases
   * Rating distribution
   * Correlation heatmap
   * Visualization of top-rated movies and trends

3. **Key Insights**

   * 📈 Most movies were released in **2019 (410 movies)**
   * ⭐ Year **2019** had the highest number of hits (102 movies)
   * 🎥 Around **70% of 2019 movies were average**, **24% were hits**, and **4% below average**

4. **Machine Learning Models**

   * **Decision Tree Regressor**
   * **Random Forest Regressor**
   * **Support Vector Regressor (SVR)**
   * Evaluation metrics: MAE, MSE, R² Score

## ⚙️ Installation

Clone the repository and install required dependencies:

```bash
git clone https://github.com/your-username/movie-rating-analysis.git
cd movie-rating-analysis
pip install -r requirements.txt
```

## ▶️ Usage

Run the Jupyter notebook to explore the analysis:

```bash
jupyter notebook "movie rating analysis (1).ipynb"
```

## 📊 Results

* **Random Forest Regressor** gave the best performance with:

  * MAE ≈ 0.51
  * MSE ≈ 0.84
  * R² ≈ 0.13
* **Decision Tree Regressor** performed moderately
* **SVR** underperformed (R² close to 0)

## 📦 Dependencies

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn



## 📌 Future Improvements

* Use deep learning models (e.g., Neural Networks)
* Hyperparameter tuning for regressors
* Include additional features like audience reviews sentiment

## 📝 Author

Developed by Muhammed fadil ✨

---

⭐ If you like this project, don’t forget to star the repo!

