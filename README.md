# Analyse et prediction de la consommation d'électricité en France

Pour notre projet, nous avons opté pour une étude approfondie de la consommation d'électricité en France.  Cette analyse s'inscrit dans le cadre de la compréhension des tendances énergétiques nationales, en mettant particulièrement l'accent sur les variations régionales et en prenant en compte les variations sectorielles. Nous avons sélectionné une base de données provenant du site officiel du gouvernement français : [Lien vers la base de données](https://www.data.gouv.fr/fr/datasets/5bf39f229ce2e77b7d0059b6/).

Nous allons aussi faire un modèle prédictif de la consommation électrique à partir des données journalières et horaires. En utilisant les données détaillées heure par heure, nous allons construire un modèle qui nous permettra de prédire la consommation électrique dans le futur. Nous allons utiliser cette base de données pour le modèle prédictif.

## **Objectifs du Projet :**

L'objectif principal de notre projet est de détailler et de comprendre les schémas de consommation d'électricité et de gaz en France sur une période allant de l'année 2012 à 2021 afin de pouvoir prédire de manière précise la consommation future. Nous nous concentrerons sur plusieurs aspects, y compris la consommation par secteur (agriculture, industrie, résidentiel, tertiaire) et les variations au fil des années. Afin de pouvoir réaliser un modèle prédictif précis, nous utiliserons une échelle plus appropriée qui est la consommation heure par heure.

## **Variables d'Intérêt :**

Les variables précises de notre analyse sont les régions, les dates, la consommation par secteur et la consommation totale. Nous utiliserons ces variables pour non seulement analyser la consommation électrique et gazière mais aussi pour pouvoir prédire de manière précise les consommations futures.

## **Source des Données :**

Les données nécessaires à notre analyse seront extraites du portail gouvernemental de données ouvertes de la France, disponible à l'adresse [https://www.data.gouv.fr/fr/datasets/5bf39f229ce2e77b7d0059b6/](https://www.data.gouv.fr/fr/datasets/5bf39f229ce2e77b7d0059b6/). 

Pour la consommation journalière, nous allons utiliser cette base de données ouverte au public qui donne la consommation électrique heure par heure en France
[https://odre.opendatasoft.com/explore/dataset/eco2mix-national-cons-def/download/?format=csv&disjunctive.nature=true&q=date_heure:%5B2014-12-07T23:00:00Z+TO+2022-11-08T22:59:59Z%5D&timezone=Europe/Berlin&lang=fr&use_labels_for_header=true&csv_separator=%3B"](https://odre.opendatasoft.com/explore/dataset/eco2mix-national-cons-def/download/?format=csv&disjunctive.nature=true&q=date_heure:%5B2014-12-07T23:00:00Z+TO+2022-11-08T22:59:59Z%5D&timezone=Europe/Berlin&lang=fr&use_labels_for_header=true&csv_separator=%3B")
