---
layout: post
title: "Aankondiging Subsurface 4.9.7"
lang: "nl"
categories: release
version: 4.9.7
previousVersion: 4.9.6
ref: subsurface-4.9.7
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze release lost een aantal problemen op in {{page.previousVersion}} en voegt enkele kleine verbeteringen toe, evenals ondersteuning voor een flink aantal nieuwe duikcomputers. Enkele van de wijzigingen in Subsurface {{page.version}}:

# nieuwe functionaliteit:

  - profiel: een "Gaswissel bewerken" rechts-klik optie toegevoegd [#2910]

  - importeren: parser toegevoegd voor SeacSync db. Momenteel gebruikt alleen Seac Action het SeacSync-programma.

  - ondersteuning voor de Shearwater Peregrine (vereist firmware V81 of nieuwer)

  - ondersteuning voor de Aqualung: i470TC

  - ondersteuning voor de Liquivision Kaon, Lynx, Xen, Xeo

  - ondersteuning voor de McLean Extreme

  - ondersteuning voor de Oceans S1

  - automatische herkenning van meer BLE-duikcomputers

# opgeloste problemen:
  
  - bluetooth/rfcomm: niet werkende klassieke BT downloads verholpen op Linux and Windows; op macOS werkt het nog steeds niet

  - uitrusting: reeds ingestelde gewichten niet overschrijven bij het wijzigen van het gewichtstype [#2938]

  - uitrusting: zoeken op substring bij type uitrusting

  - profiel: verbetering van de resolutie bij afdrukken en exporteren

  - kern: probleem opgelost bij hernummering van geïmporteerde duiken [#2731]

  - kern: probleem opgelost bij samenvoegen van duiken met meerdere cilinders

  - kern: zorg ervoor dat altijd de huidige duik is geselecteerd [#2961]

  - kern: filterstatus bijwerken bij het laden van de duiklijst [#2961]

  - media: lees de tijd van mvhd-atom van QuickTime/MP4-stijl video's

  - planner: correct initialiseren het zoutgehalte

  - planner: nul-lengte segmenten correct behandelen bij het opnieuw plannen 

  - planner: rekening houden met de "O2 narcotisch" instelling bij het berekenen van MND

  - importeren: aantal problemen opgelost bij het importeren van Shearwater Cloud

  - Shearwater parser gerepareerd voor ondersteuning van PNF op Petrel duikcomputers

{% include desktop-release-bottom.MD %}
