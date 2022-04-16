---
title: Comment stocker les données de la recherche
subtitle: Notes webinaire INIST / Service de la data UGA
author: Damien Belvèze
date: 20210525
link_citations: true
aliases: [stockage de données]
tags: [données de recherche]
---



Le stockage de données consiste à enregistrer des [[données de la recherche|données de recherche]] sur un support physique La sauvegarde de données consiste à créer une copie de ces données stockées
L'[[archivage]] de ces données consiste à rendre ces données accessibles et utilisables sur le long terme en en faisant la [[curation]] (lutte contre l'[[obsolescence des formats]] par des conversions successives dans le temps, [[règles de nommage]] et description permettant leur réutilisation dans le temps)

![[20210525_stockage_donnees_recherche.pdf]]


# Quelles vérifications faire avant de déposer un jeu de données

![[diffusion_donnees.pdf]]

- vérifier quelles données accepte l'entrepôt (certains entrepôts n'acceptent que les données issues des publicatons)

- vérifier que les données sont en format libre, sinon les convertir de leur format propriétaire natif vers un format libre. 

- Penser à la réutilisation de ces données : adopter un nom clair et un descriptif complet. 

- réfléchir aux métadonnées avec lesquelles on va décrire la ressource

- réfléchir à la licence qu'on va appliquer à ces données.

# Quel entrepôt de données utiliser

La question de l'entrepôt s'impose très vite, au moins au cours de la rédaction d'un [[Plan de gestion des données|Plan de gestion de données]]
pratique des collègues de Doranum et de l'Université Toulouse-Jean Jaurès : 

inciter d'abord au dépôt des données dans un entrepôt spécialisé (sciences humaines : Nakala) et sinon dans un deuxième temps, inciter au dépôt dans l'entrepêt recherche data gouv (ouverture prévue au printemps 2022)

[Re3data.org](https://www.re3data.org/) : annuaire des entrepôts de données institutionnels/ généralistes

code informatique : HAL (envoi du document vers Sotware heritage). Depuis 2018, quand on dépose du code dans HAL il est conservé dans Software Heritage (archive créée par l'INRIA ([source](https://www.ccsd.cnrs.fr/en/project/software-heritage-2/))

## Entrepôts utilisés à Rennes 1


| discipline | entrepôt |
|:---:|:---|
| code | HAL |
| BioInformatique | [GenOuest](https://www.genouest.org/) |
| Sciences Humaines | Nakala |
| Mathématiques | pas d'entrepôt, voir avec le [groupe RNBM](https://www.rnbm.org/category/le-reseau/groupes-de-travail/donnees-maths/) |
| environnement rennais | [Osuris](https://accueil.osuris.fr/) |
| Sciences de la terre | [data terra](https://www.data-terra.org/) |
| Sciences de la mer | [data ifremer](https://data.ifremer.fr/), [seanoe](https://www.seanoe.org/) |

entrepôts institutionnels

| institution | Pays | entrepôt | URL |
|:---:|:---:|:---:|:---:|
| Université de Lorraine | Lorraine | DOREL | https://factuel.univ-lorraine.fr/node/18396 |


# dépôt du code-source des logiciels

Software Heritage assure la conservation du code source des logiciels utilisés pour traiter les données à travers la plateforme HAL. 

>par défaut, un logiciel sans licence n'autorise personne à l'utiliser.
Une licence est donc essentielle pour permettre son usage, mais aussi à d'autres personnes de l'utiliser, le modifier et reverser à la communauté les évolutions 

(Source : Philippe Gauron, mail du 22/02/2022 sur Accès Ouvert)

Les licences recommandées par l'Etat français pour permettre la réutilisation du code produit par l'administration sont indiquées [sur le site data.gouv.fr](https://www.data.gouv.fr/fr/pages/legal/licences/)

Pour comprendre à quoi correspondent licences permissives et licences à réciprocité : 

   > **les licences permissives** qui ne protègent que la paternité des auteurs et limitent leur responsabilité. Elles autorisent la réutilisation, rediffusion, exploitation même commerciale ou modification de licence. Parmi celles-ci, on peut citer :
     pour les logiciels : les licences BSDL, Apache, CeCILL-B et MIT. Voir sur ce site une liste des licences disponibles.


   > **les licences avec obligation de réciprocité** qui obligent à conserver les conditions de la licence d’origine, et doivent la propager à toute œuvre dérivée. En particulier, elles peuvent restreindre l’utilisation commerciale des données et du code. Parmi celles-ci, on peut citer :
     pour les logiciels : les licences Mozilla, GNU GPL et CeCILL (voir à nouveau ce site)
 

(source: Céline Smith sur la liste Accès Ouvert, 21 février 2022, 17h15)

Voir aussi le [niveau de propriété intellectuelle](https://hal.archives-ouvertes.fr/hal-02399517/file/20191202_plaquette_pi_licences_V1.1.pdf) du code en fonction du statut du créateur.
Pour choisir une licence sous laquelle diffuser le logiciel, voir la présentation de Teresa Gomez-Diaz [[@Gomez-Diazlogicielsrechercheleurs2019]]


