---
layout: post
title:  "Cambios en los lanzamientos de versiones"
lang:   "es"
date:   2023-12-28 14:30:00 -0700
categories: release
ref: release-changes
---

Han pasado muchas cosas en los 14 meses que han transcurrido desde nuestro último lanzamiento, incluyendo el habernos dado cuenta de que nuestro viejo enfoque de lanzar versiones no nos estaba funcionando ya. A raíz de esto hemos decidido intentar un enfoque distinto, en lugar de lanzamientos formales cada pocos meses con un incómodo proceso manual, cambiamos a dirigir a nuestros usuarios a la última "nightly build". Estas se actualizan después de cada cambio en la rama principal de desarrollo y, por tanto, siempre están al día.

Puesto que estas compilaciones se crean en un sistema CI/CD, no están firmadas, así que macOS y Windows mostrarán mensajes de aviso al instalarlas, pero, aparte de eso,  son idénticas a las que solíamos presentar antes.

Para macOS, Windows y Android puedes encontrar los binarios en la [página de GitHub de nightly builds](https://github.com/subsurface/nightly-builds/releases)

Linux: Ubuntu: añade `ppa:subsurface/subsurface-daily` a tus fuentes de software; el .deb de ese PPA también puede instalarse en versiones suficientemente actualizadas de *Debian*, *LinuxMint*, y algunas otras distribuciones derivadas de Debian.

Linux: Fedora: descarga desde nuestra [página COPR nightly release](https://copr.fedorainfracloud.org/coprs/dirkhh/Subsurface-test)
