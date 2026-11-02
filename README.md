# Analyse des ventes d'un café (Projet ML)

## 📌 Contexte
Ce projet a pour but d'analyser les données transactionnelles d'un café afin d'extraire des insights business et de proposer des recommandations pour augmenter le chiffre d'affaires.

## 📊 Dataset
Les données proviennent de Kaggle : [Cafe Sales Dataset (Clean)](https://www.kaggle.com/datasets/aramelheni/cafe-sales-dataset-clean).
- **Lignes :** ~9 700 transactions.
- **Variables :** Nom du produit, quantité, prix unitaire, montant total, date de transaction.

## 🛠️ Technologies utilisées
- **Python** (Pandas pour la manipulation des données)
- **Matplotlib & Seaborn** (Visualisation)
- **Mlxtend** (Algorithme Apriori pour l'analyse des associations)

## 🔍 Méthodologie
1. **Nettoyage et Préparation :** Conversion des dates, extraction des heures.
2. **Analyse Exploratoire (EDA) :** Identification des produits stars et des heures de pointe.
3. **Machine Learning :** Utilisation de l'algorithme **Apriori** (Market Basket Analysis) pour découvrir quels produits sont fréquemment achetés ensemble.

## 💡 Résultats clés
*   Le produit le plus vendu est le **café**, mais le produit qui génère le plus de revenus est le **sandwich**.
*   L'analyse d'association a révélé que les clients qui achètent du **café** ont une forte probabilité d'acheter aussi des **cookies**.
*   **Recommandation :** Créer une offre combinée "Café + Cookie" pour augmenter le panier moyen.
