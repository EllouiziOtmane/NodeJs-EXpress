
######   TP1 / TP2 / TP3     ######

## Auteur:

Ellouizi Otmane
ID: p1934328

# Objectif du TP:

Mise en place une Single Page Application (SPA) permettant de créer et controler des présentations. Elle sera développée principalement côté client avec React, avec un serveur Node/Express léger. Client et serveur seront codés en JavaScript.

Les points suivants seront abordés

La mise en place d’un serveur Express
L’automatisation avec Webpack
configuration Webpack / Babel / ESlint
Création d'un projet React 
Gestion des états et flux de données
Gestion de routes React
Redux pour la gestion avancée des états
Middleware pour gérer des effets de bord
Design responsive et adaptatif


## Chemin du dossier Projet:

D:\TIW\Technologies_Web_synchrones_et_multi_dispositifs\web\TP3\NodeJs-EXpress


# Packages installés:

npm webpack
npm babel-loader
npm bootstrap
npm express
npm react
npm react-bootstrap
npm react-dev-tools
npm react-dom
npm react-router-dom
npm style-loader

## cmd Github:

git add .
git commit -m "Mise en place de Webpack / babel"
git remote add origin https://github.com/EllouiziOtmane/NodeJs-EXpress.git
git push -u origin master

## Lien du TP sur GitHub:

https://github.com/EllouiziOtmane/NodeJs-EXpress.git


## Execution:

npm run build: construction / préparation du projet.
npm run dev : Lancement du projet en mode dév ( les modifications exécutés à fil de l'eau)
npm start : Démarrage du serveur pour tester le projet.

## Hébérgement sur Heroku:

1. Création d'une nouvelle application sur Heroku ( pour moi je l'ai nomé reactslideshow ).
2. Pour vérifier qu'une télécommande nommée herokua été définie pour notre application:   

   git remote -v

3. Ajouter une télécommande à notre référentiel local avec la heroku git:remotecommande:

   heroku git:remote -a reactslideshow

4. Déploiyer notre application sur Heroku:

   git push heroku master

## Lien de notre application sur Heroku

   https://reactslideshow.herokuapp.com/

