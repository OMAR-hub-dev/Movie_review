Critiques de Films App
Bienvenue dans l'application de critique de films! Cette application a été développée pour vous apprendre à mettre en œuvre une architecture faiblement couplée, permettant au code client et au code serveur d'évoluer de manière indépendante.
Objectif

Le but de cette application est de présenter une séparation claire des préoccupations entre le code client et le code serveur. En adoptant cette approche, nous permettons à ces deux parties, mises en œuvre avec des technologies différentes, d'évoluer en parallèle sans dépendances excessives.
Fonctionnalités

    Liste de Films : Affiche une liste de films avec leurs détails.
    Critiques : Permet aux utilisateurs de laisser des critiques sur les films.
    Gestion des Utilisateurs : Système d'inscription et de connexion pour les utilisateurs.

Architecture

L'application suit une architecture client-serveur avec une séparation claire des responsabilités. Le code client est développé en utilisant React, tandis que le code serveur est mis en œuvre avec [technologie du serveur].
Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés :

    Node.js (pour le développement du client)
    [Technologie du serveur] (à installer selon les besoins)
![Capture d’écran 2023-12-04 213305.png](src%2Fmain%2Fresources%2Fimg%2FCapture%20d%92%E9cran%202023-12-04%20213305.png)
Installation

    Clonez ce dépôt : git clone https://github.com/votre-utilisateur/nom-du-repo.git
    Accédez au répertoire du client : cd client
    Installez les dépendances du client : npm install
    Accédez au répertoire du serveur : cd server
    Installez les dépendances du serveur : npm install

Configuration

    Configurez le serveur avec vos paramètres spécifiques (base de données, etc.) dans le fichier server/config/config.js.

Utilisation

    Démarrez le client : cd client && npm start
    Démarrez le serveur : cd server && npm start
![Screenshot 2023-12-04 at 21-34-21 React App.png](src%2Fmain%2Fresources%2Fimg%2FScreenshot%202023-12-04%20at%2021-34-21%20React%20App.png)
L'application sera accessible à l'adresse : http://localhost:3000.
