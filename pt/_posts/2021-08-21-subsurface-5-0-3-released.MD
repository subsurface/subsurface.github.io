---
layout: post
title:  "Lançado o Subsurface 5.0.3"
lang:   "pt"
categories: release
version: 5.0.3
previousVersion: 5.0.2
ref: subsurface-5.0.3
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão implementa algumas pequenas melhorias e corrige alguns problenas com a versão {{ page.previousVersion }}. Um dos efeitos desta nova versão é que a antiga característica das «alcunhas» dos computadores de mergulho (que pensamos não ser amplamente usada) viu alterado o seu comportamento. A razão pela qual pensamos que esta funcionalidade não é mais usada prende-se com o facto de algumas mudanças recentes no código causaram problemas subtis nesta área do programa, embora os utilizadores não se tenham apercebido disso. O Subsurface confundia-se algumas vezes ao identificar os computadores de mergulho e atribuía-lhe as alcunhas erradas. E pior: algumas vezes poderia descarregar novamente os mergulhos já descarregados. A resolução para esse problema é algo drástica na medida em que apenas permite dar alcunhas aos computadores de mergulho que possuem um campo de texto «Informação extra» no nº de série. Algumas das mudanças nesta versão adicionam essa informação para um grande nº de computadores de mergulho, mas há alguns que vão deixar de aceitar alcunhas. Se este problema o afectar, por favor indique-nos que computadores de mergulho usa e de que forma usa as alcunhas.


Mudanças no Subsurface {{ page.version }}:


# novas funcionalidades:

- substituição da gestão dos computadores de mergulho com uma nova implementação; isto resolve os raros casos em que o Subsurface descarrega desnecessariamente mergulhos já descarregados, mas significa também que alguns computadores de mergulho mais antigos deixam de aceitar «alcunhas»

- addiciona as coordenadas GPS descarregadas de uma computador de mergulho a um local de mergulho existente

- permissão para editar o perfil de mergulhos em mergulhos importados via CSV

- addionada detecção do modo BLE para o computador Aladin A2

- suporte para exportar as garrafas não usadas para divelogs.de

- melhoria na gestão dos valores de CNS ao combinar vários computadores de mergulho

- adicionado suporte para o computador Cressi Neon

- adicionado suporte para o computador Sherwood Amphos 2.0

- adicionado suporte para mudanças de gás no computador EON Steel com o firmware 2.5

- adicionado suporte para o firmware mais recente para o computador Mares Genius

- adicionado suporte para números de série textuais para vários computadores de mergulho

# correcção de problemas:

- correcção dos cálculos de OTU e CNS para os «bailout» pleaneados

- melhoria na gestão dos valores de CNS ao combinar vários computadores de mergulho

- evitar falhas potenciais ao mudar de divelog

- resolução da falha no cursor ao usar os atalhos «esquerda/direita» para alternar entre computadores de mergulho

- evitar falhas potenciais ao importar mergulhos no formato DL7

- melhorias na escala dos ícones de evento ao imprimir

- evitar falha potencial com o computador Garmin Descent Mk2

- correcção do update de firmware dos computadores HW Sport e Mares Genius


{% include desktop-release-bottom.MD %}
