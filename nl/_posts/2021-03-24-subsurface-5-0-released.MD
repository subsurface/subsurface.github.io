---
layout: post
title: "Aankondiging Subsurface 5.0"
lang: "nl"
categories: release
version: 5.0
previousVersion: 4.9.10
ref: subsurface-5.0.0
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie brengt een complete herschrijving van statistische code met veel nieuwe functies en krachtige visuele statistieken voor de duiken. Het maakt analyse mogelijk van verschillende variabelen tegen elkaar en biedt standaard staafdiagrammen, histogrammen, cirkeldiagrammen en ook spreidingsdiagrammen met regressielijnberekening.

Deze versie lost ook een aantal problmemen op van {{ page.previousVersion }}. Wijzigingen in Subsurface {{ page.version }}:

# nieuwe functionaliteit:

- volledige herschrijving van de statistieken code, waardoor de mogelijkheden aanzienlijk worden uitgebreid

- voorkeursoptie toegevoegd om standaard flestypes uit te schakelen

- planner: mogelijk maken van automatische setpoint wisselingen op specifieke diepten in CCR modus

- ondersteuning voor de Mares Horizon

- ondersteuning voor de Sherwood Sage

- ondersteuning voor de Ratio 2021 modellen

# opgeloste problemen:

- maak het selecteren van meerdere duiken redelijk snel

- houd rekening met PSCR pO2-daling bij het berekenen van CNS en OTU

- herstel OTU- en CNS-berekeningen voor CCR-duiken op ondiepe diepten

- ongedaan maken: opslaan in git na het bewerken van gewichten

- ongedaan maken: duikmodus resetten bij ongedaan maken van setpoint-toevoeging

{% include desktop-release-bottom.MD %}
