---
layout: post
title:  "Subsurface 4.9.8 released"
lang:   "en"
categories: release
version: 4.9.8
previousVersion: 4.9.7
ref: subsurface-4.9.8
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release fixes a number of issues in {{ page.previousVersion }} and adds a couple of new features. The highlight is the new, significantly more flexible dive list filtering setup. Some of the changes in Subsurface {{ page.version }}:

# new features:

 - filter: more flexible filtering system based on individual constraints

 - add Garmin Descent Mk2/Mk2i support for Linux, macOS, and 64bit Windows

 - add Scubapro Aladin A2 support

 - desktop: allow adding dives to arbitrary trips

 - equipment: use pO2 from prefernces for MOD display

 - core: make device management undoable

 - Windows: add separate 32bit and 64bit builds - the 32bit build does NOT support the Garmin Descent Mk2/Mk2i

# bugfixes:

 - desktop: improve the appearance in dark mode

 - desktop: fix crash on drag&drop into tag widgets [#3030]

 - desktop: respect page-up, page-down, home and end keys for selection change [#2957]

 - core: improve merging of cylinder pressures [#2884]

 - Windows: add missing modern Vista theme

 - macOS: fix issue with HID dive computers like Suunto Eon Core/Steel [#2999]

{% include desktop-release-bottom.MD %}
