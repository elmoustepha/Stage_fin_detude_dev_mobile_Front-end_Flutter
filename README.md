# Mon Projet Full-Stack: Gestion de Parc Informatique

Application mobile full-stack destinée à la gestion d’un parc informatique au sein d’une organisation. Elle permet de gérer les utilisateurs, les matériels, le suivi du parc, la traçabilité des actions et la validation des opérations sensibles selon les rôles.

## Technologies Utilisées
- Front-end: <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" width="20" height="20"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" width="20" height="20">
- Back-end: <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="20" height="20"> ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="20" height="20"> (le back-end n’est pas inclus dans ce repo pour des raisons de sécurité)

## Fonctionnalités
- Authentification sécurisée avec mots de passe chiffrés (bcrypt)
- Interface adaptative selon le rôle de l’utilisateur (Chef de parc / Technicien)
- Gestion des matériels : ajout, modification et suppression avec contrôle d’accès
- Suivi du parc informatique :
  - Numéro de série
  - État du matériel
  - Disponibilité
  - Date et heure d’entrée automatiques
- Historique complet des opérations :
  - Ajout, modification, suppression
  - Horodatage
  - Auteur de l’action
  - Statut (validé, rejeté, en attente)
- Validation des opérations sensibles exclusivement par le Chef de parc
- Notifications internes en temps réel pour informer les utilisateurs des actions importantes

## Structure du Projet
- `main.dart`: point d’entrée de l’application
- `home.dart`: page d’accueil (inscription / connexion)
- `signup.dart`: création de compte utilisateur
- `signin.dart`: authentification
- `materiel.dart`: gestion des matériels
- `parc.dart`: gestion du parc informatique
- `historique.dart`: historique et traçabilité des actions

## Back-End (Non Inclus)
Pour des raisons de sécurité, le back-end n'est pas inclus dans ce repo. Il comprend:
- `server.js`: serveur Express
- `db.js`: connexion à la base de données MySQL
- Routes API: utilisateurs, matériels, parc, historique
- Sécurité: variables d’environnement, données sensibles non exposées, contrôle d’accès par rôles

## Installation et Exécution (Front-End Seulement)
1. Clonez le repo: `git clone https://github.com/elmoustepha/Stage_fin_detude_dev_mobile_Front-end_Flutter.git`
2. Ouvrez les fichiers Dart dans un éditeur Flutter (ou utilisez un émulateur)
3. Pour le back-end complet, contactez-moi pour des détails privés.

## Sécurité
Les informations sensibles (mots de passe, clés API) sont exclues pour éviter les risques. Utilisez des variables d'environnement pour la configuration.

## Licence
MIT
