---
layout: post
title:  "Lanzamiento de Subsurface 5.0.9"
lang:   "es"
categories: release
version: 5.0.9
previousVersion: 5.0.8
ref: subsurface-5.0.9
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.version }} de Subsurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Changes in Subsurface {{ page.version }}:

# Nueva funcionalidad:

- Escritorio:  Permite que se importe desde la web más de un archivo de medios

- Escritorio: Mejora la interfaz de usuario para la comprobación de correo/password de la nube

- Filtros: Normaliza los caracteres unicode a sus letras básicas (para buscar ℓ, etc.)

# Soporte de ordenadores de buceo

- Se añade soporte para los Seac Screen y Action

- Se añade soporte para el Cressi Michelangelo

- Se añade soporte para la nueva versión del Aqualung i200C

- Se añade soporte para el Shearwater Petrel 3 y Perdix 2

- Se añade soporte para el  Ratio iX3M 2

- Se añade soporte para el Sherwood Amphos Air 2.0

# Resolución de errores:

- Core: Al modificar botellas en varias inmersiones, comprueba el número de botellas antes de comparar los tipos

- Core: Mezcla todas las propiedades de una inmersión, incluyendo corriente, altura de las olas, etc

- Core: Evita que el programa termine si se mezclan inmersiones sin botellas (como se pueden encontrar al importar de divelogs.de)

- Core: Apaño en torno a error en el ordenador de buceo TecDiving que reporta la temperaatura del agua a 0 grados en la primera muestra

- Core: Lee correctamente el campo DC_FIELD_SALINITY; corrige lecturas incorrectas del tipo de agua en algunos ordenadores, por ejemplo el Mares Smart

- Deshacer: Vacía la pila de acciones al cerrar el divelog activo

- Sistema de compilado: Varias actualizaciones para las distribuciones de Linux más recientes

# Ordenadores de buceo

- Garmin: Maneja correctamente los nombres de archivo en formato corto

- Garmin: Lee correctamente el modo de buceo

{% include desktop-release-bottom.MD %}
