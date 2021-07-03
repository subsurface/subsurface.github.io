---
layout: post
title:  "Lançado o Subsurface 5.0.2"
lang:   "pt"
categories: release
version: 5.0.2
previousVersion: 5.0.1
ref: subsurface-5.0.2
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão  {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão implementa algumas pequenas melhorias, incluindo o suporte para servidores remotos distribuídos geográficamente. Corrige também alguns problenas com a versão {{ page.previousVersion }}. Algumas das mudanças no Subsurface {{ page.version }}:


# novas funcionalidades:

- «nuvem»: suporta servidores remotos redundantes

- «nuvem»: tenta escolher um servidor remoto mais perto do utilizador (se possível)

- exportação: mostra o progresso ao exportar registos para o formato TeX

- edição de mergulhos: adiciona a possibilidade de copiar e colar o nº do mergulho e a sua data

- adicionado suporte para o computador Suunto Eon Steel Black

- adicionado suporte para o computador Sherwood Beacon

- adicionado suporte para uma nova variante do computador Zoop Novo

- adicionado suporte para uma novas variantes do computador Shearwater Perdix AI

- adicionado suporte para o computador Sporasub SP2

# correcção de problemas:

- desktop: corrigida a remoção/edição dos «bookmarks» no perfil

- impressão: usa um tamanho de fonte eazoável mesmo num tamanho de janela estranho

- planificador: não subir imediatamente de forma automática

- planificador: correcção de vários pequenos problemas

- importação: corrigida a leitura das strings dos cabeçalhos ADP

- núcleo: prevenção de falha ao ler certos ficheiros XML muito complexos

{% include desktop-release-bottom.MD %}
