---
title: pypandoc
subtitle:
author: Damien Belvèze
date: 19-01-2022
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: [Pandoc with Python, Pandoc avec Python]
tags: [Python]
---

# installation

pré-requis : avoir installé Python
Sur windows : 

``````
py -m pip install pypandoc
``````

# conversion simple

``````
import pypandoc
pypandoc.convert_file('D:/Home/dbelveze/Desktop/titre.odt', format='odt', to='md', outputfile='D:/Home/dbelveze/Desktop/titre.md')
``````








# bibliographie

