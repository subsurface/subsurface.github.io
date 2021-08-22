---
layout: post
title:  "Ankündigung der Version 5.0.2 von Subsurface"
lang:   "de"
categories: release
version: 5.0.2
previousVersion: 5.0.1
ref: subsurface-5.0.2
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version bringt einige kleine Verbesserungen, darunter einen geografisch verteilten Cloud Service. Sie behebt außerdem einige Probleme in früheren Versionen.

Einige der Neuerungen in Subsurface {{ page.version }}:

# Neue Features:

- Cloud: Unterstützung mehrerer Backend Server

- Cloud: Subsurface versucht einen geografisch "nahegelegenen" Cloud Server zu verwenden

- Export: zeige den Fortschritt beim TeX Export

- Tauchgang bearbeiten: jetzt können auch die Tauchgang Nummer und der Zeitpunkt des Tauchgangz kopiert werden

- Unterstützung des Suunto Eon Steel Black

- Unterstützung des Sherwood Beacon

- Unterstützung des new variant of Zoop Novo

- Unterstützung des new variants of Shearwater Perdix AI

- Unterstützung des Sporasub SP2

# Bugfixes:

- Desktop: Entfernen und Bearbeiten von Markierungen auf dem Tauchprofil sollte jetzt funktionieren

- Drucken: konsitente Schriftgröße

- Planner: vermeide einen sofortigen Aufstieg

- Planner: mehrere andere kleine Fehler sind behoben

- Import: das Importieren von übersetzten ADP Dateien funktioniert jetzt

- Core: vermeide einen möglichen Absturz mit komplexen XML Dateien

{% include desktop-release-bottom.MD %}
