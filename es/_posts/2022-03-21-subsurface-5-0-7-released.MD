---
layout: post
title:  "Lanzamiento de Subsurface 5.0.7"
lang:   "es"
categories: release
version: 5.0.7
previousVersion: 5.0.6
ref: subsurface-5.0.7
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión hace pequeños cambios en relación a {{ page.previousVersion }} y corrige algunos fallos.

Cambios en Subsurface {{ page.version }}:

# Nueva funcionalidad:

- Perfil: Incluye la edición de perfil en el sistema "deshacer/rehacer"

- General: Se cambia el nombre de "divemaster" a "guía"

- Lista de inmersiones: Hace visible ali guía en la lista de inmersiones [#3382]

- Equipo: Permite asignar sensores manualmente a determinadas botellas (esto permite a buceadores con varios ordenadores de buceo seguir las presiones de las diferentes botellas asignadas a cada ordenador)

- Sistema: Soporte inicial para Qt6 (perdiendo mapas, manual e impresión, entre otras cosas)

- Sistema: Soporte inicial para Apple M1 (usando Qt6, ver las limitaciones comentadas anteriormente)

# Resolución de errores:

- Core: Soluciona cuelgue si el almacenamiento en la nube se ha corrompido

- Planificador: Hace que funcione  ESC (cancelar plan) mientras se mueven las asas

- Escritorio: No se pierde la posición del cursor en las notas al cambiar entre ventanas [#3369]

- Sistema: Se deja de utilizar el protocolo git:// al descargar código fuente

# Soporte de ordenadores de buceo:

- Uemis : Soluciona los problemas para desconectar/re-conectar el Uemis cuando su sistema de archivos está lleno

- Libdivecomputer: Se añade soporte para el último hardware BLE en los ordenadores de buceo OSTC

- Libdivecomputer: Se añade soporte para el último firmware Shearwater, incluyendo T3/T4 en el Teric

- Libdivecomputer: Algunos otros pequeños cambios y correcciones


{% include desktop-release-bottom.MD %}
