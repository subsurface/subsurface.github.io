---
layout: post
title:  Aankondiging Subsurface 4.9.3
lang:   nl
date:   2019-09-10 08:00:00 -0700
categories: release
version: 4.9.3
previousVersion: 4.9.1
ref: subsurface-4.9.3
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie verhelpt een aantal problemen uit {{ page.previousVersion }} (versie 4.9.2 is wel uitgebracht, maar nooit aangekondigd).

Enkele van de aanpassingen in Subsurface {{ page.version }}:

# bugfixes:

- Sluit duikstek venster als de duikstek door het ongedaan maken is verwijderd
- De opmaak van planner notities niet vernietigen tijdens het bewerken van de duiknotities \[\#2265\]
- Voorkom het volledig opnieuw laden van de kaart als er op een vlag wordt geklikt
- Markeer alle geselecteerde duikstekken wanneer er op een vlag wordt geklikt
- Crash verholpen bij het klikken op een vlag in Qt 5.9
- Crash verholpen bij het opslaan van ondertitels of profielafbeelding
- Crash verholpen bij kopiëren &amp; plakken
- Opslaan naar XML met lege duikstek taxonomie verholpen
- Tonen van tripduur gecorrigeerd
- Planner: berekening van CNS voor pO2 > 1.6 bar gecorrigeerd

# libdivecomputer:

- Ondersteuning voor Deepblu Cosmiq+
- Ondersteuning voor Aqualung i200C
- diverse fouten verholpen

{% include desktop-release-bottom.MD %}
