---
title: Raspberry Pi
subtitle:
author: Damien Belvèze
date: 15-01-2022
link_citations: true
bibliography: mylibrary.bib
biblio_style: csl\ieee.csl
aliases: []
tags: []
---

# configuration
fichier config 

``````
gpu_mem=16
start_file=recovery.elf
fixup_file=fixup_rc.dat

hdmi_drive=2

[pi4]
start_file=recover4.elf
fixup_file=fixup4rc.dat
``````

# accès SSH

``````
ssh pi@IP

``````
(port 22)
IP : 192.168.1.34


# chargement de logiciels

## snap

``````
sudo apt-update
sudo apt install snapd
``````

nécessité de rebooter le Rpi

`````
sudo reboot
``````
 installer Snap

 ``````
 sudo snap install core
 ``````
 Pour installer un logiciel présent dans Snap (Inkscape par exemple)

 ``````
 sudo snap install inkscape
 ``````
 [source](https://snapcraft.io/install/inkscape/raspbian)




# bibliographie

