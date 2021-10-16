---
layout: post
title:  "Lanzamiento de Subsurface 5.0.4"
lang:   "es"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión corrige una serie de fallos observados en {{ page.previousVersion }}.
Cambios en Subsurface {{ page.version }}:

# Resolución de errores:

- Escritorio: Corrige fallo potencial al seleccionar múltiples inmersiones marcadas como "invalidas".

- Importación de fotos: Mejor soporte de diferencias de tiempo grandes.

- Planificador: corrige error al fijar la PNM en mezclas con 21% de oxígeno.

- Núcleo: corrige "off-by-one" que producía un perfil incorrecto #3184

- Núcleo: debido a un fallo en 5.0.3 ciertos divelogs se guardaban incorrectamente y luego no se podían recuperar.

- Núcleo: corrige fallos potenciales con archivos XML muy complejos.


{% include desktop-release-bottom.MD %}
