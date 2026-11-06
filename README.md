# Analyse des performances commerciales et optimisation de la gestion d'une entreprise : AFRICA DISTRIBUTION SARL

Projet de stage professionnel simulé (poste : Data Analyst stagiaire, mission principale : Business Intelligence), réalisé dans le cadre de ma soutenance de fin de formation.

## Contexte

AFRICA DISTRIBUTION SARL est une entreprise camerounaise (entreprise fictive) spécialisée dans la distribution de produits alimentaires, de boissons, de produits d'entretien et de grande consommation, avec plusieurs points de vente dans différentes villes du Cameroun.

Malgré la hausse de son activité, la direction rencontre plusieurs difficultés :
- produits les plus rentables mal identifiés ;
- ruptures de stock régulières et produits qui stagnent en entrepôt ;
- ventes très variables d'un mois à l'autre ;
- performances des commerciaux, comportements des clients et magasins les plus performants mal maîtrisés ;
- difficulté à anticiper les ventes futures.

## Objectif

Concevoir un système complet d'analyse des données commerciales pour répondre à la question :

> Comment AFRICA DISTRIBUTION SARL peut-elle augmenter son chiffre d'affaires, améliorer sa rentabilité, optimiser ses stocks et fidéliser ses clients grâce à l'analyse des données ?

## Outils utilisés

| Outil | Usage |
|---|---|
| Excel | Exploration initiale, tableaux croisés dynamiques, contrôles qualité |
| Python (Pandas, NumPy, Matplotlib, Seaborn) | Nettoyage, analyse exploratoire, prévisions |
| SQL (PostgreSQL ou MySQL) | Base relationnelle, requêtes avancées (jointures, CTE, fenêtrage) |
| Power BI (Power Query, DAX) | Modèle en étoile, tableaux de bord |
| Git / GitHub | Suivi des versions |
| PowerPoint / Word | Présentation et rapports |

## Phases du projet

| # | Phase | Statut |
|---|---|---|
| 1 | Compréhension du besoin métier et cadrage | Terminé|
| 2 | Collecte et exploration des données (Excel) | À faire |
| 3 | Nettoyage et préparation (Python) | À faire |
| 4 | Conception de la base de données (SQL) | À faire |
| 5 | Analyse exploratoire approfondie (Python) | À faire |
| 6 | Analyse des stocks et approvisionnements | À faire |
| 7 | Business Intelligence (Power BI, 5 tableaux de bord) | À faire |
| 8 | Prévisions et analyse prédictive | À faire |
| 9 | Recommandations stratégiques | À faire |
| 10 | Présentation finale | À faire |

## Structure du projet

```
STAGE_DATA_ANALYST/
├── 01_CADRAGE_PROJET/   # Cahier des charges, objectifs métier, dictionnaire des données
├── 02_DATA_BRUTE/       # Données brutes (non versionnées)
├── 03_EXCEL/            # Analyse exploratoire Excel
├── 04_PYTHON/           # Notebooks : exploration, nettoyage, analyse, prévisions
├── 05_SQL/              # Création de la base, importation, requêtes, modèle relationnel
├── 06_POWER_BI/         # Fichier .pbix et tableaux de bord
├── 07_RAPPORTS/         # Rapports qualité des données, analyse, stratégique
├── 08_PRESENTATION/     # Soutenance finale
└── README.md
```

## Données

Les données sont **synthétiques** (simulées) et volontairement imparfaites (valeurs manquantes, doublons, dates mal formatées, prix incohérents, identifiants inexistants, transactions annulées mélangées aux ventes validées).

Les 10 fichiers sources : `ventes`, `clients`, `produits`, `magasins`, `commerciaux`, `stocks`, `fournisseurs`, `achats`, `depenses`, `livraisons`.

Les données brutes **ne sont pas versionnées** dans ce dépôt (voir `.gitignore`).

## Résultats principaux

[À COMPLÉTER à la fin du projet : chiffres clés, constats, recommandations]

## Limites

[À COMPLÉTER : limites des données synthétiques, des modèles de prévision, etc.]

## Auteur

**[AGATTE MELVINE NGANZEU]**
Étudiante en informatique, Université de Douala (Cameroun)
LinkedIn : [(https://www.linkedin.com/in/agatte-melvine-nganzeu-data-analyst/)]