---
layout: post
title:  "Lançado o Subsurface 5.0.10"
lang:   "pt"
categories: release
version: 5.0.10
previousVersion: 5.0.9
ref: subsurface-5.0.10
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão adiciona algumas funções e corrige alguns problemas.

Mudanças no Subsurface {{ page.version }}:


# Novas funcionalidades:

- implementa a deslocação do perfil

- caixa de informação: apresenta um ícone para os avisos

- planificador: permite a manipulação dos pontos com o perfil aumentado

- usa uma caixa para mover o sensor de pressão entre garrafas

- remove a lista dos locais de mergulho das alhetas

# Correcção de problemas:

- importação: permite a importação de locais de mergulho sem UUID

- lista de mergulhos: não incluir as versões de planeamento de um mergulho se existirem dados reais sobre o mergulho

- corrige a composição de texto em etiquetas e locais de mergulho

# Suporte a computadores de mergulho:

- fix Ratio dive computer detection for BLE only devices

- corrige a detecção do computador de mergulho Ratio em dispositivos BLE

{% include desktop-release-bottom.MD %}
