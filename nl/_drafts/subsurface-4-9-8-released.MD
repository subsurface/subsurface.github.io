---
layout: post
title: "Aankondiging Subsurface 4.9.8"
lang: "nl"
categories: release
version: 4.9.8
previousVersion: 4.9.7
ref: subsurface-4.9.8
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze release lost een aantal problemen op in {{ page.previousVersion }} en voegt enkele verbeteringen toe. Het hoogtepunt is de nieuwe, aanzienlijk flexibelere filtermogelijkheden voor de duiklijst. Enkele van de wijzigingen in Subsurface {{ page.version }}:

# nieuwe functionaliteit:

 - filter: flexibeler filtersysteem op basis van afzonderlijke criteria

 - ondersteuning voor de Garmin Descent Mk2/Mk2i voor Linux, macOS en 64bit Windows

 - ondersteuning voor de Scubapro Aladin A2

 - desktop: toevoegen van duiken aan willekeurige trips

 - uitrusting: gebruik pO2 van voorkeuren voor MOD-weergave

 - kern: ongedaan maken van apparaatbeheer

 - Windows: afzonderlijke 32-bits en 64-bits builds - de 32-bits build ondersteunt de Garmin Descent Mk2 / Mk2i NIET

# opgeloste problemen:

 - desktop: verbeteringen in het uiterlijk in de donkere modus

 - desktop: crash verholpen bij drag&drop in tag-widgets [#3030]

 - desktop: hou rekening met page-up, page-down, home en end toetsen voor selectiewijziging [#2957]

 - kern: verbeteringen in het samenvoegen van flesdrukken [#2884]

 - Windows: ontbrekend modern Vista-thema toegevoegd

 - macOS: probleem opgelost met HID-duikcomputers zoals Suunto Eon Core/Steel [#2999]

{% include desktop-release-bottom.MD %}
