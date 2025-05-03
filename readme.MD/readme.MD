# 🚨 Foodborne Disease Prediction (ML Project)

This project uses machine learning to predict **whether a foodborne disease outbreak leads to hospitalization** based on the location, time, food type, and other features.

---

##  Dataset
- **Source:** [Kaggle - Foodborne Disease Dataset](https://www.kaggle.com/datasets/muhammadharis541/foodborne-disease-dataset)
- **File Used:** `fooddata_clean.csv`
- Contains records of disease outbreaks with columns like State, Month, Food, Etiology, Hospitalizations, etc.

---

##  Objective
To build a classification model that predicts **Hospitalization (Yes/No)** due to foodborne illness outbreaks.

---

##  Step-by-Step Workflow

### 1. Load the Data
- Use `pandas` to read `fooddata_clean.csv`.

```python
import pandas as pd
df = pd.read_csv('fooddata_clean.csv')
