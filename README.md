# STA 5703 Project 1 — Predicting Superconducting Critical Temperature

This repository contains my course project for **STA 5703: Statistical Computing (UCF)**.  
The project explores the use of classical machine learning models to predict the **critical temperature (Tc)** of superconductors using the [UCI Superconductivity dataset](https://archive.ics.uci.edu/ml/datasets/superconductivty+data).

---

## 📂 Files in this Repository
- **5703_Project1.ipynb** — Jupyter Notebook with the full workflow (EDA, preprocessing, modeling, evaluation, plots).
- **5703_Project1.pdf** — Final project report written in IEEE format.

---

## 📊 Project Overview
- **Dataset:** 21,263 materials with 81 engineered features (elemental/thermal descriptors).
- **Models compared:**
  - Linear Regression
  - Ridge Regression
  - Gradient Boosting Regressor
- **Evaluation:** 3-fold cross validation, RMSE, MAE, and R² on hold-out set.
- **Key results:**
  - Gradient Boosting achieved the best performance:
    - RMSE ≈ 11.6
    - MAE ≈ 7.7
    - R² ≈ 0.88
  - Top features: thermal conductivity range/dispersion and atomic radius.

---

## 🚀 How to Run
### Option 1 — Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `5703_Project1.ipynb`.
3. Upload the dataset zip (`superconductivty+data.zip`) when prompted.
4. Run all cells.

### Option 2 — Local Jupyter
```bash
git clone https://github.com/YOUR_USERNAME/sta5703-superconductivity-report.git
cd sta5703-superconductivity-report
jupyter notebook 5703_Project1.ipynb
