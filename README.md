Le jeu du Taquin
=======
Ecole Nationale des Sciences Géographiques (ENSG)  
Micro-Projet Webmapping et données distantes 

## Table des matières
1. [Informations](#Informations)
2. [Pré-requis](#Pré-requis)
3. [Installation](#Installation)
4. [Création](#Création)
5. [Consignes](#Consignes)
6. [Source](####Sources)

# Informations
#### Auteurs
Ilona Baran, Ziad Boukbir et Hugo Reveneau
#### Date
Décembre 2021 - Février 2022
#### URL du site
https://hugoreveneau2.alwaysdata.net
#### Le Projet et ses objectifs:
L’objectif de ce mini-projet est de réaliser un «taquin» : 
+ son interface de jeu avec son web service associé
+ de documenter un drag and drop efficace pour pousser les rangées de pions 
+ de développer l’interface de construction d’un jeu de quinze imagettes (avec son web service associé).
#### Langages utilisés
+ HTML5, CSS3
+ JavaScript, AJAX
+ PHP, PostgresSQL
#### Responsive ?
Non, il n'est pas responsive.   

***

# Pré-requis
+ Connection internet pour accéder aux sites et permettre la visualisation des images et de la carte
+ Utilisation d'un navigateur (évitez Microsoft Edge et Internet explorer)

***

Le site comporte deux pages principales : l'une permet la création de votre propre jeu de données, et l'autre permet de jouer.   
Des jeux de données ont été initialement créés pour jouer, si vous ne voulez pas créer les votres. 

***

# Intsallation

### Base de données
La base de données de ne nécessite aucune installation préalable. Elle est hébergée en ligne sur les serveurs de Alwaysdata, sur le compte associé à l’adresse mail hugo.reveneau@gmail.com. Les installations en local sont donc inutiles.
Il est possible de consulter cette base de données en se connectant sur Alwaysdata. A des fins de sécurité, le mot de passe de connexion ne sera pas référencé ici mais reste disponible sur demande.   

### Serveur local
Le site web étant également stocké sur le même serveur que la base de données, il n’est pas non plus nécessaire d’installer un serveur local. Le site est disponible directement en ligne depuis n’importe quel navigateur, il suffit alors d’installer un navigateur web. Le site semble fonctionnel sur Mozilla Firefox, Chrome, Edge, Duckduckgo mobile et Safari.


# Création
### Accès à la page web
Pour accéder à la page web, il vous suffit de rentrer l’URL suivante dans n’importe quel navigateur web, de préférence Mozilla Firefox car c’est le navigateur utilisé pour son développement.   
### URL 
https://hugoreveneau2.alwaysdata.net/creation   
Une fois que l’utilisateur y accède, un message explicatif relate les principales fonctionnalités.

#### Description de la page web et des commandes
L’objectif de cette page est de proposer aux utilisateurs de créer eux même leurs propres jeux d’imagettes 4x4 ensuite disponibles pour jouer à un jeu de taquin (cf. Projets de Ilona Baran et Ziad Boukbir). Ces imagettes sont créées à partir des fonds de carte du Géoportail. Deux fonds sont actuellement disponibles : L’ortho-image mondiale et le plan mondial. L’utilisateur peut alors sélectionner une emprise souhaitée sur une carte choisie et envoyer les 16 imagettes dans une base de données, ensuite utilisée pour le jeu de taquin.   

## Bravo, vous allez bientôt pouvoir commencer à jouer !

***

# Consignes
#### Accès à la page web
Pour accéder à la page web, il vous suffit de rentrer l’URL suivante dans n’importe quel navigateur web, de préférence Mozilla Firefox car c’est le navigateur utilisé pour son développement.
#### URL 
Webmapping : Taquin (hugoreveneau2.alwaysdata.net)

#### Description de la page web et des commandes
Cette interface permet aux utilisateurs de jouer à un jeu de taquin, qu’ils auront pu créer préalablement grâce à une autre interface web (cf. Projet de Hugo Reveneau).

### Présentation de l'interface de jeu
Une courte explication du projet et les consignes générales sont présentées à gauche. On y retrouve également le classement des meilleurs joueurs : la position, le pseudonyme ainsi que le nombre de coups des 5 meilleurs joueurs sont affichés.
A gauche, se situe l’ensemble des interactions possibles que vous pouvez faire. Vous devez entrer un pseudonyme dont le nombre de caractères doit être compris entre 1 et 20, sélectionner le jeu auquel vous voulez jouer et valider pour que le jeu s’affiche.
Vous avez également la possibilité de de mélanger le jeu autant de fois que vous le souhaitez avant de commencer à jouer grâce au bouton “nouveau tirage”.
A titre indicatif, le nombre de coups que vous avez déjà réalisé ainsi que le nombre de tuiles bien positionnées sont affichés.

Vous pouvez aisément naviguer entre l’interface de création des jeux de données et de l’interface de jeu grâce à un lien, situé sur la gauche dans le bloc des explications et consignes.
## Bon jeu !
 
 
NB : Le tirage de l’emplacement des imagettes est aléatoire. Certaines configurations de jeu sont impossibles à résoudre et peuvent quand même être proposées. Vous ne pourrez donc pas résoudre le taquin, nous nous excusons pour cette gêne, et essayons de la résoudre le plus rapidement possible. 


# Sources
Imagettes pour le taquin-création et le taquin-jeu : flux wmts de Géoportail   
Fonction utilisée pour l'algorithme de tirage aleatoire : source https://www.codegrepper.com/code-examples/javascript/javascript+randomly+shuffle+array
