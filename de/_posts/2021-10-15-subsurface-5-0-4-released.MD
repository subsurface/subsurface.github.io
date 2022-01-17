---
layout: post
title:  "Subsurface 5.0.4 veröffentlicht"
lang:   "de"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt einige Fehler in {{ page.previousVersion }}.

Neuerungen von Subsurface {{ page.version }}:

# Fehlerbehebungen:

- Desktop: Behebt Fehler, der auftritt, wenn mehrere ungültige
  Tauchgänge ausgewählt werden

- Medienimport: Bessere Unterstützung für große Zeitverschiebungen

- Tauchgangsplaner: Fehler in Berechung der MND für Gemische mit 21%
  Sauerstoff 

- Kern: Behebe Anzeige eines falschen Tauchgangsprofils in #3184

- Kern: Durch einen Fehler in 5.0.3 wurden einige Logbücher fehlerhaft
  abgespeichert und konnten dann nicht mehr eingelesen werden.

- Kern: Behebung eines Fehlers beim Lesen von sehr komplexen XML-Dateien


{% include desktop-release-bottom.MD %}
