---
title: Prenez des notes de manière plus efficace avec Obsidian en vous initiant au langage markdown
subtitle: Consignes à suivre
author: Damien Belvèze
date: 21/09/2021
---

# tour de table

Qui êtes vous ? qu'est-ce que vous pensez qu'Obsidian peut vous apporter ?

# objectifs

Obsidian permet de gérer des notes, des notes de lecture.

- l'un des objectifs de cette session est d'apprendre à s'en servir pour prendre des notes
- l'autre objectif est de s'initier au *[[Format Texte|plain text]]* et à la syntaxe markdown.
- enfin on terminera en parlant de pandoc et de l'écriture scientifique (comportant des références bibliographiques notamment)
- [[Zotero]] et LaTeX sont libres et gratuits. Obsidian n'est pas libre mais il fonctionne bien avec les deux premiers. L'un des objectifs de la session est de vous faire prendre conscience de travailler avec des formats ouverts et interopérables.

# présentation

Présentation de la méthode Zettelkasten et des outils de notes à rétroliens

# Accès aux supports d'activité

Normalement, vous devriez trouver les supports sur le bureau de l'ordinateur que l'URFIST met à votre disposition.
Si vous utilisez votre propre ordinateur, voici comment procéder pour récupérer ces supports :

## si vous avez git sur votre machine

à l'endroit où vous souhaitez charger les fichiers (par exemple sur le bureau), ouvrez la console bash de git (Clic droit) et copiez la commande suivante :

~~
git clone https://github.com/damienbelveze/URFIST_obsidian.git
~~

## si vous n'utilisez pas git

Aller sur le répertoire du cours sur github (https://github.com/damienbelveze/URFIST_obsidian)
cliquer sur le bouton vert "code", sélectionnez *Download zip*
télécharger l'archive et extrayez-la.

## Liste des fichiers et des dossiers dans le support

- bracket eraser (dossier contenant un exécutable, le script de cet exécutable et une instruction (fichier REad.me))
- images (dossier contenant quelques images)
- references (dossier vide)
- batonnage_depeches (fichier odt)
- consignes (ce fichier, en markdown)
- google_news (fichier odt)
- krishna_bharat (fichier odt)
- methode_zettelkasten (fichier markdown)
- tableau (fichier ods)
- mode d'emploi d'Obsidian (fichier markdown)

# création du coffre

aller dans Obsidian
Créer et nommer un coffre avec le nom URFIST_Obsidian
comme chemin pour créer le coffre, indiquer le bureau

Aller dans [ce répertoire](https://github.com/damienbelveze/URFIST_obsidian) sous github

cliquer sur code et choisir l'option télécharger en format Zip
charger ce dossier zip sur le bureau. Il a pour nom URFIST_Obsidian_main.zip
dézipper l'archive.
Vous avez désormais sur le bureau deux dossiers :  
- URFIST_Obsidian  
- URFIST_Obsidian_main  

copier les fichiers et dossiers qui sont sous URFIST_Obsidian_main et les coller sous URFIST_obsidian

Lorsque vous ouvrez dans Obsidian le coffre URFIST_Obsidian, vous devriez voir apparaître désormais plusieurs fichiers et un dossier dont le nom est images.

Dans Obsidian, Aller dans les paramètres > plugins principaux > mettre sur *on* les plugins suivants :

- Modèles
- Diapositives

Aller dans les *plugins tiers*, activer le mode sans échec (ça permettra à l'avenir d'installer des plugins communautaires)

Aller dans raccourcis clavier, chercher *Diapositives*, cliquer sur l'astérique, réaliser une combinaison de touches (raccourci-clavier) à cet endroit. Ce raccourci-clavier basculera en mode diapositive. Essayer avec le fichier *Méthode Zettelkasten*

# Initiation au markdown

Dans le coffre, vous avez des documents invisibles dans Obsidian parce qu'ils ne sont pas en format markdown (.md), mais en format lisible par un traitement de texte (.odt).
Vous allez créer des notes dans Obsidian dont le nom sera identique au nom de ces fichiers.
Vous allez copier le contenu du fichier .odt et le coller dans la nouvelle note qui lui correspond.
Est-ce que le copier-coller permet de retrouver la forme et la structure du document ? Si non, comment peut-on procéder ?

Pour retrouver dans Obsidian la forme du document en format open document, vous pouvez vous référer au *Mode d'emploi d'obsidian* dans votre coffre. Ce n'est pas un mode d'emploi ni officiel, ni même complet. C'est la synthèse de toutes les informations que j'ai eu à mobiliser pour me permettre de travailler avec Obsidian comme je le souhaitais.
Une version à jour de ce document se trouve sur [Github](https://github.com/damienbelveze/Obsidian3/blob/main/Mode%20d'emploi%20d'Obsidian.md)

- Mettez en forme dans Obsidian la note Google News, pour qu'elle ait la structure du document .odt

- Intégrer le tableau (tableau.ods) à la note Google News en utilisant le service [Exceltomarkdown](https://tabletomarkdown.com/convert-spreadsheet-to-markdown/)  

- Créer des liens ([[wikiliens]]) à l'intérieur des trois notes. Chaque wikilien crée un lien et un rétrolien.  

- Dans le document krishna_bharat.odt, sauvegarder l'image de KB (avec le nom de fichier krishna_bharat.jpg) et envoyez-la dans le coffre d'Obsidian, dans le dossier *image*  

- Dans la note consacrée à Krishna Bharat, changer le chemin vers la photo de Krishna Bharat : remplacer le chemin existant par le nouveau chemin (relatif) : images/Krishna_Bharat.jpg. Ajouter entre les crochets un texte alternatif (Krishna Bharat)  

# Lien avec Zotero

## installer le plugin Betterbibtex dans Zotero

On va à présent faire une copie synchronisée de votre bibliothèque Zotero dans Obsidian.
Pour cela on a besoin de trois choses :  
- une bibliothèque Zotero avec des références dedans (fichier .bib)
- charger dans __Zotero__ le plugin **betterbibtex**  
- charger dans __Obsidian__ le plugin **Citations** (plugin communautaire)  

Ouvrez Zotero.
Vous pouvez soit vous connecter avec votre compte Zotero et télécharger toutes vos références sur cette instance ou bien ne pas vous connecter et commencer l'exercice avec une bibliothèque vide.

Dans les deux cas, aller chercher la référence mentionnée dans la note sur Google News (Nikos Smyrnaios, Franck Rebillard, L’actualité selon Google L’emprise du principal moteur de recherche sur l’information en ligne - CAIRN).
Intégrer cette référence dans Zotero

Onn va à présent charger le plugin betterbibtex dans Zotero :
1. aller sur la page suivante : https://github.com/retorquere/zotero-better-bibtex/releases/tag/v5.5.1  
2. clic-droit sur le fichier .xpi (sauvegarder en tant que / save file as > envoyer le fichier sur le bureau)  
3. retour dans Zotero > Outils > Extensions > ajouter > install add-on from file | sélectionner le fichier .xpi ce qui va installer l'extension betterbibtex dans zotero  
4. Dans Zotero, Aller ensuite sur *Ma bibliothèque*, ciquer droit, choisir *exporter ma bibliothèque*, sélectionner le format *Better Bibtex* et cocher l'option *garder à jour* (ainsi chaque fois que vous ajouterez une référence dans Zotero elle sera également disponible dans Obsidian)  
5. Charger le fichier .bib (on va le nommer pour la commodité de l'exercice **URFIST_obsidian.bib**) résultant de cette opération à la racine du coffre.  

## régler le plugin Citation dans Obsidian

### chargement de Citation dans Obsidian

Aller dans Obsidian

Dans les plugins tiers, chercher le plugin *Citations* de Jon Gauthier. L'installer et l'activer (ne pas oublier d'activer les plugins tiers sinon ils ne fonctionneront pas).

### en cas de blocage par le parefeu

Si vous êtes bloqué.e par le parefeu de votre ordinateur, et que vous ne pouvez pas ou ne voulez pas modifier les règles du pare-feu. Tous les plugins communautaires d'Obsidian peuvent s'installer manuellement. Voici comment faire avec le plugin Citations

Dans votre coffre obsidian, sous le dossier *.obsidian*, créer un dossier *plugins*. C'est à cet endroit que les fichiers relatifs aux plugins doivent se trouver
Sous *plugins*, créer un dossier *Citations* (cf. la liste des noms des plugins communautaires déjà enregistrés [sur Github](https://github.com/obsidianmd/obsidian-releases/blob/master/community-plugins.json))
Aller ensuite sur la [page de livraison du plugin](https://github.com/hans/obsidian-citation-plugin/releases/tag/0.4.4)
tout en bas de la page, on a trois dossiers :

- main.js    
- manifest.json  
- styles.css  

Ces trois dossiers doivent être copiés chacun sous le dossier *Citations* (clic droit sur chacun > enregistrer la cible du lien sous > aller dans le répertoire *Citations* > coller)

L'architecture que l'on doit trouver est donc la suivante :

~~
URFIST_Obsidian
| fichiers listés ci-dessus  
|
└───.obsidian
|   └─── plugins
|   |    └─── Citations
|   |        | main.js
|   |        | manifest.json
|   |        | styles.css
~~

- Fermer et rouvrir Obsidian, ouvrir un coffre, sélectionner URFIST-obsidian  
- désactivez le mode sans échec pour permettre le chargement du plugin
- Activer le plugin *Citations* et suivre les indications pour le paramétrer (voir ci-dessous)  


### paramétrage du plugin Citations

Aller ensuite dans les options des plugins, ouvrir les options du plugin *Citation*s :

- Opter pour le format Biblatex  
- Dans le paramètre Citation Database Path, indiquer le chemin absolu vers le fichier .bib mentionné plus haut (un chemin absolu commence par désigner un disque (C:, D: E:, etc.)  
- Dans les préférences du plugin Citations, au paramètre *Literature Note Folder* remplacer le texte existant par references (nom d'un dossier qui a été téléchargé depuis le Github)  
- dans les raccourcis-clavier, paramétrer un raccourci pour insérer une citation dans un texte (insert literature note)

Utiliser ce raccourci-clavier, nouvellement créé pour insérer au bon endroit de la note sur Google News la référence à Smyrnaios et Rebillard

# conversion avec pandoc

## convertir avec pandoc en lignes de commande

Pandoc est normalement installé sur votre ordinateur.
C'est un programme qui n'a pas d'interface graphique, on l'utilise donc en lignes de commande à partir d'un interpréteur de lignes de commande.
Ouvrir l'interpréteur dans un dossier :
- GNU/Linux : Ctrl+Alt+T  
- Windows : shift+clicdroit > *ouvrir la fenêtre powershell ici*    
- Mac : command + espace > sélectionner *Terminal* puis naviguer avec la commande *cd* jusqu'au bon répertoire.  

conversion de la note sur Google News en PDF

On part du principe que LaTeX est installé et fonctionne sur la machine (sinon au lieu d'utiliser pandoc on peut convertir la note en PDF directement depuis Obsidian)

ouvrir un terminal dans le même répertoire que cette note :

~~~
pandoc google_news.md -o google_news.PDF
~~~

la conversion se fait, mais :

- on n'a pas de page de titre
- on n'a pas la référence correctement insérée dans le texte et à la fin

Pour réaliser la page de titre, on peut utiliser un entête en YAML :

commencer la note par :

\-\-\-
title: Google News  
subtitle: exercice pour maîtriser Obsidian  
date: 30/09/2021  
author : indiquericivotrenom  
\-\-\-

Renvoyer la même commande dans le terminal (flêche vers le haut + entrée)  
Observer les différences.

Créer un dossier à la racine du coffre nommé csl
dans ce dossier, télécharger la feuille de style suivante ieee (la télécharger [depuis le site Zotero](https://www.zotero.org/styles/ieee?source=1) en format .csl, envoyer ce fichier csl dans le dossier csl.

~~~
pandoc "google news.md" --from html --to pdf --bibliography=URFIST_obsidian.bib
--csl=csl\ieee.csl --pdf-engine=xelatex --citeproc -f markdown+smart -o google_news.pdf
~~~

La conversion devrait cette fois prendre en compte la citation et la référence bibliographique.

## convertir avec pandoc en utilisant bracket-eraser

bracket-eraser est un petit script qui vous permet deux choses :
- vous débarrasser des liens sous la forme [[liens]] (=wikiliens) qui restent dans le document en pdf après conversion avec Pandoc dans les exemples précédents
- utiliser pandoc de façon guidée avec une interface graphique très basique (menus). Pour ajouter de nouvelles fonctionnalités, il faudra modifier le script.
Si l'exécutable (bracket-eraser.exe) ne fonctionne pas à cause d'un parefeu, testez le script dans une fenêtre powershell (voir [ici](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.security/get-executionpolicy?view=powershell-7.2))

````powershell
./script.ps1
````

Si la console ne vous permet pas d'exécuter un script, changer les permissions de powershell:
Dans Powershell (ouvrir Powershelle en mode administrateur):

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
```

Entrer O pour O\[Oui\]

Si vous n'avez pas les droits d'administrateur sur la machine, ouvrez powershell et remplacez -Scope LocalMachine par -Scope CurrentUser

N'hésitez pas à me solliciter à tous les moments du cours afin que je vous vienne en aide.



