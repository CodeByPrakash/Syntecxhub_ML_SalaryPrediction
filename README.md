# 💰 Salary Prediction System
### Machine Learning Internship — Project 2 | Syntecxhub

> An end-to-end Machine Learning project that predicts salaries based on features like years of experience, education level, and job role using **Linear Regression**.

---

## 📌 Project Overview

This project was built as part of the **Syntecxhub Machine Learning Internship (Project 2)**. The goal is to develop a salary prediction model that can estimate a person's salary given relevant features — a practical application of supervised learning in the HR and recruitment domain.

---

## 🧰 Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning & manipulation |
| `numpy` | Numerical computations |
| `scikit-learn` | Model building & evaluation |
| `matplotlib` | Data & result visualization |
| `seaborn` | Exploratory Data Analysis (EDA) |

---

## 🔄 Workflow

```
Raw Data → Data Cleaning → EDA → Feature Engineering → Model Training → Evaluation → Prediction
```

1. **Data Collection** — Loaded salary dataset using Pandas
2. **Data Preprocessing** — Handled missing values, encoded categorical variables, removed outliers
3. **EDA** — Visualized distributions, correlations, and feature relationships using Matplotlib & Seaborn
4. **Model Training** — Trained a Linear Regression model using Scikit-learn
5. **Evaluation** — Assessed model performance using R² Score, MAE, and MSE
6. **Visualization** — Plotted Actual vs Predicted salary for validation

---

## 📈 Sample Visualizations

- Correlation heatmap of features
- Distribution of salaries across experience levels
- Scatter plot: Actual vs Predicted Salary
- Residual plot for error analysis

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/CodeByPrakash/salary-prediction-system.git
cd salary-prediction-system
```

### 2. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3. Run the notebook

```bash
jupyter notebook notebooks/salary_prediction.ipynb
```

---

## 💡 Key Learnings

- Linear Regression is highly effective for structured numerical prediction when features are properly engineered
- EDA is critical — data quality directly impacts model accuracy
- Feature correlation analysis helps identify the most impactful predictors
- Visualizing residuals is a powerful way to diagnose model limitations

---

## 🏢 Internship Details

| | |
|---|---|
| **Organization** | Syntecxhub |
| **Program** | Machine Learning Internship |
| **Project** | Project 2 — Salary Prediction System |
| **Intern** | Omprakash Behera |
| **GitHub** | [@CodeByPrakash](https://github.com/CodeByPrakash) |

---

## 📄 License

This project is for educational and internship purposes under Syntecxhub.

---

<p align="center">Built with 🤍 during the Syntecxhub ML Internship</p>
