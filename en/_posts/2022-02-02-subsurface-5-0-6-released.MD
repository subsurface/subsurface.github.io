---
layout: post
title:  "Subsurface 5.0.6 released"
lang:   "en"
categories: release
version: 5.0.6
previousVersion: 5.0.5
ref: subsurface-5.0.6
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This version adds a few small changes compared to {{ page.previousVersion }}.

Changes in Subsurface {{ page.version }}:

# new feature:

- statistics: implement ordering of categorical bar charts

# bug fixes:

- divelist: Don't attempt to compute SAC for CCR dives

- profile: fix editing of time / duration (profile of edited dive was not shown)

- profile: rewrite of part of the implementation which resulted in performance improvements

# dive computer support:

- Uwatec/Scubapro dive computers: restore the original standard gravity factor

- Garmin: fix gas change event parsing

{% include desktop-release-bottom.MD %}
