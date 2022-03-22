---
title: Web of Science
subtitle:
author: Damien Belvèze
date: 06-10-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: [WOS, WoS]
tags: [bibliométrie]
---

base de données [[bibliométrie|bibliométrique]] mise en place par l'ISI (institut créé par Eugène Garfield, le "père de la bibliométrie" en 1956)


Combien de publications de Gérald Bronner ont été indexées dans le WOS ? 

![nombre publications](recherche_author.png)

Résultats : 24 publications

Quels sont les travaux de Gérald Bronner qui ont fait l'objet de citations ?

Combien de publications de Gérald Bronner ont-elles été citées d'après le web of science

![nombre citations]()

chercher par nom et initiale (BRONNER G.)

![cited references](cited_references.png)

chercher par structure moléculaire

importer un fichier en .mol (par exemple depuis chemspider)

![recherche structure](recherche_structure.png)

pas de thésaurus, réduire la recherche aux topics (titre, résumé, nom d'auteur, descripteurs) : "Searches title, abstract, author keywords, and Keywords Plus"

Recherche par auteur

recherche avec [[ORCID]]
Adinel Gavrus : **[0000-0002-5444-0445](https://orcid.org/0000-0002-5444-0445)**
- 47 résultats
- avec le nom Adinel Gavrus : 14 résultats / Gavrus A. : 48 résultats

# Recherche avancée

TS="information literacy" AND TS=("disinformation" OR "misinformation") AND PY="2010-2020"

ramène 73 résultats. 
On peut analyser ces résultats par discipline (analyse results). Sélectionner la vue "tree map"

![visualisation WOS](WOS_visualization.png)

Sélectionner une discipline qui nous intéresse (par exemple Behavioral Sciences : 9 résultats)

Liste des critères : 

-   AD=Address
-   ALL=All Fields
-   AI=Author Identifiers
-   AU=Author
-   CF=Conference
-   CI=City
-   CU=Country/Region
-   DO=DOI
-   ED=Editor
-   FG=Grant Number
-   FO=Funding Agency
-   FT=Funding Text
-   GP=Group Author
-   IS=ISSN/ISBN
-   OG=Organization - Enhanced
-   OO=Organization
-   PMID=PubMed ID
-   PS=Province/State
-   PY=Year Published
-   SA=Street Address
-   SG=Suborganization
-   SO=Publication Name
-   SU=Research Area
-   TI=Title
-   TS=Topic
-   UT=Accession Number
-   WC=Web of Science Category
-   ZP=Zip/Postal Code

trouver tous les articles sur les amphibiens parus dans Nature

SO=Nature AND TS=Amphibian*

## organisation

enhanced organization (OG)
OG=(Universite de Rennes 1)
La requête (OG = (Universite de Rennes 1)) AND TI=crypto* permet d'obtenir 37 résultats
Avec une requête identique sur HAL Rennes 1, on obtient un nombre de résultats équivalents (38 résultats)

Autre exemple : 

OG= (Universite de Rennes 1) AND TI= (biodivers* AND conserv*)

WOS = 4 résultats
Hal Rennes 1 = 3 résultats


# catégorie de mots-clé
Web of Science indexe **deux types de mots-clés :**

-   **Author Keywords :** les mots-clés que l'auteur a fourni pour la publication de son article,
-   **Keywords Plus :** les mots et les phrases récoltés par Web of Science dans les titres des articles cités.

![keywords plus](keywordsplus.png)


# accéder aux références d'un article

voir [[controverse sur l'ivermectine]]. 
Récupérer les références de l'[article](# Ivermectin: a multifaceted drug of Nobel prize-honoured distinction with indicated efficacy against a new global scourge, COVID-19), les intégrer à Zotero : est-ce que certaines correspondent à des études qui ont été rétractées ? 

![](WOS_references.png)

un article a été rétracté

![](retracted_zotero.png)

# facteur d'impact d'une revue

cliquer sur le nom d'une revue pour connaître son [[bibliométrie#facteurs d'impact|facteur d'impact]]

# Trouver des experts. 

on cherche à trouver des publications sur l'antimatière qui aient été signée par au moins un.e chercheur.se de l'institut Max Planck


# bibliographie

