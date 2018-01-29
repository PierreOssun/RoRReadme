# Ruby sur des Rails : L'explication

### MVC

MVC ou le **Model View Controller** décrit la manière de fonctionner de ruby on rails. Le MVC se décompose en 3 parties :

##### Model

Un modèle est un **objet** avec differentes caractéristiques stocké dans la base de donnée.
Par exemple un utilisateur est un objet avec deux caractéristiques : un email et un mot de passe.
Tout ces modèles sont stocké dans la base de donnée du site.

##### View

La vue est l'interface graphique renvoyé a l'utilisateur. elle est genéré par le controleur après avoir traiter les requêtes
de l'utilisater, cherché les informations dans les bases de données et verifié les autorisations.
C'est le fichier **html** renvoyé dans le navigateur de l'utilisateur.

##### Controller

Le controler est le gestionnaire central. Il **reçoit**, **envoie**, **traite** et **renvoie** les requetes. 
C'est dans ce fichier qu'est renseigné les differentes actions a réalisté surl es modèles comme les **fonctions CRUD**.

### Les routes

Pour gérer l'enchevêtrement des pages, les routes servent a organiser les pages comme la colonne vertebrale de notre site.

### Les Bases de Données

Les bases de données sont un tableau stockant les caratéristiques des objets. Par exemple la base de données qui stocke les membres inscrit du site est un tres long hash avec en en colonne tous les utilisteurs et en ligne toutes les cartéristiques de ces même utilisateurs.

### Les relations entre les models des BDD



### Les fonctions du CRUD

Les fonctions du crud sont les fameuses **create, read, update and destroy** c'est a dire :

* Create est une fonction qui va servir a creer l'objet _pour la premiere fois_ et definir ses caractéristiques de base.
* Read est une fonction qui va _lire_ l'objet c'est à dire l'afficher pour un article ou lancer pour une video.
* Update est une fonction qui va modifier l'objet. Elle peut modifier des caractéristiques exsitantes, soit en ajouter (un deuxieme email pour un utilisateur par exemple) ou aussi supprimer une caractéristique pré-existante.
* Destroy est une fonction qui permet de supprimer l'objet.
