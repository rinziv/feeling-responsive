---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Percorsi di supporto"
  url: '/servizi/'
  image: widget-1-302x182.jpg
  text: 'Colloqui individuali per adolescenti e adulti, supporto alla genitorialita e percorsi dedicati alla coppia. Ogni percorso e costruito in base ai bisogni della persona.'
widget2:
  title: "Aree di intervento"
  url: '/aree-intervento/'
  text: 'Ansia, stress, difficolta relazionali, sostegno nelle fasi di cambiamento, benessere emotivo in adolescenza e percorsi di crescita personale.'
  image: widget-github-303x182.jpg
widget3:
  title: "Domande frequenti"
  url: '/faq/'
  image: widget-1-302x182.jpg
  text: 'Durata dei colloqui, costi, modalita di prenotazione e informazioni pratiche per iniziare con serenita un primo incontro conoscitivo.'
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
  url: /contact/
  text: Prenota un primo colloquio conoscitivo ›
  style:
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
