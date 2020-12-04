---
layout: post
title:  "Subsurface 4.9.8 released"
lang:   "pt"
categories: release
version: 4.9.8
previousVersion: 4.9.7
ref: subsurface-4.9.8
---
A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão  {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão resolve vários problemas presentes na {{ page.previousVersion }} e adiciona algumas pequenas melhorias e suporte para muitos novos computadores de mergulho. A alteração mais substancial é a nova forma -- mais flexível -- de filtrar os mergulhos da lista. Algumas das mudanças no Subsurface {{ page.version }}:

# novas funções:

 - filtro: sistema de filtros mais flexível, baseado em condições

 - adicionado suporte para o Garmin Descent Mk2/Mk2i em Linux, macOS, e Windows 64bit

 - adicionado suporte para o Scubapro Aladin A2

 - desktop: permite adicionar mergulhos a viagens arbitrárias

 - equipamento: usa pO2 definida nas Preferências para mostrar a MOD

 - núcleo: possibilidade de desfazer mudanças (undo) na gestão de computadores de mergulho

 - Windows: adicionados ficheiros binários separados por arquitectura (32 e 64bit) - o ficheiro para 32bit NÃO suporta o Garmin Descent Mk2/Mk2i

# correcção de problemas:

 - desktop: melhora a aparência no modo escuro (dark mode)

 - desktop: resolvido o problema ao arrastar e largar no widget das etiquetas [#3030]

 - desktop: respeitar as teclas page-up, page-down, home e end para mudanças na selecção [#2957]

 - núcleo: melhoria na junção das pressões das garrafas [#2884]

 - Windows: adicionado o tema "Vista" em falta

 - macOS: corrigido o problema com computadores de mergulho HID como o Suunto Eon Core/Steel [#2999]

{% include desktop-release-bottom.MD %}
