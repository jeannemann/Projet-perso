# Projet : Création d'un site météo à Montpellier :sun_with_face:
Bienvenue dans ce dépôt :hibiscus: ! 

Ce projet présente un site web qui affiche les prévisions météorologiques pour Montpellier grâce à l’API Open-Meteo, avec une mise à jour automatisée chaque jour via GitHub Actions. Voici toutes les infos importantes, le contexte, les difficultés rencontrées et ce qui a été amélioré récemment.

## :mortar_board: Contexte du projet
Ce site a été créé à l'origine dans le cadre d'un projet scolaire de l'UE "Développement logiciel" du premier semestre du Master 1 Statistiques et Science des Données de l'université de Montpellier. L'objectif était de se familiariser avec :
- l'utilisation d'APIs pour récupérer des données externes,
- la préparation et le traitement de ces données en Python,
- la création d'un site web simple avec Quarto,
- la mise en ligne via GitHub Pages,
- et l'automatisation des mises à jour avec GitHub Actions.

La consigne était d'appliquer les compétences d'un data scientist en programmation, gestion de données et développement web dans un premier projet concret : créer un site internet donnant les prévisions météorologiques à Montpellier sur 4 jours à partir de données disponibles sur le site internet OpenMeteo (disponible à l'adresse suivante : https://open-meteo.com/en/docs/meteofrance-api).

Le projet a été réalisé en autonomie en Septmebre/Octobre 2023 et évalué à l'époque à 16/20.


## :mantelpiece_clock: Pause et reprise deux ans plus tard
Au moment de la notation, ce projet n'était pas fini : 
- fichié de srtyle CSS non relié au reste du code,
- automatisation des mises à jour non fonctionnelle,
- quelques incohérences dans le code Python.
En Novembre 2025, avec plus de temps libre et une envie de finir proprement ce projet, j'ai décidé de le reprendre pour le finaliser et corriger les problèmes restants :
- nettoyage et correction de la structure du repo GitHub,
- correction du code Python pour plus de clarté et d'efficacité,
- intégration correcte du fichier CSS pour le style,
- ajout d'un fichier `.nojekyll` pour éviter les conflits avec GitHub Pages,
- mise en place fonctionnelle de l'automatisation des mises à jour via GitHub Actions.


:star2: Le site fonctionne désormais correctement et se met à jour automatiquement chaque jour à 5h UTC à l'adresse suivante : https://jeannemann.github.io/Projet-perso/


## Contributions
Ce projet a été réalisé entièrement par Jeanne Mannequin, étudiante en Master 1 Statistiques et Science des Données à l'Université de Montpellier. Le code source est disponible publiquement pour consultation, utilisation et amélioration, et toute suggestion pour améliorer le site ou le code est la bienvenue ! :sparkles: