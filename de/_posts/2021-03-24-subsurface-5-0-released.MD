---
layout: post
title:  "Ankündigung der Version 5.0 von Subsurface"
lang:   "de"
categories: release
version: 5.0
previousVersion: 4.9.10
ref: subsurface-5.0.0
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Dieses Major-Release bringt eine komplette &Uuml;berarbeitung des
Statistik-Teils mit vielen neuen Features und beeindruckenden
grafischen Statistiken &uuml;ber deine Tauchg&aumk;nge. Damit kannst
du viele verschiedene Gr&ouml;&szlig;en gegeneinander zu plotten und
bietet Balkengrafen, Tortengrafen und Scatter-Plot mit Regressionsgraden.

Diese Version behebt einige Probleme von {{ page.previousVersion }}
und enth&auml;lt einige Verbesserungen sowie Unterst&uuml;tzung
f&uuml;r eine Zahl neuer Tauchcomputer. Einige der Neuerungen
in Subsurface {{ page.version }}:

# Neue Features:

- Komplette &Uuml;berarbeitung des Statistik-Teils mit vielen neuen
F&auml;higkeiten

- Voreinstellung zum Ausschalten von Standardflaschen

- Planer: Automatische Setpoint-Wechsel an vorbestimmten Tiefen im
CCR-Modus

- Mares Horizon Unterst&uuml;tzung 

- Sherwood Sage Unterst&uuml;tzung

- Unterst&uuml;tzung f&uuml;r 2021er Modelle von Ratio

# Bugfixes:

- Beschleunigung der Auswahl mehrerer Tauchg&auml;nge

- Berechnung von CNS und OTU im PSCR-Modus

- Berechnung von CNS und OTU im CCR-Modus bei Tiefen unter 6m

- Undo: Speichern in git nach Hinzuf&uuml;gen von Blei

- Undo: Zur&uuml;cksetzen des Tauchmodus bei Undo eines
  Hinzugef&uuml;gten Setpointwechsels

{% include desktop-release-bottom.MD %}
