---
layout: post
title:  "Subsurface 5.0.9 released"
lang:   "en"
categories: release
version: 5.0.9
previousVersion: 5.0.8
ref: subsurface-5.0.9
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac, and Linux.

This version is a quick follow up to {{ page.previousVersion }} and fixes an annoying bug that snuck into the builds of that release.

Changes in Subsurface {{ page.version }}:

# new feature:

- desktop: allow more than one media file to be imported from web

- desktop: improve UX for cloud email/password checking

- filter: normalize unicode code points to base letter (for searching ℓ, etc.)

# dive computer support

- add support for the Seac Screen and Action

- add support for the Cressi Michelangelo

- add support for the new version of the Aqualung i200C

- add support for the Shearwater Petrel 3 and Perdix 2

- add support for the Ratio iX3M 2

- add support for the Sherwood Amphos Air 2.0

# bug fixes:

- core: when modifying cylinders across multiple dives, match cylinder number before comparing type

- core: merge all properties in a dive, including current, waveheight, etc

- core: prevent crash when merging dives without cylinders (as we might get when importing from divelogs.de)

- core: work around bug in TecDiving dive computer reporting spurious 0 deg C water temperature in first sample

- core: correctly parse DC_FIELD_SALINITY response; fixes incorrect water type with some dive computers, including the Mares Smart

- undo: clear undo stack when the current file is closed

- build-system: various updates for newer Linux distributions

# dive computer support

- Garmin: correctly deal with short format filenames

- Garmin: correctly parse dive mode

{% include desktop-release-bottom.MD %}
