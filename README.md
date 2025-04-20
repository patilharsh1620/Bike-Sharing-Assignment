# 🚴‍♂️ Bike Sharing Demand Prediction Using Linear Regression

## 📌 Project Overview

This project applies **Linear Regression** to the **Bike Sharing Dataset** to predict daily bike rental counts based on various seasonal, temporal, and environmental factors.

The goal is to derive actionable insights that can support **business decision-making**, including demand forecasting, resource allocation, and operational planning.

---

## 📂 Repository Contents

| File Name                                      | Description                                                      |
|------------------------------------------------|------------------------------------------------------------------|
| `Linear_Regression_Assignment(Harsh_Patil).ipynb` | Main Jupyter notebook with code, visualizations, and analysis     |
| `day.csv`                                      | Dataset containing daily bike rental records                     |
| `README.md`                                    | Project overview and documentation                               |

---

## 📊 Dataset Summary

The dataset (`day.csv`) is sourced from the UCI Machine Learning Repository and includes:

- **Date Features**: `dteday`, `season`, `yr`, `mnth`, `weekday`
- **Weather Indicators**: `temp`, `atemp`, `hum`, `windspeed`, `weathersit`
- **User Information**: `casual`, `registered`, `cnt`
- **Other Features**: `holiday`, `workingday`

The target variable is **`cnt`** — the total count of bike rentals per day.

---

## 🔍 Key Highlights

- ✅ **Data Cleaning**: Dropped unnecessary columns and handled correlations
- 📈 **EDA & Visualization**: Explored trends, patterns, and relationships
- 🧮 **Model Building**: Built a linear regression model using `scikit-learn`
- 📉 **Performance Evaluation**: Used R² score and residual analysis
- 💡 **Insights**: Identified temperature and season as primary demand drivers

---

## 🚀 Getting Started

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/bike-sharing-linear-regression.git
cd bike-sharing-linear-regression
