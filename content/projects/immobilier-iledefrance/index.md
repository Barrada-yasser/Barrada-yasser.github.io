---
title: "Prédiction de Prix Immobiliers par Machine Learning"
summary: "Modèle XGBoost pour la prédiction automatique des prix immobiliers en Île-de-France avec 43,38% de R² et feature engineering avancé"
tags:
  - Machine Learning
  - Data Science
  - Python
  - XGBoost
  - Feature Engineering
date: '2025-01-25'
image:
  caption: ''
  focal_point: ''
  preview_only: true
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/Barrada-yasser/prediction-immobilier-iledefrance
url_code: 'https://github.com/Barrada-yasser/prediction-immobilier-iledefrance'
---

## 🎯 Problématique
L'estimation des prix immobiliers est complexe et chronophage. Les méthodes manuelles sont subjectives et sujettes à l'erreur, impactant les décisions d'achat/vente des particuliers et des professionnels.

## 💡 Solution
Développement d'un modèle de machine learning basé sur **XGBoost** pour automatiser la prédiction de prix immobiliers en Île-de-France avec une précision statistiquement pertinente et un feature engineering avancé.


## 🔧 Architecture Technique
- **Modèle :** XGBoost + Feature Engineering avancé
- **Dataset :** DVF (Demandes de Valeurs Foncières) - données officielles françaises
- **Nettoyage et préparation :**
  - Filtrage Île-de-France (1 511 communes)
  - Réduction de 4,8M à 178,5K transactions propres
  - Gestion des valeurs manquantes et extrêmes
- **Feature Engineering :**
  - 6 features originales → 18 features engineerées
  - Prix moyen par commune, prix/m², surface par pièce
  - Transformations logarithmiques et interactions
- **Pipeline ML complet :** entraînement, validation, évaluation, API REST, interface Web

## 📊 Performances
- **R² Score : 43,38%** (explique 43% de la variance des prix)
- **MAE (Mean Absolute Error) : ±202,640€**
- **Amélioration avec Feature Engineering : +33%** (de 32,61% à 43,38%)
- **Temps d'inférence : <100ms**
- **Dataset : 178,497 transactions** (train/validation/test)

## 🛠️ Stack Technique
- **Framework ML :** XGBoost, scikit-learn
- **Traitement de données :** pandas, numpy
- **Backend :** FastAPI (Python)
- **Frontend :** HTML5, CSS3, JavaScript (Fetch API)
- **Visualisation :** Matplotlib, Seaborn
- **Data source :** https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/

## 🎯 Impact
Ce projet démontre l'application concrète du machine learning dans le secteur immobilier, avec un modèle capable d'assister acheteurs, vendeurs et agents immobiliers dans l'estimation de prix, facilitant les transactions et réduisant les biais humains.

## 🎓 Apprentissages
Maîtrise du feature engineering (transformant 6 features en 18 features pertinentes), gestion de datasets volumeux (4,8M lignes), techniques de nettoyage de données réelles, importance du choix des métriques adaptées au contexte métier (R² vs MAE), et développement d'une pipeline complète du data cleaning jusqu'à l'API production-ready.
