---
title: FAIR
subtitle:
author: Damien Belvèze
date: 22-03-2022
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: [données de recherche]
---


Qualités des données de la recherche qui sont correctement conservées et font l'objet d'une [[Curation]] efficace : 

- Findable
- Accessible
- Interoperable
- Reusable

L'objet d'un [[Plan de gestion des données]] est de montrer comment ces principes vont être appliquées au jeu de données décrit dans le plan.

![[FAIR.png]]

![fair data principe](FAIR1.jpg)

# *Interoperable* : la question des formats ouverts

Dès 1965 en cristallographie, des chercheurs ont commencé 
format informatique interopérable (format CIF)
défis : formats peu usités JCAMP, mzML, nmrML
multiplicité des identifiants de molécules (CAS, SMILES, Inchi, Inchikey)

Dans les entrepôts on va plutôt utiliser inchi que CAS car pour accéder aux identifiants CAS il faut disposer de la base de données CAS Sci-Finder

2 journaux d'ACS demandent les données en format FID (format de données déjà travaillées)

# Evaluer l'application des principes FAIR

## présentation de FAIR EVA (Evaluator, Validator, Advisor)


Fernando Aguilar Gomez IFCA-CSIC, impliqué dans RDA (Research Data Alliance)
S'assurer de la qualité des données que l'on crée

"create a FAIRness evaluation"

![](CSIC1.png) \

![](CSIC2.png) \

Findable

![](CSIC3.png) \

Accessible

![](CSIC4.png) \

Interopérable

![](CSIC5.png) \

not only evaluate, but also validate (label) and advise

application modulaire faite de plusieurs composants, la solution est conçue pour être flexible et adaptable à différentes communautés scientifiques

cible : déposants de données, administrateurs de portails, financeurs

développé en Python, dispose d'une API et d'une interface web.
possible de lancer l'outil Python avec Docker

![](CSIC6.PNG)

![](CSIC7.PNG)

![](CSIC8.PNG)

![](CSIC9.PNG)

![](CSIC10.PNG)

ça fonctionne en localhost (localhost:5000)
on envoie le DOI de l'entrepôt

![](CSIC11.PNG)

Quand le score n'est pas de 100% on reçoit des recommandations pour améliorer la FAIRité des données. 
On peut exporter le bilan en PDF

possibilité selon l'entrepôt de départ de configurer le fichier config en indiquant par exemple où trouver les informations relatives à la licence (dans le cas de Zotero c'est dans dc.rights)

implémentation de l'API sur l'entrepôt du CSI

![](CSIC12.PNG)

intégration dans Jupyter

![](CSIC13.PNG)

difficulté de trouver le endpoint d'un repository, pour Zenodo, c'est sur le site https://zenodo.org/oai2d
pas de menu déroulant avec la liste des dépôts liés à leurs endpoints. Il faut fournir l'un et l'autre. 






