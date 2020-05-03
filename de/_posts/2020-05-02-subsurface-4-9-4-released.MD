---
layout: post
title:  "Subsurface 4.9.4 released"
lang:   "de"
categories: release
version: 4.9.4
previousVersion: 4.9.3
ref: subsurface-4.9.4
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt eine Reihe von Fehlern und bringt ausserdem ein paar neue Features seit Version {{ page.previousVersion }}. Einige der Neuerungen in Subsurface {{ page.version }}:

# neue Features:

  - Karte: Zeigt den Tauchplatz als Marker in Google Maps

  - Undo: Rückgängigmachen von Bearbeitung von Ereignissen
    (Lesezeichen, Setpoints, Gaswechsel)

  - Undo: Veränderung von Tauchgängen im Planer kann rückgängig
    gemacht werden

  - Tauchgangsliste: Tauchgänge können ungültig gemacht werden.

  - Filter: Volltextsuche

  - Filter: Beginnt-mit und genaue Übereinstimmung bei Suche

  - Salzgehalt kann eingestellt werden

  - Momentaner Gradientenfaktor wird in der Infobox angezeigt

  - Keine Beschänkung der Tauchflaschenzahl mehr

  - Beschleunigung beim Anwählen vieler Reisen

  - Im Planer kann eingestellt werden, ob Sauerstoff als narkotisch
    behandelt werden soll

  - Planner: Verbesserte Rundung bei der Anzeige von Stopplängen im Dekoplan

# behobene Fehler:

  - Flaschenbezeichnungen können jetzt auch mit bereits bekannten
    Namen beginnen

  - Reihenfolge der Reiter im Filter-Widget

  - Ignoriert Tauchplätze ohne Koordinaten in der Umgebungssuche

  - behebt Problem des AppImage in der Kommunikation mit Bluetooth-Tauchcomputern

  - Kopieren-Einfügen von mehreren Flaschen

  - Keine fälschlichen-AMV Werte für Flaschen ohne ausreichende Daten

  - Speichern von Änderungen beim Klicken auf der Tauchplatz-Bearbeitungsseite

  - Statistikreiter wird bei Undo und Redo aktualisiert

  - Tauchgangsdetails werden beim Wieder-Planen aktualisiert

  - Beim Exportieren von Tauchplätzen werden die angewählten
    Tauchplätze exportier

# libdivecomputer:

  - neu: Unterstützung für Oceanic Geo 4.0, ProPlus 4

  - neu: Unterstützung für Scubapro Aladin A1

  - neu: Unterstützung für Sherwood Wisdom 4

  - Verbesserung der Verarbeitung von Shearwater Daten zum Flaschendruck

  - mehrere andere kleine Verbesserungen

{% include desktop-release-bottom.MD %}
