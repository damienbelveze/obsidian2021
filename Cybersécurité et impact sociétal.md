---
title: impact social de la cybersécurité
subtitle: plan de cours pour 20 heures étudiants
author: Damien Belvèze
date: 04-06-2022
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: [vie_privée]
---


# introduction

Le présent document trace les grandes lignes de la forme que pourrait prendre un cours hybride de 20 heures comportant 5 heures de cours en face à face.
Ce cours est à destination de 60 étudiants de troisième année de licence en informatique. 

# Compétences visées :

- rédiger des notes de lecture  
- réaliser un travail collaboratif à deux niveaux (sous-groupe et groupe entier)  
- chercher de la documentation pluridisciplinaire sur un sujet donné  
- utiliser des formats ouverts, interopérables  
- utiliser des outils collaboratifs respectueux de la vie privée  

# Connaissances : 

Le cours porte sur l'enjeu que représente la préservation de la vie privée en ligne et la réception des outils conçus pour protéger cette vie privée par le grand public.

# Objectifs du cours : 

Réaliser un site sur la thématique sous la forme d'un graphe public de notes de lecture. 
Pour ce faire, n'utiliser que du logiciel libre -y compris pour le travail collaboratif-
- Gestion des références bibliographiques : [Zotero](https://zotero.org)  
- Edition des notes : Zotero et [Zettlr](zettlr.com/)  
- outil de travail collaboratif et de sauvegarde : git (et gitlab ou [framagit](https://framagit.org))  
- édition du graphe de notes : [Cosma](https://cosma.graphlab.fr/)  


# Etapes : 

- Exposé de la thématique (cybersécurité, [[Vie privée|vie privée]])  
- carte mentale avec les étudiants sur les concepts principaux  
- constitution de groupes thématiques  
- téléchargement d'un nombre déterminé de textes depuis une bibliothèque en ligne par chaque groupe  
- lecture et annotation des textes  
- rédaction à partir des notes prises d'une fiche de lecture selon la méthode THOMAS (voir ci-dessous)  
- recherche de nouveaux textes sur l'un des sujets retenus  
- formatage des notes de lecture et chargement dans un entrepôt git  
- ajout de liens vers d'autres fiches de lecture en cours de construction  
- ajout de commentaires sur d'autres fiches de lecture (pour intégration ou non selon le jugement de l'autre groupe)  


# Descriptif du cours

La pandémie de COVID-19 a accéléré la production de cours hybrides au sein de l'université. Ces cours toutefois ont la plupart du temps pour caractéristique commune de proposer aux étudiants des synthèses suivies d'activités ou d'exercices. 
Les dispositifs dans lesquels les étudiants sont les principaux producteurs de contenu et où les enseignants jouent le rôle d'accompagnants et de vérification scientifique de ces contenus. 

Nous proposons ici un dispositif qui permet aux étudiants d'appréhender un sujet en leur faisant construire eux-mêmes le contenu de la formation. Le sujet porte sur le futur de la vie privée dans les activités en ligne et l'impact social des moyens mis en oeuvre pour éviter la disparition de cette vie privée.

## une posture renouvelée des enseignants

Le ou les enseignants qui administrent ce cours ne produisent pas eux-mêmes les contenus. 
Les fonctions qu'ils endossent sont les suivantes : 
- ils organisent le groupe classe en sous-groupes de 4 personnes au maximum en aidant ces sous-groupes à définir à travers un sous-thème (par exemple, l'appropriation par le grand public des outils de chiffrement) leur champ d'investigation particulier.  
- ils sélectionnent un ensemble de texte qui vont être synthétisés en fiches par leurs étudiants  
- ils donnent des pistes pour trouver d'autres textes en lien avec le sujet  
- ils présentent les différentes étapes du travail  
- ils assurent une formation basique aux outils à utiliser ou bien mettent à leur disposition des outils d'autoformation   
- ils répondent à travers un espace de discussion (à déterminer, voir ci-dessous) aux questions techniques posées par les étudiants  
- ils vérifient que tous les sous-groupes sont actifs et relancent l'activité de ceux qui ne le sont pas assez.  
- ils assurent une brève relecture des contenus qui ne saurait être exhaustive. Des expériences précédentes montrent que garantir une validité scientifique de tous les contenus présentés dans ce genre de dispositif n'est pas possible.   

## susciter l'engagement étudiant

Des expériences récentes montrent que les étudiants ont tendance à assurer une contribution minimale pour obtenir les crédits du cours[[@pudelkoConcevoirEncadrerWiki2019]]. Il est nécessaire d'être explicite sur ce qu'est ce niveau de contribution minimale : rédaction d'une fiche à partir d'une référence assortie de n contributions sous la forme de liens vers d'autres fiches ou de commentaires signés déposés sur d'autres fiches que celles qu'ils rédigent.
Les commentaires ne seront pas visibles au public. 

Les étudiants sont réticents à rendre le produit d'écriture visible aux autres, ils redoutent également de porter une appréciation sur le travail de leurs condisciples (cf.[[@pudelkoConcevoirEncadrerWiki2019]] et [[@bourbeillonAgirEnsembleDans2022]]). 
Il est possible de leur demander de faire des liens à partir des fiches sur lesquelles leur sous-groupe travaille vers les fiches d'un autre sous-groupe. On peut également leur conseiller de laisser des suggestions d'enrichissement en lien avec les fiches dont ils sont responsables sur les fiches des autres sous-groupes. 

Puisque l'idée est de lier par des liens hypertextes les fiches entre elles, il est important que les étudiants acquièrent une connaissance d'ensemble des fiches (et une connaissance d'ensemble des textes qui servent de matière première aux fiches de leur sous-groupe)

## L'écriture réflexive : une manière d'apprendre

Le dispositif présenté rejoint la perspective du *writing-to-learn* de Bereiter et Scardamalia [[@bereiterLearningWritingReading1984]]. 
L'étudiant est invité non seulement à résumer un texte mais à évaluer son apport pour une problématique particulière (par exemple l'apparent conflit entre respect de la vie privée et sécurité collective), ainsi qu'à se positionner par rapport à ce texte (pour ou contre en argumentant et en nuançant). Ce processus permet à l'étudiant en posant ses idées sur le papier de prendre conscience des apories auxquelles le mènent ses idées préconçues. Cette découverte de ses propres failles de raisonnement vont l'emmener à chercher dans les textes proposés ou les écrits de leurs camarades de quoi surmonter ces contradictions. 

L'écriture réflexive à plusieurs aide en outre les étudiants à s'habituer à ce que des pairs relisent, commentent et au besoin critiquent leurs propres écrits [[@pudelkoConcevoirEncadrerWiki2019]] : 

>Il s’agit tout d’abord d’aider les étudiants à reconnaître que leurs idées, une fois externalisées, peuvent être améliorées, synthétisées, transformées, critiquées, etc., autrement dit, que leurs idées, tout comme celles des autres, peuvent et doivent faire objet d’un travail de transformation continue, à la fois individuel et social

### Fiches rédigées en suivant la méthode THOMAS

Pour sortir de la fiche de lecture classique qui résume essentiellement le texte lu et donner davantage l'occasion à l'étudiant de placer cette lecture en contexte et de se positionner par rapport à elle, nous proposons aux étudiants de rédiger ces fiches selon le modèle [[Méthode THOMAS|THOMAS]], un modèle au départ conçu pour des étudiants en histoire [[@agmonTeaching2018]]
Nous avons traduit ci-dessous en français les énoncés de la méthode tels que formulés par Danna Agmon : 

#### T(opic) - le sujet
quel est le sujet du document
dans quel contexte a t-il été produit
qui l'a écrit ? quelle est son [[expertise]], quelles sont ses qualifications ? Qui l'a publié ?

#### H(istoriography) - contexte de la discussion

Le H de THOMAS concerne **Historiographie**.  Dans quel débat cet article intervient-il ? quel parti pris ou argument remet-il en question (ou renforce t-il) dans cette discussion en cours ?

#### O(rganization) - construction du document

A t-on affaire à une construction thématique, chronologique ? Le plan suivi présente t-il une forme d'originalité ? Qu'est-ce qu'on peut apprendre d'une lecture attentive de la table des matières ou de l'organisation interne des chapitres sur l'agencement de l'argumentation ? 

#### M(ethodology) - méthode 

Quelle méthode utilise ce document. Quelles sont les sources sur lesquelles il s'appuie ? 

#### A(rgument)

Le A de THOMAS est l'Argument. Enoncer l'argument principal souvent n'apporte que peu d'information, on doit considérer au delà-de ça comment les réponses aux premières questions (THOM) dessinent l'argumentation 


#### S(o what)

Le S de THOMAS signifie "So what" (et alors ?). On désigne ici les enjeux ou l'importance du document pour soi-même. 
Pour les lecteurs non spécialistes qui ne s'intéressent pas depuis longtemps aux spécificités du sujet ou même de l'argument, pourquoi lire ce document serait-il utile, pourquoi cela m'a été utile à moi ? C'est là que la conversation devient généralement la plus intéressante

## une approche réflexive mais partagée

### la collaboration à l'intérieur des sous-groupes

Le sens d'un texte peut s'éclairer dans la reformulation individuelle de sa problématique et l'expression de ce qu'il nous apporte, mais également au contact de pairs.
La note (en réalité une fiche de lecture) est le produit d'un sous-groupe. 
Un étudiant compte donc ses premiers relecteurs dans le sous-groupe auquel il appartient. Son travail doit refléter aussi l'avis des autres. 
Chaque étudiant étudie un texte et est l'auteur d'une fiche, mais collabore en premier lieu aux fiches des autres membres de son sous-groupe. 

### Quel outil pour susciter la collaboration entre les sous-groupes

On peut aussi parler de collaboration entre étudiants au niveau de l'ensemble du groupe. 
L'outil de collaboration éditoriale doit être libre et faciliter cette collaboration à plusieurs niveaux (entre sous-groupes et au niveau du groupe entier). 
D'après Bourbeillon et Martel [[@bourbeillonAgirEnsembleDans2022]], pour gérer le travail collaboratif, les étudiants ont majoritairement recours à des outils qu'ils maîtrisent déjà et qui assez généralement sont propriétaires, et par dessus le marché, particulièrement mal adaptés au sujet du cours. Google notamment, qui édite l'outil de travail collaboratif Google Drive, un outil plébiscité par les étudiants pour leurs travaux de groupe, s'est à maintes reprises distingué comme une ressource très peu respectueuse des données personnelles de ses utilisateurs.
Il faut donc opter pour un outil que les étudiants n'utiliseront pas seulement pour l'édition finale de leurs texte -les travaux préliminaires étant réalisés sur Google Drive- mais tout au long du travail de production. Git permet de répondre à cette demande et est adapté au public d'étudiants en informatique qui ont par ailleurs des tâches de développement. Le choix d'un outil au départ associé au développement de logiciels permet aussi de nuancer cette division un peu abstraite entre le code et le texte qui a été renforcée par l'apparition des traitements de texte à la fin des années 80. 
Le choix de Git comme outil de versionnage et de travail collaboratif pose trois questions principales : quel entrepôt choisir (sachant que Github appartient à Microsoft, également peu respectueux des libertés de ses utilisateurs) et que l'instance de Gitlab développée notre université n'est utilisable que pour des projets qui ne sont pas publics (le graphe de notes doit pourtant faire l'objet d'un affichage public sur une page web). [Framagit](framagit.org/) (instance de Gitlab hébergée par Framasoft, une association qui fait la promotion du logiciel libre en France) pourrait apporter une réponse intéressante à cette première question. 
La seconde question concerne la structuration de l'entrepôt : faut-il prévoir un *branch* par sous-groupe ou bien partir d'emblée sur une architecture la plus  horizontale possible, censée favoriser davantage de collaboration (lecture, révision, commentaires) au delà des frontières des sous-groupes ?
Une troisième question interroge la place de Git dans le cursus de ces étudiants : sachant que ce module s'adresse à des étudiants de troisième année de licence : auront-ils déjà été formés à l'outil ou bien faudra t-il leur apprendre les commandes de base pour gérer Git (add, commit, push, branch, merge...) ?

### la maîtrise des outils de gestion de notes et de références : un objectif important du cours. 

Zotero est un gestionnaire de référence libres qui permet de disposer à la fois sur un site distant et en local des références bibliographiques. Celles-ci peuvent être partagées au groupe-classe par l'enseignant. Une action préalable consistera pour les étudiants qui ne l'utilisent pas encore à télécharger cet outil et à importer les références bibliographiques promues par les enseignants du cours dans leur environnement de travail en local.
La sixième version de Zotero (parue en février 2022) permet d'annoter chaque texte conservé et d'envoyer les notes prises dans un format interopérable (markdown) vers un autre éditeur. 
Les étudiants peuvent se former seuls à Zotero en utilisant le guide mis à disposition par la bibliothèque (focus.univ-rennes1.fr/zotero)
Les bibliothécaires sont à leur disposition pour résoudre les problèmes éventuels survenus au moment de l'installation du logiciel sur les ordinateurs des étudiants.
La même méthode peut être suivie pour Zettlr et pour Cosma (auto-formation au moyen d'un tutoriel, réponses à distance des enseignants)


## Déterminer un livrable pour ce travail collaboratif

Le travail collaboratif doit prendre la forme d'un site permettant d'articuler de façon hypertextuelle, un ensemble de fiches et de documents. 
Cet hypertexte peut prendre la forme d'un wiki ([[@bourbeillonAgirEnsembleDans2022]], [[@pudelkoConcevoirEncadrerWiki2019]]) ou bien d'un graphe de notes

Le problème du wiki est qu'une fois la table des matières fixée, les étudiants ne s'occupent que de leur partie et ne s'intéressent pas du tout à ce que font leurs condisciples. 
Dans le graphe de notes, les notes sont disposées de manière horizontale, sans lien hiérarchique entre elles. Cette disposition permet de compléter l'heuristique d'une écriture dialectique (ce que dit le texte, ce que j'en pense) par une autre heuristique, celle qui consiste à relier entre eux par des liens hypertextes éventuellement qualifiés (ce que permet Cosma) différentes fiches et donc différentes lectures. 
A priori, n'importe quelle note ou fiche peut être reliée sémantiquement à n'importe quelle autre note ou fiche du répertoire. 
La recherche de mots-clé proches de sa thématique (pour savoir si celle-ci a été traitée dans une autre fiche) à l'intérieur de l'outil de rédaction (Zettlr) devrait permettre aux étudiants de prendre davantage en considération le travail que les autres sous-groupes font. 



# Références


