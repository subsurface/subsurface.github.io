---
layout: post
title:  "Lanzamiento de Subsurface 4.9.8"
lang:   "es"
categories: release
version: 4.9.8
previousVersion: 4.9.7
ref: subsurface-4.9.8
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subusurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión corrige un problema significativo en {{ page.previousVersion }} y añade un par de pequeñas mejoras. La principal el nuevo, significativamente más flexibe, sistema de filtrado de la lista de inmersiones. Algunos de los cambios en {{ page.version }}:

# Nuevas funcionalidades:

 - Filtro: Sistema de filtrado más flexible basado en restricciones individuales

 - Añade soporte para Garmin Descent Mk2/Mk2i en Linux, macOS, y Windows de 64 bits

 - Añade soporte para Scubapro Aladin A2

 - Escritorio: Se permite añadir inmersiones a cualquier viaje

 - Equipo: Utiliza la pO2 de las preferencias para mostrar la POM

 - Core: Se pueden deshacer/rehacer los cambios en el equipo

 - Windows: Se generan binarios separados de 32bits y 64bits. La versión de 32bits no soporta el Garmin Descent Mk2/Mk2i

# Resolución de errores:

 - Escritorio: Se mejora la apariencia en modo "dark"

 - Escritorio: Se resuelve fallo al arrastrar/soltar en el widget de etiquetas [#3030]

 - Escritorio: Se respetan las teclas respect page-up, page-down, home and end para cambiar las selecciones [#2957]

 - Core: Se mejora el mezclado de presiones de botellas [#2884]

 - Windows: Se añade el tema moderno Vista que faltaba

 - macOS: Se resuelve problema con los ordenadores de buceo HID como el Suunto Eon Core/Steel [#2999]

{% include desktop-release-bottom.MD %}
