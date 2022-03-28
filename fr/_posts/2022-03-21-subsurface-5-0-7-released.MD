---
layout: post
title:  "Annonce Subsurface 5.0.7"
lang:   "fr"
categories: release
version: 5.0.7
previousVersion: 5.0.6
ref: subsurface-5.0.7
---

L'équipe de développement de Subsurface est fière de vous annoncer la version {{ page.version }} de Subsurface, un carnet de plongée et planificateur open source pour Windows, Mac and Linux.

Cette version ajoute quelques petites modifications par rapport à {{ page.previousVersion }} et règle plusieurs erreurs.

Modifications dans Subsurface {{ page.version }}:

# nouvelles fonctionnalités:

- profil: inclut l'édition du profil dans le système d'annulation

- général: renommage de dive master en dive guide (guide de palanquée)

- liste des plongées: rend visible le dive guide (guide de palanquée) dans la liste des plongée [#3382]

- équipement: permet l'assignation manuelle des sondes à des bouteilles spécifiques (cela aide les plongeurs qui ont plusieurs ordinateurs de plongée qui suivent chacun la pression d'une bouteille différente)

- système de compilation: support initial de Qt6 (il manque les cartes, le manuel, l'impression entre autres)

- système de compilation: support initial des Apple M1 (en utilisant Qt6, voir limitations ci-dessous)

# résolution de bogues:

- coeur: évite un crash avec un stockage cloud corrompu 

- planificateur: permet d'utiliser ESC-Echap (annuler la planification) tout en bougeant les poignées

- bureau: ne perd pas la position du curseur dans les notes lors d'un changement entre fenêtres [#3369]

- système de compilation: ne dépend plus du protocole git:// lors du téléchargement des sources

# support des ordinateurs de plongée:

- Uemis: règle la possibilité de déconnecter/reconnecter le Zurich lorsque son système de fichier est saturé

- libdivecomputer: ajoute le support pour les derniers ordinateurs OSTC utilisant BLE 

- libdivecomputer: ajoute le support des derniers firmware Shearwater, y compris les T3/T4 sur le Teric

- libdivecomputer: divers autres petites modifications


{% include desktop-release-bottom.MD %}
