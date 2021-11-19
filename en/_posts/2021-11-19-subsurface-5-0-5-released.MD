---
layout: post
title:  "Subsurface 5.0.5 released"
lang:   "en"
categories: release
version: 5.0.5
previousVersion: 5.0.4
ref: subsurface-5.0.5
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This version adds only one noteworthy change compared to {{ page.previousVersion }}.

Changes in Subsurface {{ page.version }}:

# new feature:

- include dive computer 'fingerprints' with the dive log data, including in the cloud. This way the last download location for dive computers that support this feature is shared between all devices connected via the Subsurface Cloud. This is especially important for dive computers like the G2 which cause very lengthy downloads (especially over BLE) if this information isn't available.


{% include desktop-release-bottom.MD %}
