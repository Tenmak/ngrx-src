## Introduction

Les applications Angular sont portées et manipulées à l'aide d'un outil en ligne de commande appelé [Angular-CLI](https://cli.angular.io/) (Angular Command Line Interface).

## Pré-requis

Pour exécuter les commandes, un environnement [NodeJS](https://nodejs.org/en/) est requis. Cet environnement est disponible sur Windows et Linux.
La dernière version recommandée et utilisée dans ce projet est appelée LTS (Long Time Support). A ce jour (22/05/2018), la dernière version NodeJS LTS est 8.11.2.

Cet environnement NodeJS embarque directement le gestionnaire de packages (librairies) pour notre application : [NPM](https://www.npmjs.com/).

Dans un terminal (Windows ou Linux), les commandes permettant d'afficher les versions de ces outils devraient être disponibles et s'exécuter correctement :

* `node -v`
* `npm -v`

### Génération

Vous pouvez lancer le projet dans le mode souhaité avec les commandes suivantes :

* `npm run start` : Lance le projet en local sur la machine à l'adresse suivante : http://localhost:4200.
* `npm run build` : Créé le dossier contenant le site web packagé dans le dossier `dist` qui sera à la base du projet.
