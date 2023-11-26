# Projet de Gestion des Employés avec JSF

## Objectif
Ce projet vise à créer une application web utilisant Java Server Faces (JSF) pour la gestion efficace des employés au sein d'une entreprise, organisée par leurs services respectifs. L'application facilite les opérations CRUD (Create, Read, Update, Delete) sur les données des employés, structurées en fonction des services.

## Technologies Utilisées

- Java Server Faces (JSF) : Framework Java conçu pour le développement d'applications web basées sur des composants.
- Java EE (Enterprise Edition) : Plateforme d'exécution pour les applications d'entreprise Java.
- Java Persistence API (JPA) : Spécification Java pour la gestion de la persistance des données.
- PrimeFaces : Bibliothèque proposant des composants JSF riches et réactifs.
- MySQL : Base de données utilisée pour stocker les données de l'application.


## Fonctionnalités

L'application comprend les fonctionnalités suivantes :

1. Affichage des Employés : Présente une liste d'employés organisée par services.
2. Ajout d'Employé : Intègre un formulaire pour ajouter un nouvel employé avec attribution au service correspondant.
3. Mise à Jour d'Employé : Permet la modification des informations de l'employé.
4. Suppression d'Employé : Autorise la suppression d'un employé de la base de données.
5. Gestion des Services : Permet l'ajout, la modification et la suppression des services disponibles.


## Structure du Projet
Le projet est organisé comme suit :

- 'src/main/java' : Contient les classes Java du projet.
- 'src/main/resources' : Contient les ressources essentielles du projet, telles que les fichiers de configuration.
- 'src/main/WEB-INF' : Englobe les pages JSF, les fichiers CSS, JavaScript et les ressources web.
- 'src/test' : Répertoire réservé aux tests unitaires.


## Configuration

- Base de données : Configurer les paramètres de connexion à la base de données dans le fichier hibernate.cfg.xml.
- Serveur d'Application : Déployer l'application sur un serveur compatible Java (par exemple, Glassfish).
