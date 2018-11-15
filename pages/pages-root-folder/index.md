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
  title: Overview
  text: The Work Group (GT) IPÊ Analytics proposes a system which examines collected data of current monitoring tools in the IPÊ network applying Big Data Analytics techniques. The primary goal is to provide valuable information to assist operational management, traffic engineering, and network planning.

widget1:
  title: "Project"
  url: 'http://www.inf.ufrgs.br/ipeanalytics/project/'
  image: '/images/logo-projeto-site_v2.png'
  text: 'Introduction, motivation and primary goals.'
widget2:
  title: "Team"
  url: 'http://www.inf.ufrgs.br/ipeanalytics/people/'
  image: '/images/logo-equipe_recursos-site2.png'
  text: 'Organizations and people associated with the project.'
widget3:
  title: "Research"
  url: 'http://www.inf.ufrgs.br/ipeanalytics/publications/'
  image: '/images/logo-pesquisa-site.png'
  text: 'Scientific Research developed adjacent to the project.'
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
  url: https://tinyletter.com/ipe-analytics
  text: Keep me updated with news ›
  style: alert
permalink: /index.html
---
