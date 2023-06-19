# Configuration de klipper pour une d12 230 mono avec bltouch

Vous trouverez dans ce dépôt l'ensemble des informations nécessaire pour migrer vôtre d12 vers klipper.
Je suis autodidacte sur le sujet, je réalisé ce document tout seul avec les informations que j'ai pu trouver un peu partout.

## Resources pour la création de ce projet
Maxime de [I3DM.FR](https://i3dm.fr/2023/03/25/klipper-sur-wanhao-d12/)
La chaine youtube de [Tom's Basement](https://www.youtube.com/@TomsBasement) et sa [playlist sur klipper](https://www.youtube.com/playlist?list=PLG2DUsM4SElSYaGta07jPFdrE_DXlMMff)

## Matériel nécessaire

- [BTT CB1](https://biqu.equipment/collections/control-board/products/pi4b-adapter-v1-0?variant=39847230242914) ou [ou BTT pi v1.2](https://biqu.equipment/products/bigtreetech-btt-pi-v1-2?variant=40326121980002)
- Micro sd
- Cable d'origine de l'imprimante USB-B vers USB-A

optionel mais bien pratique
- [USB Input Shaper](https://fr.aliexpress.com/item/1005005411366555.html?spm=a2g0o.order_list.order_list_main.11.c0355e5bKZAxdP&gatewayAdapt=glo2fra) 
- un [lot de vis M3](https://www.amazon.fr/gp/product/B0BCYW4YTX/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) pour le USB Input Shaper
- avoir imprimé les fichier 3mf dans le dossier [stl_adxl](https://github.com/sheldonGordon/klipper-config/tree/main/stl_adxl), pas nécessaire mais c'est mieux
 
## Installation de klipper sur le BTT CB1 ou BTT pi v1.2
Pour commencer il faut télécharger la dernière image officiel du [CB1](https://github.com/bigtreetech/CB1/releases), et télcharger celle qui commence par "CB1_Debian11_Klipper_kernel..."

Ensuite télécharger [balena etcher](https://etcher.balena.io/) ou [raspberry imager](https://www.raspberrypi.com/software/)

Il est maintenant temps d'écrire l'image du CB1 sur vôtre micro sd.
Connecter vôtre micro sd au pc, puis lancer balena etcher ou raspberry imager, pour mon cas le deuxième fois à très bien fonctionné.
![raspberry imager](./images/raspberryImager.png)

## Installation de klipper sur un vieux pc

## Copie des fichiers de configurations

## Modification du fichier de configuration printer.cfg

## Réglage des tensiosn de courroies et de galets

## Nivellement du bed

## Réglage de l'extruder

## Réaliser les PID

## Installation et Configuration du USB Input Shaper

## Réglage du Pressure Advance
