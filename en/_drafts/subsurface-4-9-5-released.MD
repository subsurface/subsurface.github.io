---
layout: post
title:  "Subsurface 4.9.5 released"
lang:   "en"
categories: release
version: 4.9.5
previousVersion: 4.9.4
ref: subsurface-4.9.5
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release fixes a number of issues in {{ page.previousVersion }} and adds some minor enhancements for CSV import/export. Some of the changes in Subsurface {{ page.version }}:

# new features:

  - CSV import/export: support multiple cylinders

  - CSV import/export: support dive modes

# bugfixes:

  - remove confusing warning message when opening cloud storage

  - improve service selection for BLE dive computers

  - improve recognition of BLE dive computers

  - update SAC and other calculated values when changing cylinder information

  - correctly reflect user preferences for date and time after changing

  - fix several UI issues in the planner

  - fix profile display of planned dives with surface segments

  - localize thousand separator in salinity values

# libdivecomputer:

  - work around Pelagic BLE oddity (Oceanic Pro Plus X and Aqualung i770R)

  - OSTC3 firmware update improvements

{% include desktop-release-bottom.MD %}
