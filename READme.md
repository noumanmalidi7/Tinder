


# Speed Dating Analysis - Tinder Project

## Contexte

Ce projet a été réalisé dans le cadre d'une mission pour l'équipe marketing de Tinder. L'objectif est de comprendre les facteurs qui influencent la décision d'un second rendez-vous lors de speed dating, afin d'améliorer l'algorithme de matching et l'expérience utilisateur.

Les données proviennent d'expériences de speed dating menées entre 2002 et 2004. Elles contiennent des informations sur les participants, leurs évaluations mutuelles, leurs préférences et les décisions de match.

## Objectifs du projet

1. Identifier les attributs les plus et les moins désirables chez un partenaire, et comparer selon le genre.
2. Mesurer l'écart entre l'importance déclarée de l'attractivité et son impact réel sur le match.
3. Comparer l'effet des intérêts communs vs. la même origine ethnique.
4. Analyser la capacité des participants à prédire leur propre valeur perçue.
5. Étudier l'effet de l'ordre des dates sur la probabilité de match.

## Structure du notebook

- Chargement et préparation des données
- Audit qualité des données (valeurs manquantes, hétérogénéité des waves, échelles)
- Statistiques descriptives
- Analyse par attributs et par genre
- Corrélations et régression logistique
- Réponses aux 5 questions du sujet
- Conclusions et recommandations pour Tinder

## Prérequis

- Python 3.8 ou supérieur
- Les bibliothèques listées dans `requirements.txt`

## Installation

1. Clonez ce dépôt ou téléchargez les fichiers.
2. Placez le fichier de données `Speed+Dating+Data.csv` dans le même dossier que le notebook.
3. Installez les dépendances :

```bash
pip install -r requirements.txt

