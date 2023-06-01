# Fedegram

## Présentation d'ensemble du projet

### Présentation du commanditaire

La FEdération Des ETudiants Toulonnais (FEDET) cherche à répondre à la problématique de diffusion de l'information et de transition informatique et cherche un moyen de rassembler les informations conçernant les actions de la fédération et de ses associations membres sous forme d'une application qui puisse être accessible par tous.

### Périmètre du projet

Le projet est destiné à fonctionner sur ordinateur, tablette et mobile.
Il doit être compatible avec tous les systèmes d'exploitation (Windows, Linux, MacOS, Android, iOS, etc.).
Spécificités :
L'application doit intégrer une carte ainsi qu'un service de géolocalisation pour permettre aux utilisateurs de trouver les locaux ou évènements à proximité.
Il serait optimal d'ajouter plusieurs interfaces :

-   une interface avec les posts (évènements) des différentes associations ou fédérations où les utilisateurs peuvent réagir et commenter.
-   une interface de chat pour permettre aux utilisateurs de communiquer entre eux.
-   une interface de profil pour permettre aux associations de gérer leurs informations personnelles, leurs posts, leurs membres et leurs abonnements.

## Description fonctionnelle et technique

### Arborescence de l'application

** Grandes sections de l'application : (sous forme d'onglets) **

-   Accueil (posts, stories, etc.)
-   Chat (messagerie instantanée)
-   Profil (informations personnelles, posts, membres, abonnements, etc.)
-   Carte (localisation des associations, évènements, etc.)

### Contraintes techniques

** Intégration de services tiers : **

-   API Google Maps (carte et géolocalisation)
-   Socket.io (chat)

** Technologies utilisées : **
Par soucis de compatibilité, de compétences des développeurs et de facilité d'utilisation, nous avons choisi de partir sur une Web App (PWA) et d'utiliser les technologies suivantes :

-   HTML
-   CSS
-   JavaScript
-   PHP
-   MySQL
