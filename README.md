📊 Analyse Exploratoire du Catalogue Netflix
🧠 Projet réalisé par :
Perla

Rayanne

Zakaria

🎯 Objectif du projet
Ce projet a pour but de réaliser une analyse exploratoire du catalogue Netflix à partir d’un dataset contenant les informations des films et séries disponibles sur la plateforme.
Notre mission est de mieux comprendre les tendances, identifier les contenus dominants, repérer les manques éventuels, et proposer une stratégie de contenu pour 2026.

📁 Données utilisées
Le dataset netflix_titles.csv contient les colonnes suivantes :

title, type, country, release_year, date_added, rating, duration, listed_in, director, etc.

🛠️ Étapes de l’analyse
1. Chargement et aperçu des données
Chargement du fichier CSV avec pandas.

Affichage des 5 premières et 5 dernières lignes.

Informations générales (info, shape, columns, dtypes).

Observation des types de données (numériques, catégorielles).

Recherche des valeurs manquantes et affichage d’une ligne aléatoire.

2. Nettoyage et transformation des données
Conversion de date_added au format datetime.

Transformation de duration en valeur numérique pour les films et séries.

Conversion de listed_in en liste de genres.

Vérification de l’unicité des valeurs dans type, country, release_year, rating, etc.

3. Requêtes spécifiques
Récupération de l’œuvre “Catch Me If You Can”.

Identification du film et de la série les plus récents.

Détection des réalisateurs récurrents.

Année avec le plus de films / séries ajoutés.

4. Visualisations (Matplotlib & Seaborn)
Répartition des types (Movie vs TV Show)

Répartition par pays, années, rating, genres

Durées des films et séries

Top 5 des films/séries les plus longs

Répartition des œuvres françaises et des réalisateurs français

Histogramme des dates d’ajout

5. Analyse et prévisions
Sur la base des données nettoyées et visualisées, nous avons proposé 6 grandes prévisions stratégiques pour Netflix en 2026 :

Le format court va dominer.

Les séries vont dépasser les films en volume et impact.

Les genres crime, thriller, documentaire sont à pousser.

Moins d’ajouts, mais une meilleure qualité éditoriale.

La France est un marché à valoriser davantage.

Miser sur les réalisateurs réguliers pour fidéliser.

📌 Outils utilisés
Python

Pandas

Matplotlib / Seaborn

Jupyter Notebook

✅ Résultat attendu
Une vision claire et stratégique de l’offre Netflix actuelle, des tendances par genre, durée, pays, et année… le tout afin de permettre à la direction de Netflix de prendre des décisions basées sur les données.

🔚 Remerciements
Projet réalisé avec rigueur et créativité par :

Perla, Rayanne, et Zakaria
Étudiants passionnés par la data, les tendances culturelles, et la stratégie numérique.

