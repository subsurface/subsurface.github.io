---
layout: post
title: "Aankondiging Subsurface 5.0.7"
lang: "nl"
categories: release
version: 5.0.7
previousVersion: 5.0.6
ref: subsurface-5.0.7
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie voegt enkele kleine wijzigingen toe in vergelijking met {{ page.previousVersion }} en verhelpt een aantal bugs.

Wijzigingen in Subsurface {{ page.version }}:

# Nieuwe functionaliteit:

- profiel: bewerken van het profiel is opgenomen in het systeem voor ongedaan maken

- generiek: hernoemen van divemaster naar duikleider

- duiklijst: maak duikleider zichtbaar in de duiklijst [#3382]

- uitrusting: handmatig toewijzen van flessensoren aan specifieke flessen (dit helpt duikers met meerdere duikcomputers die elk de druk voor een andere fles volgen)

- build-systeem: initiële ondersteuning voor Qt6 (waaronder ontbrekende kaarten, gebruikershandleiding, printen)

- build-systeem: initiële ondersteuning voor Apple M1 (met Qt6, zie bovenstaande beperkingen)

# Opgeloste problemen:

- kern: vermijd crash bij beschadigde cloudopslag

- planner: laat ESC werken (plan annuleren) bij het verplaatsen van handles

- desktop: onthoud de cursorpositie bij het wisselen tussen vensters [#3369]

- build-systeem: vertrouw niet op het git:// protocol bij het downloaden van sources

# Duikcomputer ondersteuning:

- Uemis support: herstel de mogelijkheid om de Zurich los te koppelen/opnieuw aan te sluiten wanneer het bestandssysteem vol is

- libdivecomputer: ondersteuning toegevoegd voor de meest recente BLE hardware in OSTC duikcomputers

- libdivecomputer: ondersteuning toegevoegd voor de meest recente Shearwater firmware, inclusief T3/T4 op Teric

- libdivecomputer: diverse overige kleine aanpassingen


{% include desktop-release-bottom.MD %}
