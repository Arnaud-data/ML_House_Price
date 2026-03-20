## ML_House_Price
ML pipeline predicting house sale prices — from raw data cleaning to XGBoost modelling, built with Python &amp; Scikit-Learn.

## House Prices — ML Regression Project

Projet de régression Machine Learning sur le dataset Kaggle House Prices.

# Objectif
Prédire le prix de vente de maisons à Ames, Iowa à partir de 80 variables.

# Pipeline
- `01_exploration.ipynb` — EDA et visualisations
- `02_preprocessing.ipynb` — Nettoyage et encodage
- `03_feature_engineering.ipynb` — Création de nouvelles variables
- `04_modelisation.ipynb` — Modèles et comparaison

# Modèles utilisés
- Régression Linéaire
- Ridge / Lasso
- Random Forest
- XGBoost

# Stack technique
Python, Pandas, Scikit-Learn, XGBoost, Matplotlib, Seaborn

# Résultats
| Modèle | RMSE | R² |
| LinearRegression | 0.1308 | 0.8985 |
| XGBoost | 0.1284 | 0.9022 |
| Random Forest | 0.1458 | 0.8740 |
| Ridge | 0.1229 | 0.9104 |
