# Projet Netflix SQL
Ce projet a pour but d'explorer et d'analyser une base de donnée Netflix afin d'en extraire des informations clés sur le contenu de la plateforme. Pour cela, je me suis principalement concentré sur la répartition des titres  et la dominance de certains pays et de certains genres.

Les requêtes utilisées ont pour but de démonter mes compétences SQL d'un niveau débutant à intermédiaire, mettant l'accent sur les concepts de base et certains d'un niveau un peu plus avancé tels que :

Les fonctions d'agrégation

Les filtrages et regroupements

Les Common Table Expresions

Les fonctions de fenêtrage

# Base de données
https://www.kaggle.com/datasets/shivamb/netflix-shows : 

Cette base donnée nous liste les films et séries TV disponibles sur la plateforme ainsi que le titre, le/les réalisateurs, le pays, la date d'ajout sur la plateforme, l'année de sortie, la durée, le genre et la description.

# Questions
1) Quelle est la répartition des films et des séries et leur proportion par rapport au total ?
2) Quelle est la répartition géographique des titres ? La part des titres dont la production est des Etats-Unis.
3) Montrer l'évolution des films provenant des Etats-Unis sur les 10 dernières années d’ajout.
4) Lister les 5 réalisateurs ayant le plus de titres.
5) Classer pour chaque type les 5 genres ayant le plus de titres.
6) Pour chaque réalisateur, trouver le premier et le dernier titre ajoutés.

# Insights clés
Une dominance des films sur la plateforme, qui représentent **70% du contenu total.**

**46%**, c'est la part que détient les Etats-Unis que ce soit la production unique ou que la production soit partagée avec d'autres pays.

**2019-2020**, marque le pic en termes d'ajout de films, cela peut s'expliquer par le fait que cette période est marquée par le début de la pandémie COVID-19 ainsi que de nombreux confinementS la plateforme a sûrement dû s'adapter au contexte.

# Outil 
SQLite Studio
