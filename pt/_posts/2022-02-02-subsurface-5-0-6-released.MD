---
layout: post
title:  "Lançado o Subsurface 5.0.6"
lang:   "pt"
categories: release
version: 5.0.6
previousVersion: 5.0.5
ref: subsurface-5.0.6
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão adiciona algumas pequenas mudanças em relação à {{ page.previousVersion }}.

Mudanças no Subsurface {{ page.version }}:

# novas funcionalidade:

- estatísticas: implementa a ordenação em gráficos de barras com variáveis categóricas

# correcção de problemas:

- lista de mergulhos: Não tentar calcular o SAC para mergulhos CCR

- perfil: correcção da edição da hora / duração (o perfil do mergulho editado não era exibido)

- perfil: reescrita parte da implementação, que resultou numa melhoria do desempenho

# suporte a computadores de mergulho:

- computadores de mergulho Uwatec/Scubapro: restaurado o standard de gravidade original

- Garmin: correcção da leitura do evento de mudança de gás

{% include desktop-release-bottom.MD %}
