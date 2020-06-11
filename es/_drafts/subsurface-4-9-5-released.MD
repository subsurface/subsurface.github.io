---
layout: post
title:  "Lanzamiento de Subsurface 4.9.5"
lang:   "es"
categories: release
version: 4.9.5
previousVersion: 4.9.4
ref: subsurface-4.9.5
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subusurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión corrige algunos problemas en {{ page.previousVersion }} y añade algunas pequeñas mejoras en import/export de archivos CSV. Algunos de los cambios en {{ page.Version }}:

# Nuevas funcionalidades:

  - import/export de archivos CSV: añade soporte para varias botellas

  - import/export de archivos CSV: añade soporte para modos de buceo

# Resolución de errores:

  - elimina un mensaje confuso al abrir el almacenamiento en la nube

  - mejora la selección de servicio en ordenadores de buceo con BLE

  - mejora el reconocimiento de ordenadores de buceo con BLE

  - actualiza el CAS y otros valores calculados al modificar la información de las botellas

  - refleja correctamente las preferencias del usuario de fecha y hora al modificarlas

  - corrige varios fallos en la interfaz de usuario del planificador

  - corrige el perfil de las inmersiones planificadas que incluyen segmentos en superficie

  - muestra el separador de millar en formato local en los valores de la salinidad

# libdivecomputer

  - solución relativa a una cosa rara en BLE (Oceanic Pro Plus X y Aqualung i770R)

  - mejoras en la actualización de firmware de OSTC3

{% include desktop-release-bottom.MD %}
