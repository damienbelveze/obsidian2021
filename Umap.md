---
title: Umap, l'éditeur de cartes interactives
subtitle:
author: Damien Belvèze
date: 20-12-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: [cartographie]
---


# Trouver des données sur Wikidata

![](cemetery.csv)

Ce fichier a été réalisé extrait de Wikidata (voir la requête sur [[Sparql#exemple de requête simple les cimetières de guerre allemands]]])

# formater le fichier téléchargé de Wikidata

clic droit sur la colonne D > "insérer une colonne après"
clic droit sur la colonne > textes en colonnes > utiliser l'espace comme séparateur
On obtient désormais deux colonnes, l'une avec la longitude (colonne D), l'autre avec la latitude (colonne E)
Umap repère les colonnes dont les entêtes commencent par lon et lat et les interprête comme des entête de colonnes dans lesquelles se trouvent les coordonnées géographiques décimales (48.5678 est correct mais pas 48,5678 ni 48°5678, veiller à ce que les valeurs présentes dans les colonnes soient bien formatées)
Colonne D : supprimer *Point(* avec la fonction chercher + remplacer (Ctrl+H)
Colonne E : supprimer la parenthèse fermante

# paramétrer l'affichage des données importées dans Umap

Si l'import du fichier ne se fait pas bien à partir du module d'import. Copier les valeurs avec leurs entêtes dans le module d'import, si c'est demandé, spécifiez qu'il s'agit d'un fichier en format CSV.

Des marqueurs devraient apparaître pour indiquer les lieux figurant dans le jeu de données. 

Créer un popup avec une description du marqueur : 

éditer le calque dans lequel ont été chargées les données. 
cliquer sur options d'interactions
conserver popup par défaut
Dans Gabarit du contenu de la popup, ajouter les entêtes de la colonne. 
\# = titre 1
\#\# = titre 2, etc. 
Pour insérer une image : {{{entête de la colonne}}}

Pour notre fichier cela donne : 

\# {itemLabel}
{{{image}}}

Pour visualiser les changements, enregistrer les modifications et désactiver le mode édition

![carte interactive](umap1.png)

# exercice. 

Réaliser un calque supplémentaire avec des données sur les cimetières de guerre en Allemagne



# bibliographie

