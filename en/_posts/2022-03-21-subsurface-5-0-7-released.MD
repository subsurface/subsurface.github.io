---
layout: post
title:  "Subsurface 5.0.7 released"
lang:   "en"
categories: release
version: 5.0.7
previousVersion: 5.0.6
ref: subsurface-5.0.7
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac, and Linux.

This version adds a few small changes compared to {{ page.previousVersion }} and fixes a number of bugs.

Changes in Subsurface {{ page.version }}:

# new feature:

- profile: include profile editing in undo system

- general: rename dive master to dive guide

- dive list: make dive guide visible in dive list [#3382]

- equipment: allow manually asigning tank sensors to specific tanks (this helps divers with multiple dive computers each tracking pressure for a different tank)

- build-system: initial support for Qt6 (missing maps, user manual, printing, among other things)

- build-system: initial support for Apple M1 (using Qt6, see limitations above)

# bug fixes:

- core: avoid crash with corrupted cloud storage

- planner: make ESC (cancel plan) work when moving handles

- desktop: Don't lose cursor position in notes when switching between windows [#3369]

- build-system: don't rely on the git:// protocol when downloading sources

# dive computer support:

- Uemis support: fix the ability disconnect/reconnect the Zurich when its filesystem is full

- libdivecomputer: add support for latest BLE hardware in OSTC dive computers

- libdivecomputer: add support latest Shearwater firmware, including T3/T4 on Teric

- libdivecomputer: various other small changes


{% include desktop-release-bottom.MD %}
