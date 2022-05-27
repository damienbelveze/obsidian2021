---
title: Données de la recherche

subtitle:
graphics: yes
author: Damien Belvèze
date: 20210505
link_citations: true
aliases: [research data, données de recherche, données de la recherche, données issues de la recherche]
tags: [données_recherche]
---

<!-- header-includes : |
   \usepackage{graphicx}
-->

# cycle de vie de la donnée

- Gestion
- Analyse
- Diffusion
- Archivage

# Hétérogénéité des données de la recherche

toute donnée récoltée dans le cadre d'un projet de recherche. Définition de l'OCDE de 2007 ([[@Rebouillatpartagedonneesvu2021]]) :

> enregistrements factuels (chiffres, textes, images et sons), qui sont utilisés comme sources principales pour la recherche scientifique et sont généralement reconnus par la communauté scientifique comme nécessaires pour valider des résultats de recherche

ce terme exclue dont les [[cahiers numériques|carnets de laboratoire]], les analyses préliminaires, les [[preprint|preprints]], les working papers, les objets matériels pouvant être échangés entre collègues.

distinctions possibles entre les types de données : 

-  méthode de collecte
-  degré d'affinage (données brutes > données dérivées)
-  données sources / données produites (Schöpfel)

autre distinction, par type de collecte : 

- données issues de l'observation
- données issues de l'expérimentation
- données issues d'une simulation
- données issues d'une dérivation ou d'une compilation (cf. [[Fouille de texte]])

Les données n'existent que par rapport à un contexte (notamment disciplinaire mais aussi en fonction d'un projet de recherche) et prennent sens en fonction de ce contexte ([[@Rebouillatpartagedonneesvu2021]])

> Leonelli (2015), philosophe des sciences et spécialiste des données de la recherche, écrit qu’il n’existe pas de données en elles-mêmes. Elles ne sont pas définies selon leurs propriétés intrinsèques mais selon leur fonction au sein de processus de recherche particuliers. Leonelli propose ainsi de considérer les données comme des produits de la recherche collectés, enregistrés et diffusés dans la perspective d’être utilisés ensuite comme preuve d’une théorie scientifique au sujet d’un phénomène particulier

Les sciences de l'information ont la particularité de comprendre dans leur réflexion sur leurs données, la nature complexe et dépendante de leur contexte de production, ce qui n'est pas forcément le cas dans les autres sciences.

Les données de la recherche s'inscrivent dans la catégorie plus large des inscriptions ([[Bruno Latour]]) : objets intermédiaires des savoirs produits en amont de la publication.

![](data_narrative.jpg)

## nettoyage des données

moins on maîtrise l'origine des données, et plus il faut passer du temps à les nettoyer : cas de l'open data. Extraire de l'information présente dans plusieurs tables à partir d'un attribut pivot. 
Nécessité de faire une vérification initiale des données pour ne pas se tromper de fichier ou de filtre.

prendre en compte les limites des données, avant de les exploiter. 


\begin{figure}
\begin{minipage}[t]{.4\linewidth}
    \begin{center}
       \includegraphics[width=6cm]{data_pyramid1.png}
       \caption{pyramide ideale}
    \end{center}
\end{minipage}
\hfill
\begin{minipage}[t]{.4\linewidth}
    \begin{center}
       \includegraphics[width=6cm]{data_pyramid2.png}
       \caption{pyramide effective}
    \end{center}
\end{minipage}
\end{figure}


# partage des données

Dans le cadre de la loi sur la République Numérique, le législateur a inscrit le fait de préempter les données de la recherche issues de financements publics pour éviter la captation de ces données par des opérateurs privés (comme ça a été le cas avec les publications). Le chercheur qui collecte des données n'a donc pas de propriétés sur elles. Le partage des données n'engage donc pas cette propriété. 

## données et perceptions

séparation data / capta

"data are the new oil" : contrairement au pétrole, toutes les données ne se valent pas, il faut faire le tri pour des analyses efficaces
Les données ne parlent pas toutes seules. Ce sont des humains, avec leurs biais et leurs méthodologies parfois erronées qui leur donnent du sens. 

![[Pasted image 20211008101737.png]]


##  valeur scientifique des données : 

A quel point un jeu de données va faire avancer la recherche (cf. par exemple les données d'une étude clinique)

Dans une approche cumulative du savoir, l'accès aux données permet leur réutilisation à des fins de reproductibilité et garantit donc plus de transparence et d'efficacité dans la recherche.

Cet idéal de la science qui se partage est mis en difficulté par les nécessités de prééminer dans le champ scientifique pour continuer d'exister. 


## valeur symbolique des données : 

Dans la compétition entre laboratoires et chercheurs, les données sont une monnaie dans un marché de la réputation.
Les données sont jugées par les chercheurs très liés aux articles qui comptent dans cette économie de la publication. Leur partage en dehors de ce cadre ne fait pas vraiment sens pour une grande parties des chercheurs.

Cet aspect n'est pas de nature à motiver le chercheur à publier ses données. 

## valeur économique des données : 

coût associé à leur production (un séquençage de génome = 1500 euros) mais aussi rentabilité de leur monétisation

Les financeurs insistent sur le levier de [[croissance]] que représenterait un accès facilité aux données de la recherche (concept [[libéralisme#Néo-libéralisme|néo-libéral]] d'économie de la connaissance).

Pour les plateformes de publication, les données constituent une valeur commerciale importante : l'hébergement de ces données permet de compléter le workflow de la publication en dehors duquel il sera de plus en plus difficile aux chercheurs de se tenir ([[@brembsReplacingAcademicJournals2021]]. 
Ne pas choisir des solutions propriétaires pour héberger ses données dans la mesure du possible. 
L'importance pour les chercheurs de maintenir des standards en matière de partage et de diffusion des données réside dans la capacité qu'ils se réservent de substituer un acteur plus éthique à une firme qui s'avèrerait trop cupide ou trop intrusive (typiquement Elsevier), voir à ce sujet l'article [[stratégie de publication]]

Pour en savoir plus voir [[partage des données de recherche]]


## l'enjeu scientifique du partage des données

Réutiliser des données anciennes permet d'agrandir son [[échantillon vs population|échantillon|échantillon]], particulièrement faire des analyses de données à partir de données compilées augmenter la force statistique de l'étude[[@wilsonSharingBiologicalData2021]]. 

> Researchers can build on previous studies to corroborate or falsify their findings rather than repeating the same experiment





# la conservation et le partage des données. 

Le [[Stockage des données de la recherche]] a un coût, c'est pourquoi il n'est pas systématique qu'elles soient conservées au delà de leur valorisation par la production d'un [[articles scientifiques|article scientifique]] 


