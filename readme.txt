Instructions pour utiliser le projet (Strapi en backend et Angular 8 en frontend)

1. Démarrage du server mongo DB (nous avons utiliser une BD en local donc c'est à adopter avec votre environnement)

$ mongod --dbpath /usr/local/var/mongodb --logpath /usr/local/var/log/mongodb/mongo.log --fork


2. Créer une base de données "cookbookproject" dans MongoDB et importer les fichiers "users.json" et "recettes.json" que se trouvent dans le répertoire "filedump" afin de charger la BD

3. Se rendre dans le repertoire "cookbookproject" et exécuter  les commandes suivantes pour installer les dépendances et lancer le projet Strapi (backend) : 

$ npm install
$ npm run develop


4. Se rendre dans le repertoire "cookbook-app" et exécuter les commandes suivantes pour installer les dépendances et lancer le projet Angular (frontend) : 

$ npm install
$ ng serve -o


5. Se rendre dans le repertoire "cookbook-app/server" et exécuter les commandes suivantes pour installer les dépendances et lancer le Server Node.js permettant d'uploader les images :

$ npm install
$ ng npx nodemon server.js

6. Accéder à l'interface admin de Strapi (Backend) : 
Lien : http://localhost:1337/admin
Username : modykane
Password : strapi

7. Accéder à l'application web Angular : 
Lien : http://localhost:4200
Username : modykane
Password : strapi


