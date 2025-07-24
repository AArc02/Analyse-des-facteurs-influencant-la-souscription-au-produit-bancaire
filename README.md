# Analyse des facteurs influençant la souscription à un produit bancaire

## 🎯 Objectif
L'objectif de ce projet est de réaliser une **analyse exploratoire des données (EDA)** pour identifier les facteurs influençant la souscription à une offre bancaire.  
L'étude utilise des données client (âge, situation professionnelle, état civil, campagnes marketing, etc.) afin de comprendre quels éléments jouent un rôle dans la réponse **"yes"** ou **"no"**.

---

## 📊 Étapes de l'analyse

### 1. **Nettoyage des données**
- Détection et traitement des valeurs manquantes (`NaN`).
- Remplacement des valeurs aberrantes ou codées (ex. `-1` pour `pdays`).
- Vérification des doublons.

### 2. **Analyse univariée**
- Étude des distributions (histogrammes et boxplots) pour des variables comme `age`, `balance`, `duration`.
- Analyse des variables catégorielles (ex. `job`, `marital`, `education`) avec `value_counts()`.

### 3. **Analyse bivariée**
- Relations entre les variables indépendantes et la variable cible `y`.
- Visualisations avec `seaborn` (ex. `countplot`, `heatmap`).
- Étude des corrélations sur les variables numériques.

### 4. **Insights**
- Mise en évidence des profils clients les plus susceptibles de souscrire.
- Identification des variables les plus discriminantes (ex. `duration` ou `pdays`).

---

## 🛠️ Outils utilisés
- **Python** : `pandas`, `numpy` (manipulation des données)
- **Visualisation** : `matplotlib`, `seaborn`
- **Statistiques** : analyse des moyennes, médianes, corrélations

---

## 🔍 Ce que j’ai appris
- Techniques de base d’**EDA** pour comprendre un dataset.
- Nettoyage des données et remplacement des valeurs manquantes.
- Création de visualisations claires pour raconter une histoire avec les données.
- Utilisation des statistiques descriptives pour interpréter les tendances.

---

## 🚀 Améliorations futures
- Tester des **modèles de machine learning simples** (Logistic Regression, Random Forest) pour prédire la souscription.
- Créer un **dashboard interactif (Streamlit)** pour visualiser les insights.

---

## 📂 Contenu du projet
- `EDA_bank_marketing.ipynb` : notebook complet de l’analyse.
- `test.csv` : dataset utilisé.
- `README.md` : ce fichier de présentation.

---

## 👤 Auteur
**ALLAHNDIGUIM Arsène** – Étudiant en Machine Learning Engineer, passionné par l’analyse de données et la compréhension des comportements clients.
