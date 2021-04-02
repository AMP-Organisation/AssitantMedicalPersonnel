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
  - continuer les routes places
  - prise en main de quasar pour la partie front

- en groupe :
  - Initialisation du repo du web front pour le projet éponyme : initialisation d'un projet Quasar
  - revue de code sur les route user pour merger sur la branche develop

## Mardi 23 Mars
- en groupe
  - On a revu et merge nos travaux sur la base de donnée
    - la table avertissement (créé ce jour)
    - la table maladie
    - table place (les lieux)
  - idem sur le back
    - routes lieux
    - routes maladies
    - netoyage et merge pour pouvoir développer les fonctionnalité corectement de chaque coté 
  - idem sur le front 
  - revu de la page login : selon le figma 
  - création ensemble du Main layout : dorénavant, nous avons le composant de base pour implémenter facilement nos fonctionnalitées

- Nathan
  - recherche deploiement (temporaire) de l'application
  - Déploiement front sur netlify, back sur heroku pour les branches develop 

## 24,25,26 Mars
- Nathan
  - Dû a mon confinnement comme cas contact, j'ai travaillé pendant trois jour sur la mise en place des lieux sur le front/back

## Lundi 29 Mars
- Baptiste
    - J'ai travaillé sur le front : surtout sur la mise au propre du brouillon de la page sur le renseignement sur les maladies.
    - Avec en meme temps, monté en competence toujours sur quasar, qui, comme ce dernier gere tout ce qui est CSS, j'ai essayé de faire une UI pas trop moche
    - et continué la partie back associé qui n'est pas encore terminé. Et il y a quelques problemes de conception qui seront a corriger : nommage de certains champ en bdd
- Nathan
    - J'ai continuer à travailler sur la page des lieux en ajoutant un q-select pour les types de lieux et une barre de recherche pour l'adresse du lieu désiré. J'ai également mis en place un page de description détaillé pour chacun des lieux.

## Mardi 30 Mars
- en groupe
    - Nous avons fait une review de la partie front des lieux, avec des modifications nécessaire pour celui,
    - Nous avons fait une review et merge du back pour les lieux,
    - Nous avons fait une review de la partie maladie du front,
    - Discussion générale sur le projet (état d'avancement, fonctionnalité disponibles, ...)

- Nathan 
   - J'ai mis en place un github action pour le déploiement de notre architecture AWS lors d'un merge sur le main 

- Baptiste

## Mercredi 31 Mars
- Baptiste
  - J'ai travaillé sur le back sur une route PUT, donc qui efface l'ancienne entrée de la bdd pour en créer une toute nouvelle
  - sur le front, j'ai créé une page de description détaillé pour une maladie. j'ai eu quelques probleme juste pour créer corectement le composant ... (-_-') (juste un probleme simple mais qui fait perdre du temps)
  - et aussi, amélioration de tout ce qui est orgnaisation de la "grid" quasar, avec les columns et les rows

## Jeudi 1er Avril :fish:
- Baptiste
  - J'ai travaillé sur la route PATCH cette fois ci, un premier brouillon qui utilisait la meme fonction que PUT
  - puis refactorisaion, car sqlalchemy detect et gere très facilement le changement simple de certains champs dans une table, donc : refactorisation pour une meilleurs route PATCH (mais qui ne gere que le changement du nom et de description pour le moment)
  - amélioration de l'existant du front avec la bonne organisation de la "grid" quasar
  - travail de recherche pour avoir des sorte de variable global sur le front, et premier brouillon d'amélioration du main layout

- en binome
  - réunion de mise au point de tout ce qu'il y a maintnenant

## vendredi 2 Avril
- Baptiste 
  - modifier encore le style pour mieux organiser les elements, maintenant que j'ai bien la logique de quasar (qui est certe comme d'autre framework qui font que du CSS, mais comme j'ai commencé a mettre les éléments sans tenir comptes de la "grid")
  - netoyer le front et le back pour la partie maladie, pour faire un premier merge aujourd'hui

- en binome
  - merge des branch front et back :
    - place
    - login
    - disease
  - Pour récupéré chacun le travail de l'autre et progresser dans le développement générale de l'application


### home page
[retour à l'accueil](https://github.com/AMP-Organisation/AssitantMedicalPersonnel/blob/main/Suivi.md)
