# 🏥 Healthcare Big Data Analysis & Visualisation

A multi-disease healthcare analytics project analysing clinical datasets across three major conditions — **Diabetes**, **Heart Disease**, and **Kidney Disease** — using Python-based data analysis, visualisation, and machine learning.

Built as part of undergraduate research at Sharda University.

---

## 📊 Project Overview

This project applies exploratory data analysis (EDA), statistical visualisation, and predictive modelling to real-world clinical datasets to identify patterns, risk factors, and diagnostic indicators across three healthcare domains.

| Dataset | Records | Target Variable |
|---------|---------|----------------|
| Diabetes | 768 patients | Diabetic outcome (0/1) |
| Heart Disease | ~300 patients | Heart attack risk |
| Kidney Disease | ~400 patients | Kidney disease presence |

---

## 🔍 What's Inside

### 1. Diabetes Analysis (`/Diabetes`)
- Distribution analysis of clinical variables (Age, BMI, Glucose, Insulin, Blood Pressure)
- Correlation analysis between risk factors and diabetic outcomes
- Group-level comparisons (mean Age, Pregnancies by Outcome)
- ML models: Logistic Regression, KNN, SVM, Decision Tree, Random Forest, Gradient Boosting, Neural Network
- Model evaluation: Accuracy, ROC-AUC, Confusion Matrix, Classification Report
- Cross-validation with KFold and GridSearchCV hyperparameter tuning

### 2. Heart Disease Analysis (`/Heart`)
- Distribution plots across 13 clinical features
- Correlation heatmap identifying key risk factor relationships
- Variance and statistical summary analysis
- Visualisation of feature relationships with heart attack outcomes

### 3. Kidney Disease Analysis (`/Kidney`)
- Clinical feature exploration and data cleaning
- Pattern analysis across kidney disease indicators
- Visual summaries to support diagnostic insights

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computation |
| Matplotlib | Static visualisations |
| Seaborn | Statistical data visualisation |
| Scikit-learn | Machine learning models and evaluation |
| Statsmodels | Statistical analysis |
| Jupyter Notebook | Interactive development environment |

---

## 📁 Project Structure

```
healthcare-big-data-visualization/
│
├── Diabetes/
│   ├── Diabetes.csv
│   └── Diabetes_Github.ipynb
│
├── Heart/
│   ├── Heart.csv
│   └── Heart_Disease.ipynb
│
└── Kidney/
    ├── Kidney Disease.csv
    └── Kidney.ipynb
```

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

### Run the notebooks
```bash
git clone https://github.com/sohitkummar/healthcare-big-data-visualization.git
cd healthcare-big-data-visualization
jupyter notebook
```
Then open any of the three notebooks from the Diabetes, Heart, or Kidney folders.

---

## 📈 Key Findings

- **Diabetes:** Glucose level and BMI were the strongest predictors of diabetic outcome. Random Forest and Gradient Boosting achieved the highest classification accuracy.
- **Heart Disease:** Strong correlations identified between key cardiac markers. Heatmap analysis revealed multicollinearity patterns useful for feature selection.
- **Kidney Disease:** Visual analysis highlighted distinct clinical patterns between positive and negative cases across multiple biomarkers.

---

## 👤 Author

**Sohit Kummar**
MSc Data Science & Analytics — University College Cork (2:1)
B.Tech Computer Science & Engineering (Data Science) — Sharda University (1:1)

🔗 [LinkedIn](https://linkedin.com/in/sohitkummar) · [GitHub](https://github.com/sohitkummar)
