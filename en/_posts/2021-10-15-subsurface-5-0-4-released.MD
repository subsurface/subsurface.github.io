---
layout: post
title:  "Subsurface 5.0.4 released"
lang:   "en"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This version fixes a number of bugs in {{ page.previousVersion }}.

Changes in Subsurface {{ page.version }}:

# bugfixes:

- desktop: fix potential crash when selecting multiple dives marked invalid

- picture import: better support for large time stamp deltas

- planner: fix a bug setting the MND for gasmix with 21% oxygen

- core: fix off-by-one causing incorrect profile display #3184

- core: due to a bug in 5.0.3 certain dive logs were incorrectly stored and couldn't subsequently be read back

- core: fix potential crashes with very complex XML files


{% include desktop-release-bottom.MD %}
