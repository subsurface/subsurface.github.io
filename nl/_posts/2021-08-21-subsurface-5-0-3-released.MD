---
layout: post
title: "Aankondiging Subsurface 5.0.3"
lang: "nl"
categories: release
version: 5.0.3
previousVersion: 5.0.2
ref: subsurface-5.0.3
---

Het Subsurface ontwikkelteam presenteert met trots versie {{ page.version }} van Subsurface, een open source duiklog en duikplan programma beschikbaar voor Windows, Mac en Linux.

Deze versie voegt een aantal kleine verbeteringen toe en lost een aantal problmeen op in {{ page.previousVersion }}. Een bijwerking is dat oude functionaliteit (bijnamen van duikcomputers) waarvan we denken dat deze niet veel wordt gebruikt, is gewijzigd. De reden waarom we denken dat dit niet veel werd gebruikt, is dat een aantal wijzigingen in recente releases deze functionaliteit defect heeft gemaakt, maar niemand leek het probleem op te merken. Subsurface raakte soms in de war bij het identificeren van duikcomputers en bepaalde de verkeerde bijnaam. Nog erger, soms zou het ook reeds gedownloade duiken van bepaalde duikcomputers nogmaals downloaden. De oplossing voor dat probleem is enigszins drastisch omdat het alleen bijnamen toestaat voor duikcomputers die een tekstueel "Extra Informatie" serienummer hebben. In deze release is die informatie toegevoegd voor een zeer grote aantal van de van huidige duikcomputers, maar er zijn er nogal wat die geen bijnaam meer kunnen krijgen. Als dit bij jou het geval is, neem dan contact op met ons en laat weten welke duikcomputer je gebruikt en hoe je bijnamen gebruikt.

Wijzigingen in Subsurface {{ page.version }}:

# Nieuwe functionaliteit:

- Vervang duikcomputer beheer door een nieuwe implementatie. Dit lost een aantal bijzondere gevallen op waarin Subsurface reeds gedownloade duiken onnodig downloadt, maar betekent ook dat sommige oudere duikcomputers geen bijnamen meer kunnen hebben

- GPS-fix welke is gedownload van een duikcomputer toevoegen aan bestaande duiklocatie

- Bewerken van het profiel mogelijk gemaakt voor duiken die zonder metingen zijn geïmporteerd (via CSV)

- Detectie toegevoegd voor Aladin A2 als BLE-duikcomputer

- Ondersteuning voor het exporteren van niet gebruikte flessen naar divelogs.de

- Betere verwerking van CNS-waarden bij het gebruik van meerdere duikcomputers

- Ondersteuning voor de Cressi Neon

- Ondersteuning voor de Sherwood Amphos 2.0

- Ondersteuning voor nieuwe gaswissel gegevens van EON Steel met FW 2.5

- Ondersteuning voor de nieuwste Mares Genius firmware

- Tekstuele serienummer ondersteuning voor veel duikcomputers

# Opgeloste problemen:

- Correcte OTU- en CNS-berekeningen voor geplande bailout

- Betere verwerking van CNS-waarden bij het gebruik van meerdere duikcomputers

- Mogelijke crash opgelost bij het wisselen van duiklogboeken

- Herstel foutieve cursor links/rechts snelkoppeling voor het tonen van meerdere duikcomputers

- Mogelijke crash (en andere fouten) opgelost bij het importeren van DL7 duiken

- Verbeterde afdrukgrootte voor gebeurtenis pictogrammen

- Mogelijke crash opgelost met Garmin Descent Mk2

- Fix HW Sport en Mares Genius firmware update


{% include desktop-release-bottom.MD %}
