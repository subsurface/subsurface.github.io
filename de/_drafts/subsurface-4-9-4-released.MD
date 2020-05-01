---
layout: post
title:  "Subsurface 4.9.4 released"
lang:   "de"
categories: release
version: 4.9.4
previousVersion: 4.9.3
ref: subsurface-4.9.4
---

Das Subsurfe-Entwicklingsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt eine Reihe von Fehlern und bringt ausserdem ein paar neu Features seit Version {{ page.previousVersion }}. Einige der Neuerungen in Subsurface {{ page.version }}:

# neue Features:

  - maps: show the dive site as marker when opening Google Maps

  - undo: implement undo of event handling (viz. bookmarks, setpoints, gas switches)

  - undo: make dive replanning undoable

  - dive-list: implement dive invalidation

  - filter: implement fulltext search

  - filter: add starts-with and exact filter modes for textual search

  - dive-info: add the ability to modify dive salinity

  - dive-info: add current GF to infobox

  - dive-info: remove restriction on number of cylinders

  - UI: increase speed of multi-trip selection

  - planner: add checkbox on considering oxygen narcotic

  - planner: improve rounding of stop durations in planner notes

# behobene Fehler:

  - fix creation of new cylinder types (names couldn’t be the start of already existing names)

  - fix tab-order in filter widget

  - ignore dive sites without location in proximity search

  - fix issue with Linux AppImage failing to communicate with Bluetooth dive computers \[\#2370\]

  - allow copy\&pasting of multiple cylinders \[\#2386\]

  - don’t output random SAC values for cylinders without data \[\#2376\]

  - register changes when clicking "done" on dive-site edit screen

  - update statistics tab on undo or redo

  - update dive details when replanning dive \[\#2280\]

  - when exporting dive sites in dive site mode, export selected dive sites \[\#2275\]

# libdivecomputer:

  - neu: Unterstützung für Oceanic Geo 4.0, ProPlus 4

  - neu: Unterstützung für Scubapro Aladin A1

  - neu: Unterstützung für Sherwood Wisdom 4

  - Verbesserung der Verarbeitung von Shearwater Daten zum Flaschendruck

  - mehrere andere kleine Verbesserungen

{% include desktop-release-bottom.MD %}
