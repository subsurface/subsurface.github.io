---
layout: post
title: "Annonce Subsurface 5.0.4"
lang: "fr"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

L'équipe de développement de Subsurface est fière de vous annoncer la version {{ page.version }} de Subsurface, un carnet de plongée et planificateur open source pour Windows, Mac and Linux.

Cette version corrige un certain nombre de problèmes de la version {{ page.previousVersion }}.

Modifications dans Subsurface {{ page.version }}:

# problèmes résolus:

- bureau: résolution d'un plantage possible lors de la sélection de plusieurs plongées marquées comme invalides

- importation d'images: meilleur support pour les grandes différences de marqueur horaire

- planificateur: résolution d'un bogue réglant la MND d'un mélange gazeux avec 21% d'oxygène

- noyau: herstel weergave onjuist duikprofiel in #3184

- noyau: suite à un bogue dans 5.0.3, certains carnets de plongée étaient erronément stockés et ne pouvaient en conséquence être relus

- noyau: plantages possibles résolus avec de fichiers XML très complexes


{% include desktop-release-bottom.MD %}
