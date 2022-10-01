---
layout: post
title:  "Subsurface 5.0.10 released"
lang:   "en"
categories: release
version: 5.0.10
previousVersion: 5.0.9
ref: subsurface-5.0.10
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac, and Linux.

This version adds a number of small features a couple of bug fixes.

Changes in Subsurface {{ page.version }}:

# new feature:

- implement panning of the profile

- infobox: show an icon for warnings

- planner: allow handle manipulation in zoomed in state

- use combobox for moving sensor between cylinders

- remove divesite list from tab-widgets

# bug fixes:

- import: allow import of divesites without UUID

- divelist: do not include planned versions of a dive if there is real data

- fix key composition in tag widgets and dive site widget

# dive computer support

- fix Ratio dive computer detection for BLE only devices

{% include desktop-release-bottom.MD %}
