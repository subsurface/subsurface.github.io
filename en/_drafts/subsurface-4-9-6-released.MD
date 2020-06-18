---
layout: post
title:  "Subsurface 4.9.6 released"
lang:   "en"
categories: release
version: 4.9.6
previousVersion: 4.9.5
ref: subsurface-4.9.6
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release fixes a significant issue in {{ page.previousVersion }}:

# bugfixes:

  - fix crash when using user space FTDI support (by entering 'FTDI' as 'device' for a download)

  - re-enable user space FTDI support on Mac (this was disabled by mistake in 4.9.4 and 4.9.5)

{% include desktop-release-bottom.MD %}
