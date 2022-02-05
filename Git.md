---
title: commandes de base de Git
subtitle:
author: Damien Belvèze
date: 18-11-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: [git]
tags: [programmation, code]
---

télécharger Git
Créer un répertoire sous github ou gitlab (on fera ici référence à Github)
aller à l'endroit où l'on veut télécharger le répertoire, MAJ+clic droit > ouvrir git bash here

![](git_bash_here.png)

dans ce terminal, pour coller des expressions, utiliser la touche inser

télécharger le répertoire vide créé

``````git
git clone repertoire.git
``````

pour initialiser ce répertoire comme étant un répertoire git (va ajouter un fichier caché .git) : 
``````
git init
``````

créer, modifier les fichiers. 
Pour visualiser les fichiers qui ont été créés/modifiés et ne sont pas encore dans le track de git : 
``````
git status
``````
ces fichiers à ajouter apparaissent en rouge

pour ajouter un fichier

``````
git add nomdufichier
``````
pour ajouter tous les fichiers créés ou toutes les modifications de fichiers
``````
git add -A 
``````
Pour préparer les fichier à l'envoi dans le répertoire distant (commettre)
``````
git commit -m "message indiquant la création ou la modification réalisée"
``````
Il est nécessaire de commettre avant d'envoyer des fichiers / modifications vers le répertoire

pour envoyer les modifs vers le répertoire
``````
git push -u origin
``````
pour lier un répertoire git à un répertoire
``````
git remote add origin liendurepository.git
``````
pour supprimer un fichier du track
``````
git rm fichier
``````
pour créer une branche à partir d'une branche existante : 
``````
git branch nomdelabrancheàcréer nomdelabrancheexistante
``````
une fois cette branche créée, l'envoyer sur le répertoire
``````
git push -u origin branchecréée
``````









# bibliographie

