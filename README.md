# 🎬 Movie Correlation Analysis using Python

This project explores how different factors influence a movie’s box office performance using Python-based data analysis. The goal is to uncover **hidden relationships between budget, revenue, audience engagement, and other features** through data cleaning, visualization, and statistical correlation.

---

## 📊 Project Overview

The dataset consists of movies with attributes such as:

* Budget & Gross earnings
* Ratings and votes
* Genre, director, and cast
* Release dates and runtime

The analysis focuses on identifying **which variables most strongly impact a movie’s financial success**.

---

## 🧹 Data Cleaning & Preparation

* Handled missing values across multiple columns
* Converted data types (e.g., budget and gross to numeric formats)
* Extracted meaningful features (e.g., **year from release date using regex**)
* Removed duplicates and standardized the dataset

---

## 📈 Exploratory Data Analysis (EDA)

* Analyzed missing data distribution
* Sorted and inspected high-grossing films
* Created new scaled features (e.g., budget & gross in millions)
* Visualized relationships using scatter plots and regression lines

---

## 📉 Correlation Analysis

Multiple correlation methods were used:

* **Pearson** (linear relationships)
* **Spearman** (monotonic relationships)
* **Kendall** (rank-based correlation)

### 🔍 Key Insight

* Strong correlation between **budget and gross earnings (~0.7+)**
* Indicates higher budgets generally lead to higher revenue,
  but not perfectly — suggesting **outliers like flops and sleeper hits**

---

## 📊 Visualizations

* Scatter plots (Budget vs Gross)
* Regression plots (trend analysis)
* Heatmaps (feature correlation matrix)

These visualizations help reveal both **linear trends and hidden patterns** in the data.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Matplotlib & Seaborn** – data visualization

---

## 🚀 Conclusion

This analysis highlights that while **budget is a strong driver of revenue**, it is not the only factor. Audience engagement (votes) and other hidden variables also play a role, making movie success **partially predictable but not guaranteed**.

---

## ⭐ Key Takeaway

> Big budgets increase the chances of success — but they don’t guarantee it.

---

Feel free to explore the notebook, fork the repo, or build on top of this analysis.
