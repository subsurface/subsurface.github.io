---
layout: post
title:  "Ankündigung der Version 5.0.8 von Subsurface"
lang:   "de"
categories: release
version: 5.0.8
previousVersion: 5.0.7
ref: subsurface-5.0.8
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version ist ein recht schneller Nachfolger für die Version {{ page.previousVersion }}; sie behebt ein ärgerliches Problem, das sich in die offiziellen Pakete eingeschlichen hatte.

Einige der Neuerungen in Subsurface {{ page.version }}:

# Neue Features:

- Allgemein: Unterstützung für Trenn-Zeichen, wenn Koordinaten in Grad angegeben werden

- Profil: Anzeige der Daten eines Tankdruck-Sensors von einem anderen Tauchcomputer, falls verfügbar

- Übersetzungen: bessere Behandlung von verwandten Sprachen. Falls eine generische Sprachversion unterstützt wird, werden Übersetzungen zuerst aus der speziellen Sprache und dann aus der generischen Sprache angezeigt. Nur wenn keine der Übersetzungen einen Text enthält, wird dieser im englischen Original angezeigt.

# Bugfixes:

- die offiziellen Pakete für Windows und macOS zeigen nun wieder die Karten für Tauchplätze an

{% include desktop-release-bottom.MD %}
