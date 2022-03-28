---
layout: post
title:  "Lançado o Subsurface 5.0.8"
lang:   "pt"
categories: release
version: 5.0.8
previousVersion: 5.0.7
ref: subsurface-5.0.8
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão surge pouco tempo após o lançamento da versão {{ page.previousVersion }} e corrige um problema irritante que se encontra nos ficheiros binários dessa versão.


Mudanças no Subsurface {{ page.version }}:

# Nova funcionalidade:

- núcleo: adicinado suporte para caracteres de separação quando se usam coordenadas não-decimais

- perfil: apresentação dos dados dos sensores de pressão de outros computadores de mergulho, se disponíveis

- traduções: usa línguas relacionadas se a linguagem escolhida não estiver completa, antes de usar por defeito a língua inglesas (variante US)

# Correcção de problemas:

- Sistema de binários: corrige erro nos pacotes que evitava que os mapas fossem exibidos no Windows e macOS

{% include desktop-release-bottom.MD %}
