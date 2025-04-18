# 📊 Analyse Exploratoire du Catalogue Netflix

## 👥 Auteurs
- **Perla**
- **Rayanne**
- **Zakaria**

---

## 🎯 Objectif du Projet
Analyser le catalogue de Netflix pour :
- Comprendre les tendances par type, durée, pays, genre, année.
- Nettoyer et structurer les données.
- Proposer des prévisions stratégiques pour l’année 2026.

---

## 📁 Données Utilisées
**Fichier :** `netflix_titles.csv`  
Contient les colonnes principales :
- `title`, `type`, `country`, `release_year`, `date_added`, `rating`, `duration`, `listed_in`, `director`, etc.

---

## 🛠️ Étapes de l’Analyse

### 1. Chargement et Exploration Initiale
- Importation du fichier CSV avec `pandas`
- Aperçu des 5 premières et dernières lignes
- Affichage des infos globales du DataFrame (`info()`, `shape`, `columns`)
- Types de données (numériques, catégorielles)
- Valeurs manquantes
- Observation aléatoire

### 2. Nettoyage et Préparation des Données
- Conversion de `date_added` en `datetime`
- Extraction des durées (`duration`) en format numérique pour films et séries
- Transformation de `listed_in` en liste de genres
- Analyse des valeurs uniques (`type`, `country`, `release_year`, `rating`, etc.)

### 3. Requêtes Ciblées
- Informations sur “Catch Me If You Can”
- Film et série les plus récents
- Réalisateurs ayant plusieurs œuvres
- Années avec le plus d’ajouts de films/séries

### 4. Visualisations Graphiques
- Répartition des types d’œuvres
- Répartition par pays
- Répartition par années
- Répartition des ratings
- Durée des films et séries
- Genres d’œuvres les plus fréquents
- Top 5 des films et séries les plus longs
- Réalisateurs français et œuvres françaises
- Histogramme des dates d’ajout

### 5. Analyse et Prévisions 2026
- Prévision 1 : Le format court va dominer
- Prévision 2 : Les séries surpasseront les films
- Prévision 3 : Accent sur crime, thriller, documentaire
- Prévision 4 : Moins d’ajouts, mais meilleure qualité
- Prévision 5 : La France est un marché clé à développer
- Prévision 6 : Miser sur les réalisateurs récurrents

---

## 🔧 Technologies Utilisées
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## ✅ Résultats Attendus
- Une base de données propre et analysable
- Une visualisation claire des tendances Netflix
- Des recommandations stratégiques pour l’avenir de la plateforme

---

## 🙌 Remerciements
Projet réalisé par :
- **Perla**
- **Rayanne**
- **Zakaria**

Étudiants passionnés de data, culture numérique et innovation.
