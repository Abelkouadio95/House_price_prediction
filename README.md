# 🏠 Prédiction du Prix des Maisons – EDA & Machine Learning

## 📌 Contexte
Ce projet a pour objectif de développer un modèle de **Machine Learning** capable de prédire le prix de maisons à partir de leurs caractéristiques (surface, nombre de pièces, localisation, etc.).  
L’analyse se déroule en plusieurs étapes : exploration des données, préparation, modélisation et évaluation des performances.

---

## 🔍 Exploration des données (EDA)
L’**analyse exploratoire des données** a permis de mieux comprendre le dataset et d’identifier les variables influentes sur le prix des maisons.

**Principales étapes :**
- ✅ **Nettoyage des données** : suppression des doublons, gestion des types de variables, vérification de l’absence de valeurs manquantes.  
- 📊 **Analyse des distributions** : visualisation des prix, surfaces, et autres variables clés.  
- 📈 **Corrélations** : identification des caractéristiques les plus liées au prix, avec la **surface** comme indicateur fort.  
- 🔍 **Visualisations** :  
  - Histogrammes et boxplots pour détecter les outliers  
  - Heatmap des corrélations pour repérer les variables pertinentes  
  - Scatter plots prix vs surface  

---

## 🤖 Modélisation
Plusieurs modèles de régression ont été testés pour prédire le prix des maisons.

**Approches explorées :**
- **Régression Linéaire**  
- **Régression Ridge / Lasso** 
- Comparaison des scores R² sur un set de test

**Résultats obtenus :**
- 📌 Meilleur modèle retenu : **Régression Linéaire**
- 📈 Score R² ≈ **0,6497** → environ **65% de variance expliquée**
- 💡 Conclusion : le dataset ne permet pas d’aller beaucoup plus loin sans nouvelles variables

---

## 🛠️ Technologies utilisées
- **Python**  
- **Pandas** – manipulation et nettoyage des données  
- **NumPy** – calculs numériques  
- **Matplotlib & Seaborn** – visualisations  
- **Scikit-learn** – modélisation et évaluation  

---

## 🚀 Pistes d’amélioration
- Ajouter des **variables explicatives** (localisation géographique, année de construction, état général…)  
- Optimiser les **hyperparamètres** via Grid Search ou Random Search  
- Réaliser une **cross-validation** pour plus de robustesse
