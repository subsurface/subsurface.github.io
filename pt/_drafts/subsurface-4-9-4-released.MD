---
layout: post
title:  "Subsurface 4.9.4 released"
lang:   "pt"
categories: release
version: 4.9.4
previousVersion: 4.9.3
ref: subsurface-4.9.4
---


A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão  {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.
Esta versão resolve alguns problemas da versão {{ page.previousVersion }} e adiciona algumas características novas. Algumas das mudanças no Subsurface {{ page.version }}:


# novas funções:

  - mapas: mostra o local de mergulho como um marcador ao abrir o Google Maps

  - undo: implementação do "undo" na manipulação de eventos (bookmarks, setpoints, trocas de gás)

  - undo: permitir desfazer alterações no replaneamento de mergulhos

  - lista de mergulhos: implementação da invalidação de mergulhos

  - filtro: implementação da busca por texto

  - filtro: adicionado modos de filtro para busca por texto: "começa por" e "exacto"

  - informações do mergulho: adicionada a capacidade de modificar a salinidade

  - informações do mergulho: adicionado o GF corrente à caixa de informações

  - informações do mergulho: removida a restrição ao número de garrafas

  - UI: aumentada a velocidade de selecção de várias viagens de mergulho

  - planificador: adicionada checkbox para considerar o oxigénio como narcótico

  - planificador: melhorado o arredondamento da duração das paragens nas notas

# correcções de problemas:

  - corrigida a criação de novos tipos de garrafas (os nomes não podiam ser iguais ao início de nomes já existentes)

  - corrigida a ordem das alhetas no widget do filto

  - ignorar locais de mergulho sem coordenadas na busca na vizinhança

  - corrigido o problema com a falha de comunicação com os computadores de mergulho Bluetooth na AppImage \[\#2370\]

  - permitida a cópia\&colagem de várias garrafas \[\#2386\]

  - não mostrar valores de consumo à superfície  para garrafas sem dados de consumo \[\#2376\]

  - registar alterações ao clicar "feito" no ecrã de edição de locais de mergulho

  - actualizar a alheta das estatísticas ao fazer "undo" ou "redo"

  - actualizar os detalhes do mergulho depois de alterar o planeamento \[\#2280\]

  - exportar os locais seleccionados ao exportar os locais de mergulho na alheta dos locais \[\#2275\]

# libdivecomputer:

  - adicionado suporte para o Oceanic Geo 4.0

  - limpar o modo de lidar com a pressão das garrafas no Shearwater

  - pequenas correcções

{% include desktop-release-bottom.MD %}
