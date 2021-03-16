# Mars 

## Lundi 1er Mars
- Baptiste: J'ai continué à prendre en main de la gestion des insert et update
  - et aussi des delete (mais sur une autre bdd et une autre table)
  - j'ai refait des route sur mon projet de [test]() 
  - j'ai re créé d'autre route basic pour interagir avec ma basse de donnée et ma table user
- Nathan : Continuer la prise en main de la gestion des requêtes entre plusieurs tables
## Mardi 2 Mars :birthday:
- travail de groupe : 
  - création d'autres tables dans la base de donnée :
    - table des médicaments
    - table des type de médicaments
    - table des principes actifs
    - table des symptômes
  - Explication : nous pensions au debut réutiliser la base de données publique de l'autorité de la santé, or celle ci est trop complète et mal organisé pour nos besoin, donc nous avons décidé de créer nos propres table dans lesquels nous rajouterons et ordonnerons les données au mieux pour notre application

- Baptiste:
  - recherche pour récupéré des données de la bdm (base de données des medicaments) au final on va créer nos propres tables
  - j'ai continué de travaillé sur mon projet de test de fast api avec enfin, (je pensais que ca marchais) une relation des jointure automatique ebtre deux tables...
  - mais aussi, recherche dans la doc pour retourner des fichiers depuis fast api : il faut installé via pip aiofiles; l'interet serait de renvoyer un fichier html simple pour ajouter deux trois explication succinte sur l'api
  - et d'autre recherche autours de fast api..

- Nathan :
  - recherche pour récupérer les médicaments depuis la base de données,
  - création d'un modèle pour intéragir avec une liste d'ID,
  - test avec postman pour voir les routes à mettres en places pour les médicaments (GET, POST, PUT, ...)

## Lundi 8 Mars 
- travail en binome:
  - Nous avons initialisé le depot prorement, c'est a dire qu'on a créé toute la structure du dépot AMP-Back pour "merger" nos travaux préliminaire réaliser chacun de notre coté et pour, maintenant que nous avons en mains fast api, commencer a coder proprement l'api
  - discussion pour la mise en place de test automatisé

- Baptiste : 
  - J'ai continué a faire d'autre route :
    - les route pour les médicaments
    - et j'ai fait des recherches pour trouver un bon moyen de tester notre programme en CI/CD

- Nathan :
  - J'ai continué à mettre en place les routes pour les médicaments
  - Après répartitions des tâches pour les premières routes du projet, j'ai commencé à faire des tables dans notre BDD pour repérer les lieux de notre solution


## Mardi 9 Mars
- Baptiste
  - J'ai travaillé sur les routes "maladies" qui nous permettront de récupérer une liste de maladies, et les informations a ce propos
  - et donc j'ai créé une premiere base de donnée (pas encore exporté sur le repo)
- Nathan :
    - J'ai continué l'implémentation des tables "places",
    - Mise en place des premières routes pour places,
    - Mise en place à l'aide  de "sqlalchemy_filter" de filtre personnalisable lors de recherche dans la BDD
    
## Lundi 15 Mars
- Baptiste
  - continué les routes maladie
  - et mise au propre : transfert du travail sur le projet brouillon dans le projet 
- Nathan

- en groupe :
  - Initialisation du repo du web front pour le projet éponyme : initialisation d'un projet Quasar
  - revue de code sur les route user pour merger sur la branche develop

### home page
[retour à l'accueil](https://github.com/AMP-Organisation/AssitantMedicalPersonnel/blob/main/Suivi.md)
