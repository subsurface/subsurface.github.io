---
layout: post
title:  "Ankündigung der Version 5.0.3 von Subsurface"
lang:   "de"
categories: release
version: 5.0.3
previousVersion: 5.0.2
ref: subsurface-5.0.3
---

Das Subsurface-Entwicklungsteam ist stolz, die Version {{ page.version }} von Subsurface anzukündigen, einem Open-Source Tauchlogbuch und -Planungsprogramm für Windows, Mac und Linux.

Diese Version bringt einige kleinere neue Features und behebt einige Fehler in {{ page.previousVersion }}. Eine Nebenwirkung dieser Änderungen ist, dass ein älteres Feature (alternative Bezeichnungen für Tauchcomputer), welches aus unserer Sicht kaum benutzt wurde, sich jetzt etwas anders verhält. Wir nehmen an, dass diese Feature kaum benutzt wurde, da die letzten Versionen zu einem Fehler mit den Bezeichnungen für Tauchcomputermn geführt hatten, ohne dass wir dazu Fehlerberichte bekommen haben. In dieser Version können nur noch Tauchcomputer, die eine textuelle Seriennummer in den Extra Daten in Subsurface anzeigen, mit einer alternativen Bezeichnung versehen werden. Sollte dies ein Problem sein, wären wir über eine Nachricht dankbar.

Einige Neuerungen in Subsurface {{ page.version }}:

# neue Features:

- Neue Implementierung der Tauchconputer Verwaltung. Dies behebt das Problem, dass manchmal bereits heruntergeladene Tauchgänge erneut von Tauchcomputern heruntergeladen werden; als Nebenwirkung können manche Tauchcomputer keine alternative Bezeichnung mehr haben.

- Wenn GPS Information von einem Tauchcomputer heruntergeladen werden, und diese Daten mit bereits existierenden Daten für den selben Tauchgang verbunden werden, werden diese GPS Informationen zu einem existierenden Tauchplatz hinzugefügt.

- Tauchgang-Profile von CSV-importierten Tauchgängen können nun bearbeitet werden.

- Der Aladin A2 wird nun als BLE Tauchcomputer erkannt.

- Unbenutzte Flaschen können auf divelogs.de exportier werden.

- Verbesserte Behandlung der CNS Daten wenn mehrere Tauchcomputer für einen Tauchgang vorhanden sind.

- Unterstützung des Cressi Neon.

- Unterstützung des Sherwood Amphos 2.0

- Unterstützung der Firmware 2.5 der EON Steel Familie.

- Unterstützung der neuen Firmware für den Mares Genius

- Unterstützung textueller Seriennummern für die meisten aktuellen Tauchcomputer


# Bugfixes:

- Korrekte Berechnung von OTU und CNS für geplanten Bailout.

- Korrekte Berechnung des CNS Werte wenn mehrere Tauchcomputer kombiniert werden.

- Behebung eines potentiellen Absturzes beim Wechsel von Tauchlisten.

- Die rechts/links Tasten zum Wechsel zwischen mehreren Tauchcomputern funktionieren wieder.

- Mehrere Probleme mit dem Importieren von DL7 Dateien wurden behoben.

- Bessere Skalierung der Event-Icons beim Drucken.

- Ein möglicher Absturz beim Einlesen von Daten vom Garmin Descent Mk2 wurde behoben.

- Probleme beim Firmware Update des HW Sport und Mares Genius wurden behoben.


{% include desktop-release-bottom.MD %}
