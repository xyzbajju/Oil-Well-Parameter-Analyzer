# 🛢️ Oil Well Parameter Analysis

A project focused on analyzing and modeling key oil well parameters—porosity, water saturation, and permeability—using statistical and machine learning techniques.

---

## 📘 Overview

This project involves:

- Generating synthetic oil well data for **porosity** and **irreducible water saturation (Swc)**.
- Computing **permeability** using a reservoir-specific correlation.
- Visualizing and analyzing distributions of key parameters.
- Using **Decision Tree Regression** to predict permeability from porosity and Swc.
- Evaluating model performance using MAE, MSE, and RMSE.

---

## 💡 Key Contributions

- 📊 **Analyzed and interpreted basic oil well parameters**, including porosity and permeability transformation.
- 🧪 **Conducted Isochronal tests** and **reservoir pressure analysis** for improved understanding of well performance.
- 🌲 Applied **Decision Tree Regression** and used **elbow method** to optimize model complexity.

---

## 🧰 Tools & Technologies

- **Python**
- **NumPy, Pandas** – Data generation and manipulation
- **Seaborn, Matplotlib** – Visualization
- **Scikit-learn** – Regression models and performance metrics
- **Google Colab** – Interactive development

---

## 📁 Dataset

- **Synthetic data** generated using statistical distributions to simulate:
  - Porosity (`phi`) – normal distribution centered at 0.25
  - Irreducible water saturation (`Swc`) – normal distribution centered at 0.1
  - Permeability (`k`) – calculated using a petrophysical formula.

---

## 📊 Visualizations

- KDE plots to show parameter distributions
- Error vs. Leaf Nodes plot for model tuning
- Predicted vs. Actual Permeability scatter plot

---

## 🚀 How to Run

1. Click below to open in Google Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

2. Run all cells in order to:
   - Generate data
   - Train models
   - Visualize results

---

## 📈 Model Evaluation

The Decision Tree Regressor was evaluated using:

| Metric  | Value (%) |
|---------|-----------|
| MAE     | 0.37      |
| MSE     | 0.11      |
| RMSE    | 3.28      |

---

## 🙌 Acknowledgements

- Petrophysical equation adapted from industry-standard reservoir modeling references.
- Project developed for academic and analytical purposes only.

---

