---
layout: post
title: "Aankondiging Subsurface 4.9.5"
lang: "nl"
categories: release
version: 4.9.5
previousVersion: 4.9.4
ref: subsurface-4.9.5
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze release lost een aantal problemen op in {{page.previousVersion}} en voegt enkele kleine verbeteringen toe aan de CSV import/export. Enkele van de wijzigingen in Subsurface {{page.version}}:

# nieuwe functies :

  - CSV import/export: ondersteuning voor meerdere flessen

  - CSV import/export: ondersteuning voor duikmodus

# opgeloste problemen:

  - verwarrende waarschuwing verwijderd bij het openen van cloud opslag

  - verbeterde serviceselectie voor BLE-duikcomputers

  - verbeterde herkenning van BLE-duikcomputers

  - SAC en andere berekende waarden bijwerken wanneer de flesinformatie wijzigt

  - correcte weergave na wijzigen van de gebruikersvoorkeuren voor datum en tijd

  - diverse UI problemen opgelost in de planner

  - probleem opgelost in profielweergave van geplande duiken met oppervlaktesegmenten
  
  - toont duizendtal scheidingsteken in zoutgehalte waardes in lokaal formaat

# libdivecomputer:

  - oplossing voor Pelagic BLE eigenaardigheden (Oceanic Pro Plus X en Aqualung i770R)

  - verbeteringen in bijwerken van OSTC3 firmware

{% include desktop-release-bottom.MD %}
