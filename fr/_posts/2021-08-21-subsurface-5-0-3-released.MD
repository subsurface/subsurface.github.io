---
layout: post
title: "Annonce Subsurface 5.0.3"
lang: "fr"
categories: release
version: 5.0.3
previousVersion: 5.0.2
ref: subsurface-5.0.3
---

L'équipe de développement de Subsurface est fière de vous annoncer la version {{ page.version }} de Subsurface, un carnet de plongée et planificateur open source pour Windows, Mac and Linux.

Cette version apporte une série de petites améliorations et solutionne de nombreux problèmes de {{ page.previousVersion }}. Un effet indésirable est que d'anciennes fonctionnalités (comme le surnom des ordinateurs de plongée) qui sont rarement utilisées ne seront plus disponibles. La raison pour laquelle nous estimons que cette fonction est peu utilisée est que plusieurs modificatioins dans les versions récentes ont désactivé cette fonction d'une façon discrète, et personne n'a visiblement remarqué sa disparition. Subsurface avait parfois des difficultés à identifier les ordinateurs de plongée et utilisait un mauvais surnom. Et pire, cela menait à télécharger à nouveau des plongées déjà téléchargées depuis certains ordinateurs de plongée. La solution à ce problème est relativement drastique sachant que cela ne permet d'utiliser un surnom que pour les ordinateurs de plongée qui ont un numéro de série "Extra info" textuel. Certains des changements dans cette version ajoutent cette information dans un large ensemble d'ordinateurs de plongée, mais un petit nombre d'entre eux ne pourront plus utiliser les surnoms. Si vous êtes dans le cas, faites-nous savoir quel ordinateur de plongée vous utilisez et nous vous indiquerons comment utiliser les surnoms.

Modifications dans Subsurface {{ page.version }}:

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
