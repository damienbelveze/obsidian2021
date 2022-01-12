---
title: éditer des requêtes sur Wikidata avec le langage Sparql
subtitle:
author: Damien Belvèze
date: 20-12-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: []
---

langage d'interrogation pour chercher des entités liées, ce langage d'interrogation a été mis au point par le consortium World Wide Web et sert de langage d'interrogation à [[Wikidata]]

Analyse d'une requête en Sparql sur Wikidata (https://query.wikidata.org)

# exemple de requête simple : les cimetières de guerre allemands

![](sparql_query.png)

\#cemeteries
SELECT ?item ?itemLabel ?place ?coord
WHERE
{
  ?item wdt:P31 wd:Q1241568 .
  ?item wdt:P137 wd:Q708567 .
  ?item wdt:P625 ?coord.

   SERVICE wikibase:label { bd:serviceParam wikibase:language "en". }
}

première ligne : commentaire (titre de la requête)

SELECT : indique les informations issus des résultats à faire figurer en colonne, en l'occurrence le numéro de l'élément wikidata, son titre, l'endroit assigné à l'élément, et les coordonnées géographiques de l'endroit

WHERE {} permet de donner les critères de recherche. 

?item wdt:P31 wd:Q1241568 : on retrouve à cet endroit le triplet item propriété valeur : tous les items qui ont pour propriété (est une instance de) la valeur "cimetière militaire"

Même chose à la ligne suivante : 

?item wdt:P137 wd:Q708567 . 
tout item qui a pour propriété (est opéré par) l'agence "Volksbund Deutsche Kriegsgräberfürsorge"
  
?item wdtP625 ?coord. 
tout item qui dispose de coordonnées géographiques

Les résultats sont téléchargeables

![](sparql_results.png)

Pour avoir en plus les images, on peut ajouter dans le Where {} la condition suivante : 

  ?item wdt:P18 ?image.
  
  et ajouter ?image après SELECT

# bibliographie

