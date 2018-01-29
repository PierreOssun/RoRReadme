# Ruby sur des Rails : L'explication

### MVC

MVC ou le **Model View Controller** décrit la manière de fonctionner de ruby on rails. Le MVC se décompose en 3 parties :

##### Model

Un modèle est un **objet** avec differentes caractéristiques stocké dans la base de donnée.
Par exemple un utilisateur est un objet avec deux caractéristiques : un email et un mot de passe.
Tout ces modèles sont stocké dans la base de donnée du site.

##### View

La vue est l'interface graphique renvoyé a l'utilisateur. elle est genéré par le controleur après avoir traiter les requetes
de l'utilisater, cherché les informations dans les bases de données et verifié les autorisations.
C'est le fichier **html** renvoyé dans le navigateur de l'utilisateur.

##### Controller

Le controler est le gestionnaire central. Il **reçoit**, **envoie**, **traite** et **renvoie** les requetes. 
C'est dans ce fichier qu'est renseigné les differentes actions a réalisté surl es modèles comme les **fonctions CRUD**.

### Les routes

### Les Bases de Données

### Les relations entre les models des BDD

### Les fonctions du CRUD
