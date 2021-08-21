---
layout: post
title:  "Subsurface 5.0.3 released"
lang:   "en"
categories: release
version: 5.0.3
previousVersion: 5.0.2
ref: subsurface-5.0.3
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This version adds a number of small improvements and also fixes a number of bugs in {{ page.previousVersion }}. One side effect is that an old feature (dive computer nicknames) that we believe not to be broadly used has changed behavior. The reason we believe this wasn't widely used is that a couple of changes in recent releases broke this feature in a subtle way, yet no one appeared to notice the problem. Subsurface sometimes got confused identifying dive computers and would get the nicknames wrong. And worse, it would also sometimes redownload already downloaded dives from certain dive computers. The fix for that problem is a bit drastic in that it only allows nicknames for dive computers that have a textual "Extra Info" serial number. Some of the changes in this release add that info for a very large subset of current dive computers, but there are quite a few that no longer can get nicknames. If this affects you, please reach out to us and let us know which dive computer you use and how you use nicknames.

Changes in Subsurface {{ page.version }}:

# new features:

- replace dive computer management with a new implementation, this fixes rare cases where Subsurface unnecessarily download already downloaded dives, but also means that some older style dive computer can no longer have nicknames

- add GPS fix downloaded from a dive comuter to existing dive site

- allow editing the profile for dives imported without samples (via CSV)

- add detection for Aladin A2 as BLE dive computer

- support exporting unused cylinders to divelogs.de

- improve handling of CNS values when combining multiple dive computers

- add support for Cressi Neon

- add support for Sherwood Amphos 2.0

- add support for new gas change data from EON Steel with FW 2.5

- add textual serial number support for many dive computers

# bugfixes:

- correct OTU and CNS calculations for planned bailout

- improve handling of CNS values when combining multiple dive computers

- avoid potential crash when switching divelogs

- fix broken curser left/right shortcut for showing multiple dive computers

- fix potential crash (and other errors) importing DL7 dives

- improve printout scaling for event icons

- fix potential crash with Garmin Descent Mk2

- fix HW Sport and Mares Genius firmware update


{% include desktop-release-bottom.MD %}
