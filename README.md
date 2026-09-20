# FinTrust Risk Review Prediction

Data Science track project for the **AnalystLab Africa Experience Lab**  a 4-week
multidisciplinary program built around a fictional digital bank, **FinTrust Digital Bank**.

**Disclaimer:** FinTrust is a fictional organisation. All customers, transactions,
 labels and business information used in this project are **synthetic** and intended
 for educational purposes only.

## Objective

Determine how machine learning can support FinTrust's risk-related decision-making by
predicting whether a transaction should be flagged for **risk review**
(`Risk_Review_Flag`)  a binary classification problem built on synthetic customer and
transaction data.

## Project Context

This repository documents the Data Science track contribution to the wider
FinTrust Financial Intelligence & Digital Banking Support Solution, which also includes
Data Analytics, ML Engineering, Generative AI and Project Management tracks.

Illustrative overall flow:

```
Customer & Transaction Data → Analytics & KPIs → Predictive Risk Intelligence
→ ML Workflow/Service → Knowledge-Based GenAI Support → Integrated FinTrust Solution
```

## Repository Structure

```
fintrust-risk-review-prediction/
├── data/
│   ├── raw/            # Original synthetic datasets (not tracked in git)
│   └── processed/      # Cleaned / feature-engineered data
├── notebooks/          # EDA, feature engineering, modelling notebooks
├── src/                # Reusable scripts (data prep, features, training, evaluation)
├── reports/            # Weekly deliverables (Week 1–4)
├── README.md
├── requirements.txt
└── .gitignore
```

## Data

| File | Description |
|---|---|
| `FinTrust_Customer_Data.csv` | Synthetic customer-level information (1,500 records) |
| `FinTrust_Transaction_Data.csv` | Synthetic transaction-level information (12,000 records) |
| `FinTrust_Data_Dictionary.xlsx` | Field definitions, business meaning and modelling guidance |

Target variable: `Risk_Review_Flag` (`Yes` / `No`) imbalanced at roughly 80.4% / 19.6%.

## Progress

- [x] **Week 1 : Understand & Plan:** Predictive problem statement, target assessment,
  candidate feature table, hypotheses, initial modelling plan, data-quality observations.
- [ ] **Week 2 :Analyse & Prepare:** Data preparation, EDA, feature engineering.
- [ ] **Week 3 :Develop & Integrate:** Model training, evaluation, cross-track integration.
- [ ] **Week 4 :Test, Refine & Present:** Final validation, refinement, presentation.

## Tools

Python · Pandas · NumPy · Scikit-learn · Jupyter Notebook / Google Colab · Git & GitHub

## Author

**Archimède Mulunda**
[GitHub](https://github.com/mulundaarchimede-del)

---
*Part of the AnalystLab Africa Experience Lab  #AnalystLabAfrica*
