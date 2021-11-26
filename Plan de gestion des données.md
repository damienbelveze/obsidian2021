---
title: Plan de gestion des données
subtitle:
author: Damien Belvèze
date: 20210506
link_citations: true
aliases: [DMP, PGD, Plan de gestion de données, data management plan]
---
#données_recherche

Document formalisant la manière dont les [[données de la recherche|données de la recherche]] recueillies à la faveur d'un projet de recherche vont être décrites, conservées (traitées = curated), ([[Anonymat|anonymisation]]), diffusées ou protégées. 
Depuis l'entrée en vigueur de [[Horizon2020]], les agences de financement, comme l'[[Agence Nationale pour la Recherche]] exige des chercheurs la fourniture de ce document 6 mois après la décision de financer le projet de recherche (et une version révisée à 24 mois)

> Les plans de gestion des données sont des éléments\-clé d'une bonne gestion des données. Un plan de gestion des données décrit le cycle de vie de la gestion des données qui seront recueillies, traitées et/ou générées \[...\].

(H2020 Programme Guidelines on FAIR Data Management in Horizon 2020)

Les PGD sont nés dans les communautés scientifiques. 
Dès les années 70, la NASA donnait des standards pour décrire, classer et conserver des images satellites (rapport technique de 1973)
Aspect patrimonial : ces données coûtent très cher à produire et étaient volumineuses à conserver. 

# Quelques chiffres sur les plans de gestion des données. 

Ces chiffres montrent à quel point il est urgent de "convertir" les chercheurs à la rédaction de plans de gestion des données : 

-   50 % des expériences sont considérées comme **non-[[reproductibilité|reproductibles]]**.
-   80 % des données produites ces 20 dernières années seraient **perdues**.
-   93 % des établissements d’enseignement supérieur n’ont pas de démarche de plan de gestion des données de la recherche.
-   90 % des chercheurs interrogés dans le cadre d’un sondage européen disent effectuer de manière individuelle le stockage, l’archivage ou la transmission de leurs données.
-   33 % de ces mêmes chercheurs n’ont jamais entendu parler des plans de gestion de données ou estiment qu’ils n’en ont pas besoin.
-   Plus de 80 % des données produites sont **stockées ailleurs que dans des entrepôts**.

(source : Cécile Arènes[[@ArenesRedigerplangestion2021]])


# Accès aux données, les avantages pour l'auteur : 


- conformité avec les exigences des financeurs de la SO
- transparence dans la production des résultats (reproductibilité)
- visibilité pour les chercheurs, notamment davantage de citations
- possibilités de collaboration

Bien évidemment la transparence favorise le taux de citations, les bénéfices sont liés entre eux. 

## avantage de citation pour les données liées et présentes dans des entrepôts

D'une publication à l'autre les données peuvent avoir des stauts différents : 

- ne pas être du tout accessible (pas de déclaration sur les données)
- être accessibles sur demande
- être accessibles dans la publication ou ses annexes
- être accessibles depuis la publication avec un lien qui renvoie vers un répertoire de données
- être accessibles depuis la publication avec un lien qui renvoie vers un répertoire de données mais avec des restrictions

![data availibility statement](data_citation_advantage.png)

Une étude de 2020, montre que les données accessibles depuis la publication avec un lien qui renvoie vers un répertoire de données ont un bénéfice de citation de l'ordre de 25% sur la moyenne des citations des articles appartenant aux autres groupes [[@Colavizzacitationadvantagelinking2020]]


# structure d'un plan de gestion de données

document structuré en 6 parties

- Décrire le jeu de données
- Documenter (fournir les info qui gravitent autour du jeu de données)
- stockage : 3/2/1 trois back-ups sur 2 supports différents don 1 à distance
- exigences légales et éthiques : licences, RGPD
- Partage es données et conservation à long terme : ne pas confondre l'archivage et le stockage ([[archivage]] = migration des formats) - identifier l'entrepôt de données en fonction de la découvrabilité (un entrepôt disciplinaire est plus riche en métadonnées pertinentes)
- responsabilités

Cette structure va légèrement changer. 
Opidor : machine actionable DMP : export du PGD en Json (en complément de la version en ligne du plan de gestion)


