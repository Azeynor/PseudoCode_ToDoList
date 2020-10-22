Pseudo-Code 

Projet To-Do-List 1.0

Etapes: 

1. Créer une base de données 

Composition:
Une Base de Donnée "ToDo"
Une table "Tasks"
Créer une entrée "TaskTitle"
Créer une entrée "TaskDate"
Créer une entrée "TaskDescription"

Structure: 
ID: type: INT NULL: Non Extra: ajouter l'auto-incrémentation 
"TaskTitle" : type: VARCHAR (255) NULL: non 
"TaskDate": type: DATETIME NULL: non
"TaskDescription" type: TEXT NULL: non

2. Connecter le projet à la base SQL

Créer la fonction de connexion à la base de données SQL
Faire un test de vérification de la connexion

3. Créer un formulaire html permettant de faire apparaitre une liste de To-Do

Composition des champs:
Tâche: entrez ici le titre de la tâche
Description de la tâche: entrez ici une brève description
Date : entrez ici la date limite de réalisation de la tâche

Sécurisation basique des champs:
Réfléchir aux failles XSS et protéger les champs de formulaire HTML

4. S'assurer de faire fonctionner depuis les formulaires HTML les 3 fonctions suivantes

La collecte et l'insertion de données depuis les formulaires HTML vers la base de données
La lecture des données sur la page html depuis la base de données

5. Améliorer le visuel avec du CSS



