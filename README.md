# 👔 Task 2 — Employee Attrition Prediction

<p align="center">
  <img src="https://img.shields.io/badge/Internship-CodTech-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Task-2%20of%204-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Data%20Science-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8%2B-yellow?style=for-the-badge&logo=python" />
</p>

---

## 📌 Overview

A comprehensive analysis of **IBM's HR Analytics dataset** to identify the key factors driving employee attrition and build a machine learning model to predict which employees are at risk of leaving the company.

> **Intern:** Rahul Prasad  
> **Internship:** CodTech Data Science Internship  
> **Task:** 2 — HR Analytics & Attrition Prediction  

---

## 🎯 Objective

- Discover patterns and risk factors behind employee attrition
- Analyze departments, roles, income, satisfaction scores, and tenure
- Engineer meaningful HR-relevant features
- Build and evaluate a **Gradient Boosting Classifier** to predict attrition

---

## 📂 File Structure

```
📁 Task2-Employee-Attrition/
 └── Employee_Attrition_Prediction.ipynb   ← Main notebook (run top to bottom)
```

---

## 📊 Dataset

| Property    | Details                                                        |
|------------|----------------------------------------------------------------|
| Source      | IBM HR Analytics (auto-downloaded from GitHub)                |
| Rows        | 1,470 employee records                                         |
| Features    | 35 columns (age, department, income, satisfaction, etc.)      |
| Target      | `Attrition` — Yes (left) / No (stayed)                        |
| No download | Auto-loads on first run ✅                                     |

---

## 🔬 Notebook Structure

| Section | Description |
|---------|-------------|
| 1 | Import Libraries |
| 2 | Load Dataset (auto-downloads from GitHub) |
| 3 | Data Overview (types, stats, quality check) |
| 4 | Data Cleaning (drop constants, encode target) |
| 5 | Exploratory Data Analysis — 9 visualizations |
| 6 | Feature Engineering (age_bin, tenure_bin, avg_satisfaction, years_per_company) |
| 7 | Model Preparation & Stratified Split |
| 8 | Gradient Boosting Classifier (300 estimators) |
| 9 | Model Evaluation (Accuracy, ROC-AUC, Feature Importance) |
| 10 | Conclusions & Business Recommendations |

---

## 📈 Key Findings

| Factor | Finding |
|--------|---------|
| **OverTime** | Employees working overtime have ~3× higher attrition rate |
| **Job Role** | Sales Representatives have the highest attrition (~40%) |
| **Age** | Younger employees (18–25) leave at significantly higher rates |
| **Income** | Lower income groups show markedly higher attrition |
| **Tenure** | First 2 years are critical — new employees are most at risk |
| **Satisfaction** | Low job and environment satisfaction strongly predict attrition |

---

## 🤖 Model Performance

| Metric | Value |
|--------|-------|
| Algorithm | Gradient Boosting Classifier |
| Estimators | 300 |
| Test Accuracy | ~87–90% |
| 5-Fold CV Accuracy | ~87% |
| AUC Score | ~0.90+ |

---

## 💼 Business Recommendations

1. **Target overtime policies** — high-workload employees are the most at-risk group
2. **Focus retention on Sales Representatives** — the highest-attrition job role
3. **Invest in onboarding programs** — attrition peaks in the first 2 years
4. **Monitor low-satisfaction employees** — satisfaction scores are strong early signals
5. **Review compensation bands** — employees in lower income tiers leave at higher rates

---

## 🛠️ Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---

## ▶️ How to Run

```bash
# Option 1 — Jupyter Notebook
# Upload Employee_Attrition_Prediction.ipynb → Kernel → Restart & Run All

# Option 2 — Install dependencies if needed
pip install pandas numpy matplotlib seaborn scikit-learn
```

> ✅ Dataset auto-downloads from GitHub. Requires internet connection on first run.

---

## 📜 License

This project is part of the **CodTech Data Science Internship** program.

---

<p align="center">Made with ❤️ by <b>Rahul Prasad</b> | CodTech Internship 2024</p>
