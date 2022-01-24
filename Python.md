---
title: Python
subtitle: programmer en Python
author: Damien Belvèze
date: 08-02-2021
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: [Py]
tags: [Programmation]
---

# ouvrir, écrire, modifier, fermer un fichier
Ouvre un fichier et le lit tout d'un coup
"r" = read ([[@SchultzPythonpourSHS2021]], p81)
> ouvre un fichier avec la fonction *open* en donnant le chemin du fichier et le mode lecture "r" puis stocke le lien vers le fichier ouvert dans la variable **fichier** 


``````
fichier=open("data1.txt", "r")
contenu=fichier.read()
``````

``````
fichier.close()
print(contenu[0:40])
``````

ferme le fichier, imprime les premières lignes (de la première ligne à la ligne 40)

# modifier des caractères dans un fichier

``````
# ouvre et lit le fichier titre.md
with open('titre.md', 'r') as file :
  filedata = file.read()

# remplace dans ce fichier le e par un a
filedata = filedata.replace('e', 'a')

# écrit un fichier avec le texte modifié dont le nom est file.txt
with open('file.txt', 'w') as file:
  file.write(filedata)
``````

# bibliographie



langage de programmation

voir tutoriel de base sur [Focus](https://focus.univ-rennes1.fr/python1)

