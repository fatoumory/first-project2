Gestion De Projet IT

Pour un projet, d'abord définir la méthode de travail pour aller plus vite : L'efficacité



On va voir d'abord git pour travailler en groupe, agilité : Une façon de gérer une équipe, scrum, et qualité logicielle



GIT:

push, commit, init, add, pull, merge, branch, checkout, switch, clone, log



Au niveau de notre projet nous avons un fichier caché : .git qui représente notre BD



Quand on est dans le répertoire de travail et qu'on fait git add, on stocke notre projet dans le repo local



On a 3 zones : répertoire de travail, index, et repos local

git pull pour accéder au repo distant



CREATION

Méthode 1: git init

1. On crée le dossier localement : on fait **git init** pour créer le repo local .git
2. On configure le repo distant : **git remote add origin + le lien**
3. Si on veut ajouter tous les fichiers dans l'index : **git add. ou git -A**
4. On crée la branche locale main : **git branch -M main** du repo local
5. Si on veut enregistrer les fichiers de la zone de l'index à mon repo local : **git commit -m "la description de ce qu'on a effectué"**
6. Pour lier le repo local au repo distant et au branch main du repo distant : **git push -u origin main** ou **git push -set-upstream origin main**
7. Avant tout ça faire, **git config --global user.name "on précise le name", git config --global user.email "on précise l'email"** pour configurer le projet
8. **gitk** pour voir l'interface graphique



**NB : Toujours mettre des commit lors d'un travail en équipe sur GitHub**

**NB : Toutes ces commandes sont utiles si on a un projet déjà fait mais si c'est un projet vide, cloner directement le projet**



**Si on travaille à deux, toujours mettre pull pour éviter les conflits**

