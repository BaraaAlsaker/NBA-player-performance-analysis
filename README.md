# 🏀 NBA Player Performance Analysis

🚀 End-to-end machine learning project analyzing NBA player performance using regression, clustering, and classification.

---

## 📌 Project Overview

This project explores NBA player performance using game-by-game statistics from the 2024–2025 season.
The goal is to understand player behavior, identify playing styles, and analyze how individual performance relates to team success.

The project follows a complete machine learning pipeline:

* Data cleaning & preprocessing
* Feature engineering
* Model training & evaluation
* Insight extraction

---

## 🎯 Objectives

* Predict player scoring performance (Regression)
* Identify player playing styles (Clustering)
* Predict game outcomes (Classification)

---

## 🧠 Machine Learning Tasks

### 1. Regression – Predicting Points (PTS)

* Models:

  * Linear Regression
  * Random Forest
  * Support Vector Regression (SVR)

📊 **Best Model:** SVR (best generalization performance)

---

### 2. Clustering – Player Style Analysis

* Models:

  * K-Means
  * Hierarchical Clustering

📌 Players naturally separate into:

* **Low-usage / Role Players**
* **High-usage / Primary Players**

📊 Optimal number of clusters selected using Silhouette Score.

---

### 3. Classification – Game Outcome Prediction

* Models:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine (SVM)

📊 **Best Model:** Logistic Regression (highest ROC-AUC)

---

## 📊 Key Insights

* Minutes played is the strongest predictor of performance
* Simpler models often generalize better than complex ones
* Player-level statistics alone are not enough to predict game outcomes accurately
* Basketball performance is highly variable and context-dependent

---

## 📁 Project Structure

```bash
data/        # Raw and cleaned datasets
notebooks/   # ML models and analysis
results/     # Clustering outputs
```

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib
* SciPy

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/BaraaAlsaker/NBA-player-performance-analysis.git
cd nba-player-performance-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn scipy
```

### 3. Run the notebooks

Open Jupyter Notebook or VS Code and run the notebooks in this order:

1. `notebooks/regression.ipynb`
2. `notebooks/clustering.ipynb`
3. `notebooks/classification.ipynb`

---

## 📌 Notes

* The dataset is included in the `data/` folder
* Each notebook is independent and can be run separately
* Results such as clustering outputs are saved in the `results/` folder

---

## 👨‍💻 Author

**Baraa Alsaker**
AI Student | Machine Learning Developer

---

## ⭐ About This Project

This project was originally developed as part of an AI course and later refined into a professional portfolio project.
