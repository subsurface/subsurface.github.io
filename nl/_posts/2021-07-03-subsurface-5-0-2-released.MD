---
layout: post
title: "Aankondiging Subsurface 5.0.2"
lang: "nl"
categories: release
version: 5.0.2
previousVersion: 5.0.1
ref: subsurface-5.0.2
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie voegt enkele kleine verbeteringen toe, waaronder geografisch gedistributeerde cloud backend servers.
Het lost ook een aantal problemen op in {{ page.previousVersion }}. Wijzigingen in Subsurface {{ page.version }}:

# Nieuwe functionaliteit:

- Cloud: ondersteuning voor meerdere cloud backend servers

- Cloud: probeer een server te kiezen die dicht bij de gebruiker staat

- Exporteren: voortgangsdialoog weergeven bij exporteren naar TeX

- Duik wijzigent: mogelijkheid toegevoegd om duiknummer en datum te kopiëren en te plakken

- Ondersteuning voor de Suunto Eon Steel Black

- Ondersteuning voor de Sherwood Beacon

- Ondersteuning voor de nieuwe versie van de Zoop Novo

- Ondersteuning voor de nieuwe versies van de Shearwater Perdix AI

- Ondersteuning voor de Sporasub SP2

# Opgeloste problemen:

- Desktop: herstel verwijderen/wijzigen van bladwijzers op het duikprofiel

- Printen: gebruik betere fontgrootte, ook voor een ongewone venstergrootte

- Planner: niet meteen automatisch opstijgen

- Planner: diverse kleine bugfixes

- Importeren: herstel verwerken van vertaalde APD kopteksten

- Core: crash voorkomen bij verwerken het van zeer complexe XML-bestanden

{% include desktop-release-bottom.MD %}
