---
layout: post
title:  "Ankündigung der Version 4.9.5 von Subsurface"
lang:   "de"
categories: release
version: 4.9.5
previousVersion: 4.9.4
ref: subsurface-4.9.5
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt eine Reihe von Fehlern und bringt ausserdem ein paar kleine Verbesserungen beim Einlesen und Schreiben von CSV Dateni. Einige der Neuerungen in Subsurface {{ page.version }}:

# neue Features:

  - CSV Import/Export: Unterstützung für mehrere Flaschen

  - CSV import/export: Unterstützung des Tauchmodus

# behobene Fehler:

  - eine verwirrende Fehlermeldung beim Öffnen des Cloud Speichers wurde entfernt

  - verbesserte Auswahl des korrekten BLE Service für BLE Tauchcomputer

  - verbesserte Erkennung von BLE Tauchcomputern

  - korrekte Anzeige von berechneten Werten nach dem Ändern von Flaschendaten

  - korrekte Anwendung der Benutzereinstellungen für Datum und Zeit

  - mehrere Probleme in der Benutzeroberfläche des Planers wurden behoben

  - korrekte Anzeige des Tauchprofils für geplante Tauchgänge mit Oberflächensegment

  - korrekte Anzeige des Tausendersymbols

# libdivecomputer:

  - bessere Unterstützung von Pelagic BLE Tauchcomputern (Oceanic Pro Plus X und Aqualung i770R)

  - Verbesserungen für das Firmwareupdate eines OSTC3

{% include desktop-release-bottom.MD %}
