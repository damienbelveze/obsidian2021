---
title: Plan de gestion des données
subtitle:
author: Damien Belvèze
date: 20210506
link_citations: true
aliases: [DMP, PGD, Plan de gestion de données, data management plan]
tags: [données_recherche]
---

Document [[formaliser|formalisant]] la manière dont les [[données de la recherche|données de la recherche]] recueillies à la faveur d'un projet de recherche vont être décrites, conservées (traitées = curated), ([[Anonymat|anonymisation]]), diffusées ou protégées. 
Depuis l'entrée en vigueur de [[Horizon2020]], les agences de financement, comme l'[[Agence Nationale pour la Recherche]] exige des chercheurs la fourniture de ce document 6 mois après la décision de financer le projet de recherche (et une version révisée à 24 mois)

> Les plans de gestion des données sont des éléments\-clé d'une bonne gestion des données. Un plan de gestion des données décrit le cycle de vie de la gestion des données qui seront recueillies, traitées et/ou générées \[...\].

(H2020 Programme Guidelines on FAIR Data Management in Horizon 2020)


Les PGD sont nés dans les communautés scientifiques. 
Dès les années 70, la NASA donnait des standards pour décrire, classer et conserver des images satellites (rapport technique de 1973)
Aspect patrimonial : ces données coûtent très cher à produire et étaient volumineuses à conserver. 
Aujourd'hui en France, le Plan de Gestion des Données est une étape nécessaire à tout projet de recherche comme l'indique le décret 2021-1572 (3 décembre[[@Decret20211572decembre2021]]) : 

> Les établissements publics et fondations reconnues d'utilité publique mentionnés au troisième alinéa de l'article L. 211-2 du code de la recherche définissent une politique de conservation, de communication et de réutilisation des résultats bruts des travaux scientifiques menés en son sein. A cet effet, ils veillent à la mise en œuvre par leur personnel de plans de gestion de données et contribue aux infrastructures qui permettent la conservation, la communication et la réutilisation des données et des codes sources.

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

## où trouver le template du document

livrable demandé de manière fixe 6 mois après le début du projet et de manière variable en fin de parcours (date indiquée dans le premier document)
possibilité de remplir les informations sur DMP Opidor et de télécharger le document

outils pour rédiger des plans de gestion des données : 

- [DSW](https://ds-wizard.org/)(Hollande + République Tchèque)
- [DMP Opidor](https://dmp.opidor.fr/plans/new) France
- [DMP tools](https://dmptool.org/) USA

## structure de base d'un DMP

- Décrire le jeu de données
- Documenter (fournir les info qui gravitent autour du jeu de données)
- stockage : 3/2/1 trois back-ups sur 2 supports différents dont 1 à distance
- exigences légales et éthiques : licences, RGPD
- Partage es données et conservation à long terme : ne pas confondre l'archivage et le stockage ([[archivage]] = migration des formats) - identifier l'entrepôt de données en fonction de la découvrabilité (un entrepôt disciplinaire est plus riche en métadonnées pertinentes)
- responsabilités

exemple de description de données, voir présentation de Cécile Arènes (DMP one tool with many applications[[@HuserDatamanagementplans2022]])

## plan de gestion de données structuré pour une lecture artificielle

PGD structuré = machine actionable

Intérêts du PDG structuré : 

- facilite la réutilisation automatique de l'information (par exemple dans les projets ANR)
- Encourage le recours aux identifiants pérennes (pour les contributeurs, les organisations et les partenaires, etc.)
- propose des entrepôts où déposer ses données (et des thesaurus ou des vocabulaires pour les décrire)
- identifie et liste les coûts relatifs à la gestion des données
- simplifie l'échange et l'automatisation des informations entre les services qui interviennent dans la gestion des données
- Permet de créer des DMP compatibles avec le format RDA DMP Common


Cette structure va légèrement changer. 
Opidor : machine actionable DMP : export du PGD en Json (en complément de la version en ligne du plan de gestion)

[instructions pour trouver et remplir un DMP structuré](https://github.com/OPIDoR/DMPOPIDoR/blob/dmpopidor-master/public/files/DMPOPIDoR/DMPOPIDoRV3_Guide_Utilisateur.pdf)

Voir [contenu d'une formation de l'INIST](https://www.inist.fr/wp-content/uploads/2022/01/Inist-CNRS_DMP-OPIDoR_Modele-plus-structure_2022-01-27_PDF.pdf) (février 2022) sur les DMP structurés


![[Inist-CNRS_DMP-OPIDoR_Modele-plus-structure_2022-04-05_PDF.pdf]] : version avril 2022 de la présentation d'Yvette Lafosse et Laurent Rassinoux (INIST-CNRS, intervenants OPIDOR)


La partie rédigée est plus complète dans le modèle structuré (lien avec les référenciels, les langages de métadonnées)
référentiels communs au modèle classique et modèles spécifiques au modèle structuré.

[Liste des référentiels](https://dmp.opidor.fr/static/about_registries)

![](DMP_struc1.PNG)


Modèle structuré de Sciences Europe (choisir la version française ou anglaise de Sciences Europe)
Organisé en 12 questions - respect des principes FAIR

Dans la partie information générale, commune avec le modèle classique, sélectionner le nom du projet ANR dans le formulaire pour les faire entrer dans le DMP
Dans l'anglais contributeurs on peut rajouter une autre personne ou organisation qui contribue à la gestion des données. Les rôles seront attribués automatiquement

onglet concernant les produits de recherche (images, jeu de données, logiciels, corpus de textes, etc.).
entrer chaque produit de recherche.

Dans l'onglet Rédiger, on va répondre aux mêmes questions pour chaque produit de recherches
ajouter des mots-clé libres et des mots-clé issus de thésaurus comme celui du thesaurus de l'INRAE

attribut sujet lié au thésaurus INRAE
indiquer la personne contact pour la description des données

indiquer l'identifiant pérenne du produit de recherches
indiquer s'il s'agit de données personnelles ou des données sensibles il faut l'indiquer.

indiquer si les données qu'on réutilise ont un coût (par exemple coût de stockage de données anciennes).
sélectionner le plateau technique qu'on veut utiliser
sélectionner dans la liste la personne qui va être responsable de la collecte de données. 
Indiquer le standard de métadonnées qui va être utilisé (Darwin Core, Dublin Core)

pas de référentiel à ce jour pour le code éthique. on peut rajouter par exemple le nom du DPO, personne ressource pour la protection des données. 

choix dans une liste fermée de l'entrepôt dans lequel on va déposer ses données et choix de la licence du dépôt. Indiquer l'URL. 
Liste des services d'archivage pérenne. 

Les contributeurs vont voir leur rôle augmenté de la fonction qu'on a sélectionnée dans la rédaction du PGD.

Le DMP structuré permet de visualiser très vite les contributeurs avec leur rôle et les éléments de coût. 

possibilité d'exporter le PGD en Json pour faciliter les échanges entre machines. 
Format par défaut (format plus riche mais moins interopérable que le format RDA)
On échange plus facilement en [[format RDA]] avec d'autres systèmes d'information. 
On pourra bientôt importer des PGD d'une plateforme étrangère à OPIDOR, grâce au format RDA
Json permet d'intégrer le DMP dans une [[base de données]] en SQL

On ne peut pas avoir plusieurs personnes contact pour un même produit de recherche, mais l'ensemble des personnes contributrices peuvent être mentionnées dans la description du produit de recherche.

Dans le DMP, il faut planfier les coûts de conservation des données à venir. 

Le propriétaire et les éventuels co-propriétaires peuvent ajouter des contributeurs
3 rôles (au sens informatique) : 
- propriétaire
- co-propriétaire
- éditeur
ne pas confondre les collaborateurs du projet et les contributeurs du DMP. 

Plus d'infos sur la FAQ d'Opidor https://opidor.fr/category/dmp-faq/

exemple de DMP machine actionable conçu pour les projets OpenAire : [argos](https://argos.openaire.eu)

# Accompagner les chercheurs à la rédaction d'un PGD

éviter le syndrôme du *congélateur de données* (il faut qu'il y ait une panne sur un entrepôt pour qu'on se pose la question de ce qui s'y trouve)


L'incitation des financeurs est déterminante, mais les chercheurs peuvent venir de leur propre impulsion ou devancer cette injonction en posant ce type de questions :

![](questions_donnees.png)
(source[[@BraccoCommentmonterservice2021]])

démystifier la création d'un DMP en mettant en pratique sa rédaction. 

## relire les projets de financement à l'aune de la [[science ouverte]]

nécessité une collaboration avec le service en charge du montage de ces projets.
Vérifier que le projet de financement prévoit bien la conservation, la gestion et le partage des données
Pour cette relecture, se service du [guide](https://zenodo.org/record/3769954) de Cécile Arènes et Laëtitia Bracco

## ateliers de relecture de PGD

(source: Café [Renatis](https://www.canal-u.tv/chaines/renatis/cfe-renatis-retours-d-experience-accompagner-a-la-redaction-de-pgd))

relecture de plans publics.

On ne peut pas demander à chaque chercheur d'apporter son plan ; partir sur une idée de relecture d'un PGD public sur Opidor. 
Exemple avec le [Plan de gestion de données Atlas de Joseph Lamarange](https://dmp.opidor.fr/plans/3354/export.pdf)
création sur cette base d'un faux DMP
atelier de relecture de 2 heures (avec trois sous-groupes qui se répartissent le travail)

Mise à disposition d'une grille de relecture de métadonnées. Cette grille détaille tous les contenus. cela permet aux apprenants de cocher au fur et à mesure la qualité des informations fournies. 

chaque atelier réparti en 3 sous-groupes. Un animateur présent dans chaque sous-groupe. 
période de restitution en fin d'atelier. 


## formation en autoformation via Doranum

[grille de relecture des PGD (modèle ANR)](https://doranum.fr/wp-content/uploads/Grille-relecture-PGD-Modele-ANR-V3.pdf)
utiliser cette grille pour mettre en place des ateliers

pouvoir accompagner les chercheurs sur des questions liées à des contenus spécifiques et pour lesquels ils ne vont pas trouver de réponses sur des modules d'auto-formation qui restent assez généraux.

Faire ressentir que la rédaction d'un PGD n'est pas un acte adminstratif mais une pratique de chercheur/se

## dispositifs de formation à destination des doctorants

 - formations doctorales
 - déplacements en labo
 - formations lors d'événements sur les données de la recherche

voir formation de l'université Toulouse Jaurès (formation en hybride, formation en présentiel à 6 et 24 mois + auto-formation sur Moodle)

![](competences_PGD.png)

en vue : parcours pour les porteurs de projet + parcours sensibilisation ouvert à l'ensemble des chercheurs de l'établissement.

problème soulevé : données imprimées dans les thèses, dynamique lancée par le SCD pour résoudre ce problème. 
Rencontre avec les informaticiens, le service valo, les juristes, l'archiviste, le DPO.
Chaque corps de métier donne les formations qui le concerne. Tout ce qui est RGPD va être donné par le DPO, tout ce qui est légal par les juristes et tout ce qui est informatique par la DSI. Les facilitateurs et les coordinateurs sont les bibliothécaires.

### jeux sérieux

[GOpenDore](https://www.inist.fr/nos-actualites/jeu-gopendore-telechargement/)

[Faut pas s'en FAIR](https://www.inist.fr/nos-actualites/faut-pas-sen-fair-sur-les-donnees-de-la-recherche/)

