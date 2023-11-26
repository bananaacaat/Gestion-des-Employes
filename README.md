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

- `src/main/java` : Contient les classes Java du projet.
- `src/main/resources` : Contient les ressources essentielles du projet, telles que les fichiers de configuration.
- `src/main/WEB-INF` : Englobe les pages JSF, les fichiers CSS, JavaScript et les ressources web.
- `src/test` : Répertoire réservé aux tests unitaires.

## Screenshots 
### Base de données
![WhatsApp Image 2023-11-26 at 01 47 12_534cf188](https://github.com/bananaacaat/tp-JSF/assets/147453939/6e7a1962-14dd-4a45-8849-182808d982bd)

### Ajouter Employée
![WhatsApp Image 2023-11-26 at 02 28 18_8ed37e0c](https://github.com/bananaacaat/tp-JSF/assets/147453939/1c9ce8a3-2e26-4d76-8d7c-4eacfbab7747)

### Modifier Employée
![WhatsApp Image 2023-11-26 at 02 29 33_65626b1f](https://github.com/bananaacaat/tp-JSF/assets/147453939/bd984ad4-e345-4d45-b6ce-60499e9eefdf)

### Supprimer Employée
![WhatsApp Image 2023-11-26 at 02 30 06_f435284d](https://github.com/bananaacaat/tp-JSF/assets/147453939/6cde3511-98a4-42f8-b208-1925cb35480c)

### Ajouter Service
![WhatsApp Image 2023-11-26 at 02 30 38_12b4d132](https://github.com/bananaacaat/tp-JSF/assets/147453939/9590e28c-81fe-40f7-b70b-f4df9cb985b0)

### Modifier Service
![WhatsApp Image 2023-11-26 at 02 31 06_7df25cbf](https://github.com/bananaacaat/tp-JSF/assets/147453939/7da4a741-118c-4bff-b085-ce35311132ac)

### Supprimer Service
![WhatsApp Image 2023-11-26 at 02 32 01_f5c9e096](https://github.com/bananaacaat/tp-JSF/assets/147453939/9da57795-1e84-4693-9b05-a8402bef1c27)

### STATS
![WhatsApp Image 2023-11-26 at 02 35 56_9d53dcda](https://github.com/bananaacaat/tp-JSF/assets/147453939/8a6b3383-72f5-4ac6-8856-0adb31450627)


## Configuration

- Base de données : Configurer les paramètres de connexion à la base de données dans le fichier hibernate.cfg.xml.
- Serveur d'Application : Déployer l'application sur un serveur compatible Java (par exemple, Glassfish).
