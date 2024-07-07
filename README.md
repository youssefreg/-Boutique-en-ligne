# Boutique-en-ligne

Bienvenue sur le projet "Boutique-en-ligne" ! Ce projet est une application de boutique en ligne développée avec Spring Boot pour le backend et Angular pour le frontend.

## Table des matières

- [Introduction](#introduction)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Introduction

"**Boutique-en-ligne**" est une plateforme de commerce électronique qui vise à simplifier l'expérience d'achat en ligne pour les utilisateurs. Ce projet utilise **Spring Boot** pour la partie serveur et **Angular** pour la partie cliente.

## Fonctionnalités

- Inscription et authentification des utilisateurs
- Parcourir et rechercher des produits
- Ajouter des produits au panier
- Passer des commandes
- Interface d'administration pour gérer les produits et les commandes

## Prérequis

Assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 12+)
- [Angular CLI](https://angular.io/cli) (version 10+)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (version 11+)
- [Maven](https://maven.apache.org/) (version 3.6+)
- [MySQL](https://www.mysql.com/) (ou toute autre base de données relationnelle)

## Installation

### Backend (Spring Boot)

1. Clonez le dépôt :

    ```bash
    git clone https://github.com/votre_nom_d_utilisateur/Boutique-en-ligne.git
    ```

2. Accédez au répertoire backend :

    ```bash
    cd Boutique-en-ligne/backend
    ```

3. Configurez la base de données MySQL dans `src/main/resources/application.properties` :

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/votre_base_de_données
    spring.datasource.username=votre_nom_d_utilisateur
    spring.datasource.password=votre_mot_de_passe
    ```

4. Compilez et démarrez le serveur :

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

### Frontend (Angular)

1. Accédez au répertoire frontend :

    ```bash
    cd ../frontend
    ```

2. Installez les dépendances :

    ```bash
    npm install
    ```

3. Démarrez l'application Angular :

    ```bash
    ng serve
    ```

4. Ouvrez votre navigateur et accédez à `http://localhost:4200`.

## Utilisation

1. Accédez à l'interface utilisateur via votre navigateur à `http://localhost:4200`.
2. Inscrivez-vous ou connectez-vous pour commencer à utiliser l'application.
3. Parcourez les produits, ajoutez-les à votre panier et passez des commandes.

## Contribuer

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b fonctionnalité/AmazingFeature`).
3. Commitez vos modifications (`git commit -m 'Ajoutez une fonctionnalité incroyable'`).
4. Poussez à la branche (`git push origin fonctionnalité/AmazingFeature`).
5. Ouvrez une Pull Request.

## Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.
