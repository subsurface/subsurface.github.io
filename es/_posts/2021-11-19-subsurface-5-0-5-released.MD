---
layout: post
title:  "Lanzamiento de Subsurface 5.0.5"
lang:   "es"
categories: release
version: 5.0.5
previousVersion: 5.0.4
ref: subsurface-5.0.5
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión efectúa un único cambio notable en relación a {{ page.previousVersion }}.

Cambios en Subsurface {{ page.version }}:

# nueva funcionalidad:

- Introduce "huellas" (fingerprints) del ordenador de buceo en los datos de la inmersión, incluidos los datos en la nube. De esta forma, la ubicación de la última descarga, en ordenadores que tengan esta característica, se comparte entre todos los dispositivos conectados a través de la nube de Subsurface. Esto es especialmente importante para ordenadores de buceo como el G2 que hace descargas muy lentas (especialmente usando BLE) si esta información no se encuentra disponible.


{% include desktop-release-bottom.MD %}
