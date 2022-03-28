---
layout: post
title:  "Lanzamiento de Subsurface 5.0.8"
lang:   "es"
categories: release
version: 5.0.8
previousVersion: 5.0.7
ref: subsurface-5.0.8
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión es un continuación rápida de {{ page.previousVersion }} y resuelve un molesto problema que apareció en las compilaciones de esa versión.

Cambios en  Subsurface {{ page.version }}:

# Nueva funcionalidad:

- Core: Añade soporte para caracteres separadores al utilizar coordenadas en formato "grados"

- Perfil: Traza datos de sensores de otros ordenadores, si están disponibles

- Traducciones: Recurre a traducciones relacionadas (antes de recurrir a inglés USA)

# Resolución de errores:

- Sistema de compilación: Corrige errores de empaquetado que hacían que no se mostraran los mapas en Windows y macOS

{% include desktop-release-bottom.MD %}
