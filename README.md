# CodeAlpha_SalesPrediction
Sales Prediction using Python for CodeAlpha Internship

# 📈 Sales Prediction using Python

This repository contains a Sales Prediction project completed as part of the **Data Science Internship at CodeAlpha**. The goal of the project is to develop a machine learning model that can predict sales based on advertising spend across various media platforms.

---

## 🧠 Objective

To forecast sales using multiple linear regression by analyzing how advertising budgets for **TV**, **Radio**, and **Newspaper** influence sales figures. This model provides actionable insights that can support marketing decision-making and budget optimization.

---

## 📂 Dataset

- **Source**: [Kaggle - Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Features**:
  - `TV` – Advertising budget spent on TV
  - `Radio` – Advertising budget spent on Radio
  - `Newspaper` – Advertising budget spent on Newspapers
  - `Sales` – Target variable (units sold)

---

## 🔧 Technologies Used

- **Python**
- **Libraries**: 
  - `Pandas`, `NumPy` – Data manipulation
  - `Matplotlib`, `Seaborn` – Data visualization
  - `Scikit-learn` – Machine learning

---

## 🚀 Workflow Summary

1. **Data Cleaning**: Verified nulls, data types, duplicates.
2. **Exploratory Data Analysis (EDA)**:
   - Pairplots and correlation heatmap to understand relationships
3. **Feature Selection**:
   - Chose TV, Radio, and Newspaper as features
4. **Model Training**:
   - Applied **Linear Regression** using `scikit-learn`
5. **Model Evaluation**:
   - Metrics: R² Score, MSE, RMSE
   - Compared actual vs predicted values
6. **Visualization**:
   - Actual vs Predicted Sales scatterplot

---

## 📊 Results

| Metric               | Value (example) |
|----------------------|-----------------|
| R² Score             | 0.89            |
| Mean Squared Error   | 2.90            |
| Root Mean Squared Error | 1.70         |

The model shows a strong correlation between advertising budgets and resulting sales, particularly with **TV and Radio** being the most impactful.

---

## 📌 Project Structure

CodeAlpha_SalesPrediction/
│
├── advertising.csv # Dataset file
├── sales_prediction.ipynb # Jupyter Notebook with full code
├── README.md # Project documentation
└── images/ # (Optional) Plots and charts


