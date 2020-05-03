---
layout: post
title:  "Lanzamiento de Subsurface 4.9.4"
lang:   "es"
categories: release
version: 4.9.4
previousVersion: 4.9.3
ref: subsurface-4.9.4
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subusurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión corrige algunos problemas in {{ page.previousVersion }} y añade varias nuevas funcionalidades importantes. Algunos de los cambios en {{ page.Version }}:

# Nuevas funcionalidades:

  - Mapa: muestra el punto de buceo con un marcador al abrir Google Maps.

  - Deshacer: se implementa la opción de deshacer en eventos (visibilidad, marcadores, setpoints, cambios de gas)

  - Lista de inmersiones: Implementa la posibilidad de marcar inmersiones como "invalidas"

  - Filtro: añade modos de filtrado "empieza por" y "exacto" para la búsqueda por texto.

  - Información de la inmersión: añade la posibilidad de modificar la salinidad del agua.

  - Información de la inmersión: añade el factor de gradiente actual en la caja de información.

  - Información de la inmersión: Se elimina el tope en el número de botellas

  - Interfaz: Se aumenta la velocidad de la selección de múltiples viajes

  - Planificador: Se añade casilla de selección para marcar el oxígeno como narcótico

  - Planificador: mejora el redondeo de la duración de las paradas en las notas del planificador

# Resolución de errores:

  - Se soluciona la creación de nuevos tipos de botella (anteriormente los nombres no podían ser el comienzo de nombres que ya existieran)

  - Corrige el orden de las pestañas en la ventana de filtrado

  - Ignora puntos de buceo sin ubicación en la búsqueda por proximidad

  - Corrige problema con las AppImage de Linux que fallaban al comunicarse por  Bluetooth con los ordenadores de buceo \[\#2370\]

  - Se permite copia\&pega de varias botellas a la vez \[\#2386\]

  - No genera valores aleatorios de CAS para botellas sin datos \[\#2376\]

  - Guarda los cambios efectuados al hacer click en "hecho" en la pantalla de edición de los puntos de buceo

  - Actualiza la pestaña de estadísticas al hacer "deshacer" o "rehacer"

  - Actualiza los detalles de la inmersión al replanificar una inmersión \[\#2280\]

  - Cuando se exportan puntos de buceo en el modo de edición, exporta solo los puntos seleccionados \[\#2275\]

# libdivecomputer

  - Añade soporte para Oceanic Geo 4.0, ProPlus 4

  - Añade soporte para Scubapro Aladin A1

  - Añade soporte para Sherwood Wisdom 4

  - Corrige el manejo de presión de las botellas de Shearwater

  - Pequeñas correcciones

{% include desktop-release-bottom.MD %}
