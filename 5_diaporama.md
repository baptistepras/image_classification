---
jupytext:
  notebook_metadata_filter: rise
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.14.5
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
rise:
  auto_select: first
  autolaunch: false
  backimage: fond.png
  centered: false
  controls: false
  enable_chalkboard: true
  height: 100%
  margin: 0
  maxScale: 1
  minScale: 1
  scroll: true
  slideNumber: true
  start_slideshow_at: selected
  transition: none
  width: 90%
---

+++ {"slideshow": {"slide_type": "slide"}}

## Jeu de données

+++ {"slideshow": {"slide_type": "subslide"}}

**Sens Interdit/Sens Unique**

15 images de chaque, sur fonds variés:                           
    - Fond blanc                   
    - Arbres                       
    - Bâtiments                   
    - Ciel                         

<img src=media/jeu_donnees.png>

+++ {"slideshow": {"slide_type": "slide"}}

## Prétraitement

+++ {"slideshow": {"slide_type": "subslide"}}

**Extraction avec la fonction donnée**

<img src=media/extraction1.png>

+++ {"slideshow": {"slide_type": "subslide"}}

**Implémentation d'une nouvelle fonction spécialement pour ce jeu**

<img src="media/extraction_avant.png">
<img src="media/bleu_fonce.png">

+++ {"slideshow": {"slide_type": "subslide"}}

**Si on cherche un bleu plus foncé pour éliminer un maximum le ciel (1.65)**

<img src="media/extraction2.png">

+++ {"slideshow": {"slide_type": "subslide"}}

**Extraction finale du premier plan**

<img src="media/extraction3.png">

+++ {"slideshow": {"slide_type": "subslide"}}

**Implémentation d'une nouvelle fonction de recadrage**

<img src="media/recadrage.png">

+++ {"slideshow": {"slide_type": "subslide"}}

**Recadrage carré autour du centre**

<img src="media/recadrage2.png">

+++ {"slideshow": {"slide_type": "subslide"}}

**Recadrage autour des bornes du premier plan**

<img src="media/recadrage3.png">

+++ {"slideshow": {"slide_type": "slide"}}

## Visualisation des données

+++ {"slideshow": {"slide_type": "subslide"}}

**Distance euclidienne des données**

<img src=media/visualisation.png>
<img src=media/dist_euclide.png>

+++ {"slideshow": {"slide_type": "subslide"}}

**Analyse en composantes principales**

<img src=media/attributs_PCA.png>

+++ {"slideshow": {"slide_type": "subslide"}}

**Métadonnées**

<img src=media/metadonnees.png>

+++ {"slideshow": {"slide_type": "slide"}}

## Analyse et classificateurs

+++ {"slideshow": {"slide_type": "subslide"}}

**Analyse par attributs**

<img src=media/matrice.png>
<img src=media/meilleurs.png>
<img src=media/analyse_attributs.png>

+++ {"slideshow": {"slide_type": "subslide"}}

**Résultat des classificateurs**

<img src=media/classificateurs.png>
<img src=media/apprentissage.png>

+++ {"slideshow": {"slide_type": "subslide"}}

**Comité de classificateurs**

__Résultat:__                                                                                                           
<img src=media/comite.png>                                                                                             
__Incertitude aléatorique:__                                                                                                  
<img src=media/aleatorique.png>                                                                                             
__Incertitude épistémique:__                                                                                               
<img src=media/epistemique.png>

+++ {"slideshow": {"slide_type": "slide"}}

## Résultats

+++ {"slideshow": {"slide_type": "subslide"}}

**Observations**

<img src=media/jeu_donnees.png>

+++ {"slideshow": {"slide_type": "slide"}}

## Discussion

+++ {"slideshow": {"slide_type": "subslide"}}

__Objectif du projet__:

<img src=media/panneaux.jpeg>
