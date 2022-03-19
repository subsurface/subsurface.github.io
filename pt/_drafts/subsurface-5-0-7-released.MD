---
layout: post
title:  "Lançado o Subsurface 5.0.7"
lang:   "pt"
categories: release
version: 5.0.7
previousVersion: 5.0.6
ref: subsurface-5.0.7
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão adiciona algumas pequenas mudanças em relação à {{ page.previousVersion }} e corrige alguns problemas.


Mudanças no Subsurface {{ page.version }}:

# Nova funcionalidade:

- Perfil: incluída a edição do perfil no sistema de desfazer («undo»)

- Geral: renomeado Dive Master para Guia de Mergulho

- Lista de mergulhos: tornar o campo «Guia de Mergulho» visível na lista [#3382]

- Equipamento: permite atribuir manualmente sensores de pressão a garrafas específicas (isto ajuda mergulhadores com vários computadores de mergulho a seguir as pressões de garrafas diferentes

- Sistema de compilação: suporte inicial para o Qt6 (ainda faltam os mapas, o manual de utilizador, a impressão, entre outras coisas)

- Sistema de compilação: suporte inicial para o Apple M1 (com o Qt6 --- ver as limitações acima)

# Correcção de problemas:

- Núcleo: evita crash com armazenamente remoto corrupto

- Planeamento: faz com que premir a tecla ESC (cancelar plano) funcione ao movimentar os pontos

- Desktop: não perde a posição do cursor nas notas ao alternar entre janelas [#3369]

- Sistema de compilação: não usar o protocolo git:// ao descarregar o código-fonte

# Suporte a computadores de mergulho:

- Uemis: corrige a possibilidade de desligar/ligar novamente o Zurich quando o seu sistema de ficheiros está cheio

- libdivecomputer: adicionado suporte para o hardware BLE mais recente nos computadores OSTC

- libdivecomputer: adicionado suporte para o mais recente firmware Shearwater, incluíndo o T3/T4 no Teric

- libdivecomputer: pequenas alterações variadas


{% include desktop-release-bottom.MD %}
