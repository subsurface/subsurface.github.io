---
layout: post
title:  "Ankündigung der Version 4.9.6 von Subsurface"
lang:   "de"
categories: release
version: 4.9.6
previousVersion: 4.9.5
ref: subsurface-4.9.6
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version behebt ein größeres Problem in Version {{ page.previousVersion }}:

# behobene Fehler:

  - vermeidet einen Absturz bei der Verwendung der eingebauten FTDI Unterstützung (also mit 'FTDI' als Verbindung beim Herunterladen von Tauchdaten)

  - macht die eingebaute FTDI Unterstützung auf Macs wieder verfügbar (diese war versehentlich in den Versionen 4.9.4 und 4.9.5 nicht vorhanden)

{% include desktop-release-bottom.MD %}
