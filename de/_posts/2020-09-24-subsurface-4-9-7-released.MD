---
layout: post
title:  "Subsurface 4.9.7 veröffentlicht"
lang:   "de"
categories: release
version: 4.9.7
previousVersion: 4.9.6
ref: subsurface-4.9.7
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt einige Probleme von {{ page.previousVersion }}
und enth&auml;lt einige Verbesserungen sowie Unterst&uuml;tzung
f&uuml;r eine Zahl neuer Tauchcomputer. Einige der Neuerungen
in Subsurface {{ page.version }}:

# Neue Features:

  - Profil: "Gaswechsel bearbeiten" im Kontextmen&uuml; [#2910]

  - Import: Parser f&uuml;r SeacSync db. Vorerst nutzt nur Seac Action das SeacSync-Pprogramm.

  - Unterst&uuml;tzung f&uuml;r Shearwater Peregrine (erfordert
    Firmware V81 oder neuer)

  - Unterst&uuml;tzung f&uuml;r Aqualung: i470TC

  - Unterst&uuml;tzung f&uuml;r Liquivision Kaon, Lynx, Xen, Xeo

  - Unterst&uuml;tzung f&uuml;r McLean Extreme

  - Unterst&uuml;tzung f&uuml;r Oceans S1

  - automatische Erkennung von weiteren BLE Tauchcomputern

# Bugfixes:
  
  - Bluetooth/rfcomm: Behebung von Problemen mit classic BT-Downloads
    auf Linux und Windows, MacOS ist weiterhin fehlerhaft.

  - Ausr&uuml;stung: Bereits einegtragene Gewichte werden nicht mehr
    &uuml;berschrieben, wenn der Gewichtstyp ge&auml;ndert wird. [#2938]

  - Ausr&uuml;stung: Suche findet auch Teilw&ouml;rter

  - Profil: Bessere Aufl&ouml;sung beim Export und Drucken

  - Kern: Automatische Numerierung importierter Tauchg&auml;nge repariert [#2731]

  - Kern: Zusammenf&uuml;hren von Tauchg&auml;ngen mit mehreren
    Flaschen repariert

  - Kern: Der aktuelle Tauchgang ist immer selektiert [#2961]

  - Kern: Aktualisierung des Filters beim Laden der Tauchgangsliste [#2961]

  - Medien: Zeitstempel des mvhd-Atoms von QuickTime/MP4 Videos wird
    ausgewertet. 

  - Planer: Salzgehalt richtig initialisieren

  - Planer: Segmente mit l&auml;nge 0 richtig behandeln

  - Planer: "O2 narkotisch" richig bei der Berechnung der MND
    ber&uuml;cksichtigen

  - Import: Behbung einiger Probleme beim Import aus der Shearwater
    Cloud 

  - Shearwater-Parser zur Unterst&uuml;tzung von PNF auf Petrel
    Tauchcomputern 

{% include desktop-release-bottom.MD %}
