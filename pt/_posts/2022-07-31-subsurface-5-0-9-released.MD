---
layout: post
title:  "Lançado o Subsurface 5.0.9"
lang:   "pt"
categories: release
version: 5.0.9
previousVersion: 5.0.8
ref: subsurface-5.0.9
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão surge pouco tempo após o lançamento da versão {{ page.previousVersion }} e corrige um problema irritante que se encontra nos ficheiros binários dessa versão.

Mudanças no Subsurface {{ page.version }}:

# Novas funcionalidades:

- desktop: permite importar mais do que um ficheiro multimédia a partir da web

- desktop: melhoria do interface de utilizador para verificação das credenciais do armazenamento remoto

- filtro: normalizados os pontos de códigos de unicode para caracteres base (para procurar ℓ, etc.)

# suporte para computadores de mergulho

- adicionado suporte para os computadores Seac Screen e Action

- adicionado suporte para o computador Cressi Michelangelo

- adicionado suporte para a nova versão do computador Aqualung i200C

- adicionado suporte para os computadores Shearwater Petrel 3 e Perdix 2

- adicionado suporte para o computador Ratio iX3M 2

- adicionado suporte para o computador Sherwood Amphos Air 2.0

# correcção de problemas:

- núcleo: ao modificar garrafas em vários mergulhos, igualar o número de garrafas antes de comparar o seu tipo

- núcleo: juntar todas as propriedades de um mergulho, incluindo a corrente, altura da vaga, etc.

- núcleo: impede falha ao juntar mergulhos sem garrafas (como pode suceder ao importar mergulhos de divelogs.de)

- núcleo: resolução do bug presente no computador de mergulho TecDiving que reporta uma temperatura de água falsa de 0º C na primeira amostra

- núcleo: análise correcta do campo DC_FIELD_SALINITY; corrige o tipo de água (salinidade) indicado por alguns computadores de mergulho, incluindo o Mares Smart

- desfazer: limpa a lista de acções a desfazer quando o ficheiro actual é encerrado

- build-system: várias actualizações para novas distribuições Linux

# suporte para computadores de mergulho

- Garmin: lida correctamente com os nomes de ficheiros em formato curto

- Garmin: análise correcta do modo de mergulho

{% include desktop-release-bottom.MD %}
