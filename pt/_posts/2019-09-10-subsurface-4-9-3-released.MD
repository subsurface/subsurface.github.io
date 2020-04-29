---
layout: post
title:  "Lançado o Subsurface 4.9.3"
lang:   "pt"
date:   2019-09-10 08:00:00 -0700
categories: release
version: 4.9.3
previousVersion: 4.9.1
ref: subsurface-4.9.3
---
A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão corrige um conjunto de problemas com a versão {{ page.previousVersion }} (Subsurface 4.9.2 criado mas nunca anunciado).

Algumas das alterações no Subsurface {{ page.version }}:


# correcção de problemas:

  - Desktop: fechar o widget dos locais de mergulho se o local for removido através de um "undo"

  - Desktop: não destruir o formato das notas ao editar notas no planeamento \[\#2265\]

  - Mapa: evitar carregar a totalidade do mapa ao clicar numa bandeira

  - Mapa: salientar todos os locais de mergulho ao clicar numa bandeira

  - Mapa: correcção do crash ao clicar numa bandeira com o Qt 5.9

  - Desktop: correcção do crash ao gravar legendas ou imagens do perfil de mergulho

  - Desktop: correcção do crash ao copiar e colar

  - Desktop: correcção do crash ao exportar para XML locais de mergulho com nodos vazios
  
  - Desktop: correcção da exibição da hora da viagm de mergulho

  - planeamento: correcção do cálculo do CNS para pO2 \> 1.6 bar

  - Mobile: permitir a edição do lastro para mergulhos sem informação de lastro

# libdivecomputer:

  - adicionado suporte para o Deepblu Cosmiq+

  - adicionado suporte para o Aqualung i200C

  - várias correcções de problemas


{% include desktop-release-bottom.MD %}
