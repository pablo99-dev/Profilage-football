# Profilage et Typologie de Joueurs de Football (FIFA 21)

## À propos du projet
Ce projet d'Analyse Exploratoire de Données (Master 1 Informatique) a pour objectif de concevoir un **outil d'aide à la décision** pour la cellule de recrutement d'un club de football. 

L'application permet d'analyser les performances statistiques de milliers de joueurs (issu du dataset FIFA 21) afin d'identifier des profils de jeu réels indépendamment de leur réputation, de détecter des joueurs "atypiques" et de trouver des équivalents statistiques moins coûteux.

## 🚀 Fonctionnalités
* **Prétraitement des données** : Gestion des valeurs manquantes non aléatoires (ex. attributs des gardiens), normalisation et discrétisation des variables (âge, valeur marchande).
* **Exploration & Réduction de dimension** : Matrice de corrélation et Analyse en Composantes Principales (ACP) pour identifier les axes majeurs du jeu.
* **Discrimination supervisée** : Analyse Discriminante (LDA) pour analyser le chevauchement et la séparation des postes officiels.
* **Clustering non supervisé** : Algorithmes K-Means et CAH (Classification Ascendante Hiérarchique) pour faire émerger des profils de jeu indépendants du poste officiel.
* **Dashboard interactif (Plotly Dash)** :
  * Filtrage multicritère (poste, âge, budget, championnat).
  * Projection interactive des profils et sélection d'un joueur en un clic.
  * Algorithme des plus proches voisins ($k$-NN) pour recommander des équivalents statistiques.

## 🛠️ Technologies utilisées
* **Langage** : Python 3.x
* **Data Science & ML** : `pandas`, `numpy`, `scikit-learn`, `scipy`
* **Dashboard & Visualisation** : 'dash', 'plotly'
