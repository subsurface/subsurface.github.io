---
layout: post
title:  "Subsurface 5.0.8 released"
lang:   "en"
categories: release
version: 5.0.8
previousVersion: 5.0.7
ref: subsurface-5.0.8
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac, and Linux.

This version is a quick follow up to {{ page.previousVersion }} and fixes an annoying bug that snuck into the builds of that release.

Changes in Subsurface {{ page.version }}:

# new feature:

- core: add support for separator characters when using degree-style coordinates

- profile: plot sensor data from other dive computer if available

- translations: fall back to related translations (before falling back to US English)

# bug fixes:

- build-system: fix packaging errors that prevented maps from being shown on Windows and macOS

{% include desktop-release-bottom.MD %}
