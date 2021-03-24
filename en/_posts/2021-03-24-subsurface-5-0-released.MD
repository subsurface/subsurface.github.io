---
layout: post
title:  "Subsurface 5.0 released"
lang:   "en"
categories: release
version: 5.0
previousVersion: 4.9.10
ref: subsurface-5.0.0
---

The Subsurface development team proudly announces the release {{ page.version }} of Subsurface, an open source dive log and dive planning program for Windows, Mac and Linux.

This release brings a complete rewrite of statistics code with many new features and powerful visual statistics for your diving. It allows analysis of various variables against each other and provides standard bar charts, histograms, pie charts, and also scatter plots with regression line calculation.

This version also fixes a few bugs in {{ page.previousVersion }}. Changes in Subsurface {{ page.version }}:

# new features:

- complete rewrite of the statistics code, significantly expanding capabilities

- add preferences option to disable default cylinder types

- planner: allow automatic setpoint changes at specified depths in CCR mode

- add Mares Horizon support

- add Sherwood Sage support

- add support for Ratio 2021 models

# bugfixes:

- make selection of multiple dives reasonable fast

- take into account PSCR pO2 drop when computing CNS and OTU

- fix OTU und CNS calculations for CCR dives at shallow depths

- undo: save to git after editing weights

- undo: reset dive-mode on undo of set-point addition

{% include desktop-release-bottom.MD %}
