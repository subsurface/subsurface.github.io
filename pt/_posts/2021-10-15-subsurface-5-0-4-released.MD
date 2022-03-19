---
layout: post
title:  "Lançado o Subsurface 5.0.4"
lang:   "pt"
categories: release
version: 5.0.4
previousVersion: 5.0.3
ref: subsurface-5.0.4
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão implementa algumas pequenas melhorias e corrige alguns problenas com a versão {{ page.previousVersion }}.

Mudanças no Subsurface {{ page.version }}:

# correcção de problemas:

- desktop: correção de falhas potencias ao selecionar vários mergulhos marcados como inválidos

- importação de imagens: Melhor suporte de grandes diferenças temporais

- planificador: corrige um problema de cálculo do MND para misturas com 21% de oxigénio

- núcleo: corrige o "off-by-one" de causar a exibição incorreta do perfil #3184

- núcleo: devido a um problema na versão 5.0.3 certos registos de mergulho foram incorretamente
  armazenados e não puderam ser posteriormente recuperados.

- núcleo: correção de falhas potenciais com ficheiros XML muito complexos


{% include desktop-release-bottom.MD %}
