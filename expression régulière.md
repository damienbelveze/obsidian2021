---
title: 
subtitle:
author: Damien Belvèze
date: 28-10-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: []
---

Comment remplacer des liens par un texte de lien cliquable

Voici un type de lien. 
``
<a href="https://doi.org/10.1107/S0021889807056944">https://doi.org/10.1107/S0021889807056944</a>
``

le texte du lien correspond à l'URL. Il faudrait que ce texte soit doi

ouvrir notepad++

dans la dernière partie du lien 

``
">https://doi.org/10.1107/S0021889807056944</a>
``

remplacer l'URL par doi au moyen d'une expression régulière : 

">https:\/\/doi.org\/\[a-zA-Z0-9./()-]+\</a>

ne pas oublier le **+** pour que la recherche s'effectue sur tous les caractères entre **doi.org\/** et **<\/a>**

![notepad](notepad_regular_expression.png)


cliquer sur remplacer tout. 


# bibliographie

