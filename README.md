# 🎬 Netflix Data Analysis & Visualization

## 📌 Project Overview

This project explores and analyzes Netflix’s content catalog to uncover insights about movies and TV shows, including trends in content type, release patterns, ratings, and geographic distribution. The goal is to transform raw data into meaningful visual insights using Python.

---

## 📂 Dataset

* Source: Kaggle – *Netflix Movies and TV Shows Dataset*
* Key features:

  * `title` – Name of the content
  * `type` – Movie or TV Show
  * `director` – Director of the content
  * `cast` – Actors involved
  * `country` – Country of production
  * `date_added` – Date added to Netflix
  * `release_year` – Year of release
  * `rating` – Content rating (PG, TV-MA, etc.)
  * `duration` – Length (minutes or seasons)
  * `listed_in` – Genre/category

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas – Data cleaning & manipulation
* NumPy – Numerical computations
* Matplotlib & Seaborn – Static visualizations
* Plotly – Interactive visualizations

---

## 🔍 Workflow

### 1. Data Loading & Inspection

* Imported dataset using Pandas
* Explored structure with `.info()`, `.describe()`
* Checked for missing values and inconsistencies

### 2. Data Cleaning

* Handled null values
* Converted `date_added` to datetime format
* Standardized categorical data for consistency

### 3. Exploratory Data Analysis (EDA)

* Distribution of Movies vs TV Shows
* Year-wise content addition trends
* Most frequent content ratings
* Country-wise content production
* Genre distribution analysis

### 4. Data Visualization

* Bar charts for content distribution
* Pie charts for type comparison
* Heatmaps for correlations
* Time-series plots for yearly trends
* Interactive charts using Plotly

---

## 📊 Key Insights

* Netflix has a higher proportion of **movies compared to TV shows**
* Significant growth in content addition after 2015
* Certain countries dominate content production
* Popular genres and ratings reflect audience preferences
* Seasonal trends observed in content releases

---

## 📈 Visualizations Included

* Distribution plots
* Count plots
* Pie charts
* Heatmaps
* Interactive dashboards (Plotly)

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
   ```

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```

3. Open the notebook:

   * Jupyter Notebook / Jupyter Lab / VS Code
   * Run all cells

---

## ⚠️ Notes

* Dataset not included due to GitHub size limits
* Download from Kaggle and update file path:

  ```python
  df = pd.read_csv("path_to_dataset.csv")
  ```

---

## 💡 Future Enhancements

* Build a recommendation system 🎯
* Perform sentiment analysis on descriptions
* Deploy interactive dashboard (Streamlit / Power BI)
* Add machine learning models for predictions

---

## 👤 Author

**Shirisha Jasthi**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
