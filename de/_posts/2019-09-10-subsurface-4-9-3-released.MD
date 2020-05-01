---
layout: post
title:  "Ankündigung der Version 4.9.3 von Subsurface"
lang:   "de"
date:   2019-09-10 08:00:00 -0700
categories: release
version: 4.9.3
previousVersion: 4.9.1
ref: subsurface-4.9.3
---

Das Subsurfe-Entwicklingsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt eine Reihe von Fehlern und bringt ausserdem ein paar neu Features seit Version {{ page.previousVersion }} (Subsurface 4.9.2 wurde zwar erzeugt, aber niemals angekündigt).

Einige der Neuerungen in Subsurface {{ page.version }}:


# behobene Fehler:

  - Desktop: schließe die Tauchplatz-Seite, wenn ein Tauchplatz mittels 'rückgängig machen' entfernt wurde

  - Desktop: behalte die Formatierung der Tauchplan-Notizen nach dem sie bearbeitet wurden \[\#2265\]

  - Karte: kein komplettes Neu-Laden der Karte, wenn auf eine Fahne geklickt wurde

  - Karte: zeige alle ausgewählten Tauchplätze, wenn auf eine Fahne geklickt wurde

  - Karte: beseitige einen Absturz, wenn in Qt 5.9 basierten Programmen auf eine Fahne geklickt wurde

  - Desktop: behebe einen Absturz beim Speichern von Untertiteln oder Profil-Bildern

  - Desktop: behebe einen Absturz beim Kopieren von Daten

  - Desktop: behebe ein Problem bei Speichern als XML im Fall leerer Tauchplazt Taxonomie

  - Desktop: zeige die korrekte Zeit für Tauchreisen

  - Planner: korrekte Berechnung der CNS für pO2 \> 1.6 bar

# libdivecomputer:

  - Unterstützung des Deepblu Cosmiq+

  - Unterstützung des Aqualung i200C

  - zahlreiche kleinere Fehler behoben


{% include desktop-release-bottom.MD %}
