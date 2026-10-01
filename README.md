# Fréquence de sinistres en assurance auto

Projet de modélisation de la fréquence des sinistres en assurance automobile, réalisé dans le cadre du cours d'Assurance Non-Vie. La question de départ : qu'est-ce qui fait qu'un conducteur a plus de sinistres qu'un autre ?

La démarche, les résultats et les limites sont détaillés dans le rapport (`Rapport.pdf`). Ce dépôt contient les données et le code qui vont avec.

## Les données

`assurance_sale.csv` est tiré du jeu public freMTPL2 (assurance auto, responsabilité civile, France). Je l'ai volontairement dégradé : formats mélangés, valeurs manquantes, doublons, valeurs impossibles.

## Contenu du dépôt

- `Rapport.pdf` : le rapport complet.
- `Prétraitement des données.Rmd` : script R de nettoyage et de préparation des données.
- `Modelisation_frequence.Rmd` : script R de modélisation, de validation, et d'export des résultats pour le tableau de bord.
- `sorties modele/` : fichiers produits par la modélisation et utilisés dans le tableau de bord.
- `Images/` : captures du tableau de bord Power BI. Le fichier `.pbix` n'est pas dans le dépôt.

## Refaire tourner le projet

1. Mettre `assurance_sale.csv` dans le même dossier que les scripts.
2. Lancer `Prétraitement des données.Rmd`.
3. Lancer `Modelisation_frequence.Rmd`.

Les fichiers générés arrivent dans `sorties modele/`.

## Outils

R (`data.table`, `MASS`, `knitr`), Power BI, et LaTeX pour le rapport.

## Auteur

Attuoman Prince Josias Koffi
