---
layout: post
title:  "Lanzamiento de Subsurface 5.0.2"
lang:   "es"
categories: release
version: 5.0.2
previousVersion: 5.0.1
ref: subsurface-5.0.2
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subusurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión incluye algunas pequeñas mejoras, entre las que se encuentra el soporte para servidores de la nube distribuidos. También resuelve algunos fallos en {{ page.previousVersion }}. Cambios en Subsurface {{ page.version }}:

# nuevas características:

- nube: soporte para servidores de backup redundantes

- nube: intenta seleccionar un servidor cercano al usuario si es posible

- exportación: muestra diálogo de progreso mientras se exporta a TeX

- edición de inmersiones: se añade capacidad de copiar/pegar Nº de inmersión y fecha

- se incluye soporte para Suunto Eon Steel Black

- se añade soporte para Sherwood Beacon

- se añade soporte para la nueva variante de Zoop Novo

- se añade soporte para nuevas variantes de Shearwater Perdix AI

- se añade soporte para Sporasub SP2

# resolución de errores:

- escritorio: corrige borrado/edición de marcas en el perfil

- impresión: utiliza tamaño de fuente sensible incluso en tamaños de ventana extraños

- planificador: no se asciende automáticamente de manera inmediata

- planificador: corrige varios errores menores

- importación: corrige el análisis de las cadenas de cabeceras ADP traducidas

- core: previene fallo catastrófico al analizar ciertos archivos XML muy complejos

{% include desktop-release-bottom.MD %}
