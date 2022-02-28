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
#### Le Projet et ses objectifs:
L’objectif de ce mini-projet est de réaliser un «taquin» : son interface de jeu avec son web service associé,  de documenter un drag and drop efficace pour pousser les rangées de pions et de développer l’interface de construction d’un jeu de quinze imagettes (avec son web service associé).
#### Langages utilisés
+ HTML5, CSS3
+ JavaScript, AJAX
+ PHP, MySQL
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

METTRE LA PARTIE DU HUGO : manuel d'utilisation
Bravo, vous allez bientôt pouvoir commencer à jouer !

***

# Consignes
Vous devez d'abord rentrer un pseudo. Celui-ci doit faire entre 1 et 20 caractères.
Ensuite, séléctionnez un jeu parmi la liste proposée. Validez ! Vous pouvez commencer le taquin.

Si la disposition des tuiles ne vous satisfaits pas, vous pouvez re-mélanger les images grâce au bouton sur la droite "nouveau tirage".

Vous pourrez voir le nombre de coups que vous avez mis à réaliser le jeu. Une fois le jeu fini, vous avez également la possibilité de voir votre position dans le classement si vous êtes suffisament bien classé ! 

Vous pouvez aisément changer de page grâce à un bouton, situé lui aussi sur la droite.

Bon jeu !


# Sources
Imagettes pour le taquin-création et le taquin-jeu : flux wmts de Géoportail   
Fonction utilisée pour l'algorithme de tirage aleatoire : source https://www.codegrepper.com/code-examples/javascript/javascript+randomly+shuffle+array
