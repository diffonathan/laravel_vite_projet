# Application de Gestion de Cours

## Description

Cette application web permet de gérer des cours et leurs épisodes associés. Elle offre une interface utilisateur intuitive pour la création, la modification et la suppression de cours et d'épisodes.

## Technologies utilisées

* **Framework Backend:** Laravel 8 (PHP) - Un framework robuste et populaire pour le développement d'applications web.
* **Framework Frontend:** Inertia.js - Permet de construire des interfaces utilisateur riches et réactives en utilisant des composants Vue.js, tout en conservant l'architecture serveur-side rendering de Laravel pour un meilleur SEO et des performances optimales.
* **CSS Framework:** Tailwind CSS - Un framework CSS utilitaire qui permet de créer des interfaces utilisateur rapidement et efficacement.
* **Base de données:** MySQL - Gestion de la persistance des données.

## Fonctionnalités principales

* Création et gestion de cours (titre, description, etc.).
* Ajout d'épisodes à chaque cours (titre, durée, lien vidéo, etc.).
* Visualisation des épisodes d'un cours.
* Authentification utilisateur.

## Valeur ajoutée

Cette application démontre ma maîtrise de :

* Laravel et son écosystème (routes, controllers, models, Eloquent ORM).
* La construction d'applications web full-stack.
* L'utilisation de frameworks frontend modernes comme Inertia.js et Tailwind CSS.
* La gestion de données persistantes avec une base de données relationnelle.
* Authentification et gestion des utilisateurs.
* Tests unitaires (présents dans le dossier `tests`).

## Installation et exécution

1. **Cloner le dépôt:** `git clone <URL_DU_DEPOT>`
2. **Installer les dépendances:** `composer install` et `npm install`
3. **Configurer la base de données:** Modifier le fichier `.env` avec les informations de votre base de données MySQL (nom d'hôte, nom de base de données, nom d'utilisateur, mot de passe).
4. **Générer les clés:** `php artisan key:generate`
5. **Migrer les bases de données:** `php artisan migrate`
6. **Lancer le serveur de développement:** `php artisan serve`  (ou utiliser un autre serveur web comme Nginx ou Apache)
