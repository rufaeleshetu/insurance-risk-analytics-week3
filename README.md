# 🚗 Insurance Risk Analytics - AlphaCare Project (Week 3)

This repository contains all deliverables for the 10 Academy AIM Week 3 challenge, focused on **end-to-end risk modeling and predictive pricing** for AlphaCare Insurance Solutions. The project uses historical South African car insurance data to develop data-driven insights and models for premium optimization.

---

## 📦 Tasks Overview

| Task | Description |
|------|-------------|
| **Task 1** | Project setup, EDA, and statistical profiling |
| **Task 2** | Data Version Control (DVC) for reproducibility |
| **Task 3** | A/B Hypothesis testing for segmentation strategies |
| **Task 4** | Predictive modeling for claim severity and risk-based premium pricing |

---

## 🧠 Business Objective

To help AlphaCare Insurance optimize marketing strategies and premium pricing by:
- Discovering low-risk customer segments
- Identifying profitable locations and vehicle types
- Predicting claim severity using ML models
- Supporting pricing strategies with explainable AI

---

## 🗂 Repository Structure

.
├── data/ # Data folder (excluded from Git)
├── dvc_storage/ # DVC-managed data (not tracked in Git)
├── notebooks/
│ ├── task-1-eda.ipynb # EDA and loss ratio analysis
│ ├── task-2-dvc-setup.ipynb # DVC initialization and tracking
│ ├── task-3-ab-testing.ipynb # Hypothesis testing and statistical validation
│ └── task-4-modeling.ipynb # Predictive models & SHAP explainability
├── .dvc/ # DVC config and metadata
├── .gitignore
├── MachineLearningRating_v3.csv.dvc # DVC pointer file (dataset)
├── README.md

yaml
Copy
Edit

---

## 🧪 Task Details

### ✅ Task 1: EDA & Stats

- Portfolio-level loss ratio analysis
- Trends by Province, Gender, VehicleType
- Outlier detection, temporal trends, distributions
- Creative visualizations to highlight insights

### 🔁 Task 2: DVC Version Control

- `dvc init` and local remote setup
- Dataset tracking with `.dvc` file
- Enables reproducible ML workflows

### 📊 Task 3: A/B Testing

- Null hypotheses tested for:
  - Province-based risk
  - Zip code profitability
  - Gender-based risk
- Used Chi-square and T-tests
- Business interpretations included

### 🤖 Task 4: Predictive Modeling

- Filtered policies with `TotalClaims > 0`
- Used:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Evaluated via RMSE and R²
- Explainability via SHAP
- Identified top 10 influential features for pricing strategy

---

## 📈 Key Metrics

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | _fill_here_ | _fill_here_ |
| Random Forest     | _fill_here_ | _fill_here_ |
| XGBoost           | _fill_here_ | _fill_here_ |

---

## 🧰 Tools Used

- Python (pandas, sklearn, xgboost)
- Jupyter Notebooks
- SHAP for explainability
- DVC for dataset versioning
- Git & GitHub for collaboration

---

## 🚀 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/rufaeleshetu/insurance-risk-analytics-week3.git
   cd insurance-risk-analytics-week3
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Restore dataset with DVC:

bash
Copy
Edit
dvc pull
Run notebooks inside notebooks/

👤 Author
Rufael Eshetu
This challenge was completed as part of 10 Academy's Artificial Intelligence Mastery (AIM) Program.

LinkedIn

