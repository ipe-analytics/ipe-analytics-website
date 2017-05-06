---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: main-header_v2.jpg

overview:
  title: Sobre o Grupo de Trabalho (GT)
  text: O IPÊ Analytics propõe um sistema para analisar os dados coletados pelos monitoramentos existentes na rede IPÊ usando técnicas de Análise de Grandes Volumes de Dados (Big Data Analytics). O principal objetivo é fornecer informações mais valiosas para amparar a gerência de operações, a engenharia de tráfego e o planejamento da rede.

widget1:
  title: "Projeto"
  url: 'https://ipe-analytics.github.io/project/'
  image: '/images/logo-projeto-site_v2.png'
  text: 'Apresentação do contexto, motivação e objetivos.'
widget2:
  title: "Equipe"
  url: 'https://ipe-analytics.github.io/people/'
  image: '/images/logo-equipe_recursos-site2.png'
  text: 'Organizações e pessoas envolvidas no projeto.'
widget3:
  title: "Pesquisa"
  url: 'https://ipe-analytics.github.io/publications/'
  image: '/images/logo-pesquisa-site.png'
  text: 'Pesquisa Científica desenvolvida por trás do projeto.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/networks-at-scale-ufrgs
  text: Me mantenha informado sobre as novidades ›
  style: alert
permalink: /index.html
---
