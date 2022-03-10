---
layout: post
title: "Aankondiging Subsurface 5.0.4"
lang: "nl"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie lost een aantal problemen op in {{ page.previousVersion }}.

Wijzigingen in Subsurface {{ page.version }}:

# opgeloste problemen:

- desktop: mogelijke crash verholpen bij het selecteren van meerdere als ongeldig gemarkeerde duiken

- afbeelding importeren: betere ondersteuning voor grote tijdsverschillen

- planner: verhelp een bug bij het instellen van de MND voor gasmix met 21% zuurstof

- kern: herstel weergave onjuist duikprofiel in #3184

- kern: door een bug in 5.0.3 werden bepaalde duiklogboeken verkeerd opgeslagen en konden dan niet meer worden ingelezen

- kern: mogelijke crashes opgelost met zeer complexe XML-bestanden


{% include desktop-release-bottom.MD %}
