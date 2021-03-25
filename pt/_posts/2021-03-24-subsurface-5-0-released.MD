---
layout: post
title:  "Subsurface 5.0 released"
lang:   "pt"
categories: release
version: 5.0
previousVersion: 4.9.10
ref: subsurface-5.0.0
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão  {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão resolve apresenta uma reformulação completa das funções estatísticas com muitas funcionalidade novas e visualizações poderosas. Permite a análise de várias variáveis em função umas das outras e contém as visualizações gráficas mais comuns (barras, histogramas, dispersão, tartes, etc.).


Esta versão corrige ainda alguns problemas encontrados na {{ page.previousVersion }}. Algumas das mudanças no Subsurface {{ page.version }}:


# novas funcionalidades:

- reescrita completa do código das funções estatísticas, com uma importante expansão das suas capacidades

- adicionada opção nas preferências para desactivar a lista de garrafas padrão

- planeamento: permite mudanças automáticas nos "setpoints" a profundidades definidas no modo CCR

- adicionado suporte para o computador Mares Horizon

- adicionado suporte para o computador Sherwood Sage

- adicionado suporte para os modelos Ratio 2021

# correcção de problemas:

- tornar mais rápida a selecção de vários mergulhos

- ter em conta a queda na pO2 nos PSCR aquando do cálculo do CNS e OTU

- correcção dos cálculos OTU e CNS em mergulhos CCR a baixas profundidades

- undo: gravar para git após edição do lastro

- undo: reinicializar o modo de mergulho ao refazer a adição de "setpoints"

{% include desktop-release-bottom.MD %}
