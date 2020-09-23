---
layout: post
title:  "Lanzamiento de Subsurface 4.9.7"
lang:   "es"
categories: release
version: 4.9.7
previousVersion: 4.9.6
ref: subsurface-4.9.7
---

El equipo de desarrollo de Subsurface se complace en anunciar el lanzamiento de la versión {{ page.Version }} de Subusurface, un divelog y planificador de inmersiones de código abierto para Windows, Mac y Linux.

Esta versión corrige un problema significativo en {{ page.previousVersion }} y añade un par de pequeñas mejoras así como soporte para algunos nuevos ordenadores. Algunos de los cambio en {{ page.version }}:

# Nuevas funcionalidades:

  - Perfil: Añade una opción con el click derecho "Editar cambio de gas" [#2910]

  - Importación: Añade soporte para la base de datos SeacSync. Actualmente solo el Seac Action utiliza el programa SeacSync.

  - Añade soporte para el Shearwater Peregrine (necesario firmware V81 o posterior)

  - Añade soporte para Aqualung i470TC

  - Añade soporte para Liquidvision Kaon, Lynx, Xen y Xeo

  - Añade soporte para McLean Extreme

  - Añade soporte para Oceans S1

  - Añade reconocimiento automático de más ordenadores

# Resolución de errores:

  - Bluetooth/rfcomm: Corrige las descargas por BT tradicional en Linux y Windows; macOS sigue sin funcionar.

  - Equipo: No sobre escribe los lastres ya grabados al cambiar de tipo, [#2938]

  - Equipo: Ejecuta búsqueda por subcadenas para tipos de equipamiento.

  - Perfil: Mejora la resolución en la impresión y la exportación.

  - Núcleo: Corrige renumerar las inmersiones importadas [#2731]

  - Núcleo: Soluciona fallo al mezclar inmersiones con varias botellas

  - Núcleo: Se asegura que la inmersión actual siempre está seleccionada [#2961]

  - Núcleo: Actualiza el estado de los filtros al cargar la lista de buceos [#2961]

  - Medios: Lee la marca de tiempo desde mvhd en vídeos tipo QuickTime/MP4

  - Planificador: Inicializa correctamente la salinidad

  - Planificador: Maneja correctamente segmentos de longitud cero al replanificar.

  - Planificador: Tiene en cuenta la preferencia "O2 narcótico" al calcular la MND

  - Importación: Corrige un par de fallos el importar de Shearwater Cloud

  - Corrige el importador de Shearwater para soportar PNF en ordenadores Petrel

{% include desktop-release-bottom.MD %}
