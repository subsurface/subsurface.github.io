---
layout: post
title:  "Subsurface 4.9.7 released"
lang:   "en"
categories: release
version: 4.9.7
previousVersion: 4.9.6
ref: subsurface-4.9.7
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release fixes a number of issues in {{ page.previousVersion }} and adds a couple of minor enhancements as well as support for quite a few new dive computers. Some of the changes in Subsurface {{ page.version }}:

# new features:

  - profile: add an "Edit Gas Change" right-click option [#2910]

  - import: add parser for SeacSync db. Currently only Seac Action uses SeacSync program.

  - add support for Shearwater Peregrine (requires firmware V81 or newer)

  - add support for Aqualung: i470TC

  - add support for Liquivision Kaon, Lynx, Xen, Xeo

  - add support for McLean Extreme

  - add support for Oceans S1

  - add automatic recognition of more BLE dive computers

# bugfixes:
  
  - bluetooth/rfcomm: fix broken classic BT downloads on Linux and Windows; macOS is still broken

  - equipment: don't overwrite already set weights when changing weight type [#2938]

  - equipment: do substring search for equipment types

  - profile: improve resolution in printing and export

  - core: fix renumbering of imported dives [#2731]

  - core: fix broken merging of dives with multiple cylinders

  - core: make sure current dive is always selected [#2961]

  - core: update filter status when loading dive list [#2961]

  - media: read timestamp from mvhd atom of QuickTime/MP4 style videos

  - planner: properly initialize salinity

  - planner: handle zero length segments gracefully when replanning

  - planner: honor the "O2 narcotic" preference when computing MND

  - import: fix a copule of bugs on Shearwater Cloud import

  - fix Shearwater parser to support PNF on Petrel dive computers

{% include desktop-release-bottom.MD %}
