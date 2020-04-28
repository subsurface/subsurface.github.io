---
layout: post
title:  "Subsurface 4.9.3 released"
lang:   "en"
date:   2019-09-10 08:00:00 -0700
categories: release
version: 4.9.3
previousVersion: 4.9.1
ref: subsurface-4.9.3
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release fixes a number of issues in {{ page.previousVersion }} (Subsurface 4.9.2 was tagged but never announced).

Some of the changes in Subsurface {{ page.version }}:


# bugfixes:

  - Desktop: close dive site widget if dive site is removed by undo

  - Desktop: Don’t destroy format of planner notes when editing dive notes \[\#2265\]

  - Map: avoid full map reload when clicking on flag

  - Map: highlight all selected dive sites when clicking on flag

  - Map: fix crash when clicking on flags in Qt 5.9

  - Desktop: fix crash when saving subtitles or profile picture

  - Desktop: fix copy & paste crash

  - Desktop: fix saving to XML with empty dive site taxonomies

  - Desktop: fix display of trip time

  - Planner: fix calculation of CNS for pO2 \> 1.6 bar

  - Mobile: allow editing weights for dives that have no weight

# libdivecomputer:

  - add support for Deepblu Cosmiq+

  - add support for Aqualung i200C

  - various bug fixes


{% include desktop-release-bottom.MD %}
