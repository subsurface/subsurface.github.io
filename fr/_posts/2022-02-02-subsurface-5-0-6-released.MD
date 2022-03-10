---
layout: post
title: "Aankondiging Subsurface 5.0.6"
lang: "nl"
categories: release
version: 5.0.6
previousVersion: 5.0.5
ref: subsurface-5.0.6
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie voegt enkele kleine wijzigingen toe in vergelijking met {{ page.previousVersion }}.

Wijzigingen in Subsurface {{ page.version }}:

# Nieuwe functionaliteit:

- Statistieken: sorteren van categorische staafdiagrammen

# Opgeloste problemen:

- Duiklijst: geen SAC berekening voor CCR-duiken

- Profiel: fix bewerking van tijd / duur (profiel van bewerkte duik werd niet getoond)

- Profiel: een deel van de implementatie herschreven wat resulteerde in prestatieverbeteringen

# Duikcomputer ondersteuning:

- Uwatec/Scubapro duikcomputers: gebruik de oorspronkelijke standaard zwaartekrachtfactor

- Garmin: fix verwerking gasverandering gebeurtenis

{% include desktop-release-bottom.MD %}
