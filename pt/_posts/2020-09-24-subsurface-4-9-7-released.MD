---
layout: post
title:  "Lançado o Subsurface 4.9.7"
lang:   "pt"
categories: release
version: 4.9.7
previousVersion: 4.9.6
ref: subsurface-4.9.7
---

A equipa de desenvolvimento do Subsurface tem o orgulho de anunciar a disponibilização da versão  {{ page.version }} do Subsurface, um programa de código livre para registo e planeamento de mergulhos para Windows, Mac e Linux.

Esta versão resolve vários problemas presentes na {{ page.previousVersion }} e adiciona algumas pequenas melhorias e suporte para muitos novos computadores de mergulho. Algumas das mudanças no Subsurface {{ page.version }}:

# novas características:

  - perfil: adicionada uma opção (acessível com um clique com o botão direito) para "editar uma troca de gás" [#2910]
  
  - importar: adiciondo parser para a base de dados SeacSync. Presentemente apenas o Seac Action usa o programa SeacSync

  - adicionado suporte para o Shearwater Peregrine (requer firmware V81 ou posterior)

  - adicionado suporte para o Aqualung i470TC

  - adicionado suporte para o Liquivision Kaon, Lynx, Xen, Xeo

  - adicionado suporte para o McLean Extreme

  - adicionado suporte para o Oceans S1

  - adicionado reconhecimento automático para mais computadores de mergulho com o protocolo BLE

# correcção de problemas:
  
  - bluetooth/rfcomm: resolvido o problema com o download através do protocolo BT clássico em Linux e Windows; a versão para macOS ainda apresenta problemas

  - equipamento: não escrever sobre um conjunto de lastro já existente ao alterar o tipo de lastro [#2938]

  - equipamento: efectuar buscas por substrings para tipos de equipamento

  - perfil: melhorada a resolução na impressão e exportação

  - núcleo: resolvida a renumeração de mergulhos importados [#2731]

  - núcleo: resolvida a junção de mergulhos com várias garrafas

  - núcleo: assegurar que o mergulho actual está sempre seleccionado [#2961]

  - núcleo: actualizar o estado do filtro ao carregar a lista de mergulhos [#2961]

  - media: ler o timestamp do mvhd atom de vídeos QuickTime/MP4

  - planeamento: incializar correctamente a salinidade

  - planeamento: manejar correctamente segmentos com comprimento zero ao replanear mergulhos

  - planeamento: cumprir a preferência "O2 narcotic" ao calcular MND

  - importação: correcção de um conjunto de problemas ao importar mergulho da Shearwater Cloud

  - correcção do parser da Shearwater de forma a suportar PNF nos computadores Petrel

{% include desktop-release-bottom.MD %}
