---
layout: post
title: "Aankondiging Subsurface 4.9.4"
lang: "nl"
categories: release
version: 4.9.4
previousVersion: 4.9.3
ref: subsurface-4.9.4
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze release lost een aantal problemen op in {{page.previousVersion}} en voegt enkele belangrijke nieuwe functies toe. Enkele van de wijzigingen in Subsurface {{page.version}}:

# nieuwe functies:

  - kaarten: toon de duikstek als markering bij het openen van Google Maps

  - ongedaan maken: mogelijkheid om gebeurtenissen ongedaan te maken (bladwijzers, setpoints, gaswissels)

  - ongedaan maken: mogelijk voor herplannen van duik

  - duiklijst: mogelijkheid om duiken ongeldig te verklaren

  - filter: mogelijkheid voor zoeken in volledige tekst

  - filter: "begint met" en "exact" filters toegevoegd voor zoeken op tekst

  - duikinformatie : mogelijkheid om het zoutgehalte te wijzigen

  - duikinformatie: huidige GF toegevoegd aan het informatievak

  - duikinformatie: geen restrictie meer op het aantal flessen

  - UI: snelheid verbeterd bij selectie van meerdere trips

  - planner: selectievak toegevoegd om zuurstof als narcotisch te beschouwen

  - planner: verbetering van afronding stoptijden in planner notities

# opgeloste problemen:

  - creëren van nieuwe flestypes gecorrigeerd (naam kon niet gelijk zijn aan het begin van een reeds bestaande naam)

  - tabvolgorde gecorrigeerd in het filter venster 

  - negeer duikstekken zonder locatie bij een dichtstbijzijnde zoekopdracht

  - probleem opgelost in Linux AppImage met niet kunnen communiceren met Bluetooth duikcomputers \[\#2370\]

  - kopiëren en plakken van meerdere flessen is mogelijk \[\#2386\]

  - geen willekeurige SAC waarden genereren voor flessen zonder gegevens \[\#2376\]

  - wijzigingen vastleggen bij klikken op "Klaar" in het duikstek wijzigen scherm

  - statistieken tabblad bijwerken bij ongedaan maken of opnieuw uitvoeren

  - duikdetails bijwerken bij herplannen van een duik \[\#2280\]

  - bij exporteren van duikstekken in duikstekken mode, exporteer de geselecteerde duikstekken \[\#2275\]

# libdivecomputer:

  - ondersteuning voor de Oceanic Geo 4.0, ProPlus 4

  - ondersteuning voor de Scubapro Aladin A1

  - ondersteuning voor de Sherwood Wisdom 4

  - opschonen Shearwater flesdruk verwerking 

  - kleine verbeteringen

{% include desktop-release-bottom.MD %}
