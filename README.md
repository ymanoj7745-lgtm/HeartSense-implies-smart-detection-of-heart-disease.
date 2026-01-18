# HeartSense – Heart Disease Prediction Using Machine Learning 🫀

## Project Overview
HeartSense is a machine learning project designed to **predict the risk of heart disease** using clinical and physiological data from multiple sources. The project demonstrates how **feature engineering, model tuning, and ensemble methods** can be applied to healthcare datasets to provide actionable insights.

---

## Key Features
- Combined datasets: Cleveland, Hungarian, Switzerland, and VA.  
- Handles missing values and performs **data cleaning**.  
- **Engineered features** for better prediction:
  - `hr_reserve` – heart rate relative to age  
  - `chol_age_ratio` – cholesterol normalized by age  
  - `oldpeak_slope` – interaction of ST depression and slope  
  - `cp_exang` – chest pain type combined with exercise-induced angina  
- Implements **Random Forest** with hyperparameter tuning.  
- Optional **XGBoost ensemble** for improved stability and performance.  
- **Threshold optimization** to maximize F1-score for heart disease detection.  

---

## Results
- **Accuracy:** ~86%  
- **F1-score (heart disease):** 0.88  
- **Key predictive features:** `cp` (chest pain), `thalach` (max heart rate), `oldpeak_slope`, `hr_reserve`, `ca`  
- The model reliably identifies patients at risk of heart disease.

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/ymanoj7745-lgtm/HeartSense.git
