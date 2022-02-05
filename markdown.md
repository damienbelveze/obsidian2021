---
title: La markdown comme syntaxe universelle
subtitle: Atelier dans le cadre du stretching numérique
author: Damien Belvèze
date: 23/06/2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: [MD]
tags: [programmation]
---

# avantages du markdown
<!--
# Limites des traitements de texte

Un traitement de texte peut-il vous convenir si :

si vous voulez faire du code et du texte (usages scientifiques par exemple)

si vous souhaitez inclure des formules mathématiques ou chimiques dans votre texte

si vous souhaitez maîtriser toutes les étapes de la mise en page ? 

si vous souhaitez convertir rapidement votre texte d'un format à un autre ? 

NON
-->


syntaxe très simple à apprendre permettant d'éditer dans une grande variété de formats (wiki, odt, doc, pdf, html, [[LaTeX]], ce qu'on appelle la versatilité. 

Depuis 1984, ceux qui écrivent de la poésie et ceux qui écrivent du code, à quelques exceptions près, n'écrivent plus sur le même support numérique. (le traitement de texte Wordstar vendu avec la microinformatique de l'époque permettait auparavant d'écrire les deux avec le même logiciel)

essor du traitement de texte qui ne permet plus d'écrire du code (maintien parallèle des éditeurs de texte pour les langages informatiques)

>Nous avons donc perdu progressivement la capacité d’écrire dans un langage interprétable par la machine

(Julien De Hut[[@DehutfiniravecWord2018]])

Un traitement de texte est fait pour vous faciliter certaines mises en page en prenant en charge (et invisibilisant les opérations sous-jacentes), cela vous fait gagner du temps jusqu'à un certain point

le fait de recourir à ces traitements de texte opaques (parce que propriétaires et parce que ne permettant pas d'accéder à la liste des opérations) constitue un danger pour écrire la science (risque d'erreur et manque de transparence du logiciel)

LaTeX : découplage du texte et de sa mise en forme. Permet une finesse d'édition plus importante que les traitements de texte. 
convient aux chercheurs en informatique pour qui l'édition est une affaire de programmation. 

Aaron Swartz et John Gruber ont inventé le markdown plus simple à utiliser que la LaTeX (courbe d'apprentissage beaucoup moins grande)

>Le HTML comprend un grand nombre de balises. La mise en page du texte peut être également enrichie au moyen du CSS. La force du Markdown résulte dans l’utilisation de balises peu nombreuses, simples à mettre en place et à mémoriser. Il devient aisé de réaliser un document dont on maîtrise la mise en page sur le Web, sans pour autant devoir apprendre le HTML. Plus encore, en conjonction de Pandoc qui est un moteur de conversion, il devient possible de produire aussi bien du HTML, que des pdf, des docx, des epub, et même des présentations de type PowerPoint. On ne produit alors ses données qu’une seule fois et on les exporte mises en forme automatiquement pour plusieurs supports. [[@DehutfiniravecWord2018]]

Au lieu d'apprendre à utiliser des interfaces qui changent régulièrement avec les changements de version et n'engendrent qu'un savoir restreint à l'éditeur de texte, apprenons plutôt le langage homme-machine pour compiler du texte avec des instructions de mise en forme. 
L'une des raisons pour lesquelles écrire en markdown sur Obsidian peut être aussi une bonne introduction au code (de même que pour [[Twine]] fournit une introduction au langage Haskell)

voir également la frustration d'universitaires qui considèrent que les traitements de texte restent trop attachés à l'impression comme finalité[[@Vitali-RosatichercheursSHSsaventils2018]]


# petite démonstration

<!-- prérequis

Dans Répertoire "Atelier Markdown", prévoir un répertoire images
dans le répertoire images mettre les deux images drake1.png et drake2.png)
Sous Atelier Markdown, placer [alignement_figures.md](aligner des figures.md)

-->

ouverture de alignement_figures.md avec Atom pour montrer birèvement à quoi ressemble le markdown

conversions avec pandoc, d'abord en PDF

``````powershell

pandoc "D:\Home\dbelveze\Desktop\atelier markdown\document.md" -o document.pdf

``````









# Bibliographie


