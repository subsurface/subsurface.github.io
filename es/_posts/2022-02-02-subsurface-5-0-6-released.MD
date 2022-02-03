---
layout: post
title:  "Lanzamiento de Subsurface 5.0.6"
lang:   "es"
categories: release
version: 5.0.6
previousVersion: 5.0.5
ref: subsurface-5.0.6
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión hace pequeños cambios en relación a {{ page.previousVersion }}.

Cambios en Subsurface {{ page.version }}:

# Nueva funcionalidad:

- Estadísiticas : Implementa ordenar los diagramas de barras por categorías

# Resolución de errores:

- Lista de inmersiones: No se intenta calcular el CAS en buceos con CCR

- Perfil: Corrige la edición de hora/duración (no se mostraba el perfil de la inmersión editada)

- Perfil: Se reescribe parte de la implementación lo que supone una mejoría en su funcionamiento

# Soporte de ordenadores de buceo:

- Ordenadores Uwatec/Scubapro: Se reestablece el factor de gravedad estandar original

- Garmin: Se corrige la lectura de eventos de cambio de gas

{% include desktop-release-bottom.MD %}
