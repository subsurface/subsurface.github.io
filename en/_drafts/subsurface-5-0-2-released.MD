---
layout: post
title:  "Subsurface 5.0.2 released"
lang:   "en"
categories: release
version: 5.0.2
previousVersion: 5.0.1
ref: subsurface-5.0.2
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This version adds a number of small improvements, including support for geo-distributed cloud backend servers. It also fixes a number of bugs in {{ page.previousVersion }}. Changes in Subsurface {{ page.version }}:

# new features:

- cloud: support redundandant backup servers

- cloud: try to pick a server close to the user if possible

- export: show progress dialog when exporting to TeX

- dive edit: add ability to copy and paste dive nr and date

- add support for Suunto Eon Steel Black

- add support for Sherwood Beacon

- add support for new variant of Zoop Novo

- add support for new variants of Shearwater Perdix AI

- add support for Sporasub SP2

# bugfixes:

- desktop: fix removal/editing of bookmarks on the profile

- printing: use sensible font size even for strange window size

- planner: don't immediately ascent automatically

- planner: various small bug fixes

- import: fix parsing of translated ADP header strings

- core: prevent crash when parsing certain very complex XML files

{% include desktop-release-bottom.MD %}
