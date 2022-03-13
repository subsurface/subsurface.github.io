---
layout: post
title:  "Annonce Subsurface 5.0.6"
lang:   "fr"
categories: release
version: 5.0.6
previousVersion: 5.0.5
ref: subsurface-5.0.6
---

L'équipe de développement de Subsurface est fière de vous annoncer la version {{ page.version }} de Subsurface, un carnet de plongée et planificateur open source pour Windows, Mac and Linux.

Cette version ajoute quelques petits modifications par rapport à la version {{ page.previousVersion }}.

Modifications dans Subsurface {{ page.version }}:

# nouvelles fonctionnalités:

- statistiques: implémentation de l'ordre de bar-graphs par catégorie 

# bogues résolus:

- liste des plongées: ne tente plus de calculer la consommation sur les plongée en recycleur à circuit fermé

- profil: corrigé l'édition de l'heure/durée (le profil de la plongée éditée n'était plus affichée)

- profil: réécriture d'une partie de l'implémentation qui conduit à l'amélioration de performances

# support d'ordinateurs de plongée:

- ordinateurs de plongée Uwatec/Scubapro: rétablit de facteur de gravité stangard original

- Garmin: corrige la prise en compte d'événement de changement de gaz

{% include desktop-release-bottom.MD %}
