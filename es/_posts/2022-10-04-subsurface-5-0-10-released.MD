---
layout: post
title:  "Lanzamiento de 5.0.10"
lang:   "es"
categories: release
version: 5.0.10
previousVersion: 5.0.9
ref: subsurface-5.0.10
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión añade pequeñas funcionalidades y corrige algunos errores.

Cambios en Subsurface {{ page.version }}:

# Nueva funcionalidad:

- Se implementa vista ampliada en el perfil

- Ventana de información: se muestra un icono para los avisos

- Planificador: permite manipular mientras se hace zoom

- Se introduce un combo para mover sensores entre botellas

- Se elimina la lista de puntos de inmersión de las pestañas

# Corrección de errores:

- Importación: Se permite importar puntos de buceo sin UUID

- Lista de inmersiones: No se incluyen versiones planificadas de un buceo si existen datos reales

- Corrige la composición de textos en etiquetas y puntos de inmersión

# Soporte de ordenadores de buceo

- Soluciona la detección del ordenador Ratio en dispositivos BLE

{% include desktop-release-bottom.MD %}
