# Web scraping de Wikipédia et analyse d'un graphe de liens

Collecte automatisée des pages d'une catégorie Wikipédia, analyse statistique des contenus et construction d'un graphe de liens.

## Démarche (`Projet_1_WebScraping.ipynb`)

1. **Exploration d'une catégorie** : extraction des sous-catégories et des pages (BeautifulSoup).
2. **Scraping des pages** : fonctions `extraire_sous_categories`, `extraire_pages`, `extraire_toutes_pages`, `extraire_informations_page`, export en JSON et CSV.
3. **Analyse statistique** des informations extraites.
4. **Graphe de liens** entre pages (NetworkX).

## Données produites

Le dossier `Donnée_scrapé/` contient les jeux de données extraits (CSV et JSON).

## Outils

Python, requests, BeautifulSoup, pandas, NetworkX, Matplotlib, Seaborn.

## Bonnes pratiques

Respecter les conditions d'utilisation du site, limiter la cadence des requêtes et ne collecter que des données publiques.

## Auteur

**Hady Coulibaly**, Data Analyst & Data Scientist, titulaire d'un Master Chef de projet Data & IA (Nexa Digital School). Contact : hady.coulibaly.data@gmail.com · [LinkedIn](https://www.linkedin.com/in/hady-coulibaly-data-ia-france-cdi/)
