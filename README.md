# TP Initiation GIT

Bienvenu(e) sur Github !

Je vous fais vite fait un petit récap de ce qu'est **Git** :
> Git est un outil pour versionner vos projets. Vous envoyez votre projet dans des **repository** (similaire à des dossiers) sur des platforms tel que Github, Gitlab ou Gitea dans le cas d'YNOV. Ainsi vous pouvez partager ou encore travailler à plusieurs sur vos projets.

Dans ce TP, vous appliquerez les notions vu précédemment. Ainsi vous comprendrez un peu mieux le fonctionnement des commandes.

Le TP se fera en 2 parties. Dans la première, vous manipulerez sur un repository seul pour que vous vous familiarisez avec l'outil. Dans la seconde, vous serez en groupe sur un seul repository.

---
## Sommaire

- [Haut de page](#tp-initiation-git)
- [Sommaire](#sommaire)
- [TP Partie 1](#partie-1---familiarisation)
    - [Objectif](#objectif)
    - [Création du repository](#création-de-votre-repository)
    - [Manipulation](#manipulation)
- [TP Partie 2](#partie-2---travailler-en-groupe)

# Partie 1 - Familiarisation
## Objectif
L'objectif de cette partie est de vous familiarisez avec l'outil **Git** afin de comprendre son fonctionnement et de pouvoir l'utiliser dans des projets de groupe.

## Création de votre repository
Sur **Gitea**, vous pouvez créer un nouveau repository avec le bouton suivant :\
![](./images/create_repo.png)
> Il se situe en haut à droite de la page.

Appelez votre repo **tp-git-initiation**

Une fois votre repo de créer, nous pouvons commencer le TP.

## Manipulation
> En cas de soucie, une doc récapitulative se situe [ici](./doc/).\
> À chaque étape, vérifiez votre repo via Gitea pour confirmer les modifications.
1. Cloner votre repository.
2. Créer un fichier quelconque dans le dossier du repository sur votre pc.
    - Un dossier a du être créer à l'endroit où vous avez cloné votre repo.
3. Ajouter ce fichier à votre repo (il doit apparaître sur le repo Gitea 👀).
4. Recréer un autre fichier que vous allez ajouter aussi à votre repo.
5. Maintenant, il faut **revert** votre commit.
    - L'objectif et de revenir un pas en arrière, donc l'étape 4 sera annulé.
    - Vous devez avoir à ce point, seulement le fichier de l'étape 3 dans votre repo.
6. Créer une branche et sélectionner la.
7. Effectuer un commit (création d'un fichier).
8. Faites un merge vers la branche **main** .

Bien, maintenant que vous avez fait cette première partie en étant seul, vous allez vous mettre un peu plus dans la plus grande utilisation de Git : un travail de groupe.

# Partie 2 - Travailler en groupe