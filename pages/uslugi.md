---
# GLOBAL 
layout: services
title: Projektujemy i programujemy rozwiązania dla Twojego biznesu
seo_title:  SEO Usługi
seo_description: |-
  MEAT Usługi
menu_title: Usługi
visibility_in_menu: true
position_in_menu: 1 
cta_in_menu: false
cta_text_in_menu: 
show_contact_in_footer: true

# INDEX layout
header_intro: |-
  Wspólnie opracujemy rozwiązanie odpowiadające potrzebom Twojego biznesu. Dzięki dobrze dopasowanym narzędziom wykorzystasz wszystkie możliwości do rozwoju i przeniesiesz swoją firmę lub startup na wyższy poziom.
services:
  -
    service: _services/aplikacje-internetowe.md
    casestudy: _casestudies/system-wms-expano.md
  -
    service: _services/sklepy-internetowe.md
    casestudy: _casestudies/sklep-internetowy-manwoman-co.md
  -
    service: _services/ux-ui.md
    casestudy: _casestudies/strona-internetowa-arcom-net-pl.md
  -
    service: _services/branding.md
    casestudy: _casestudies/sklep-internetowy-agdmaster-com.md

---
CONTENT Usługi
      {% for service in site.services %}
  <ul>
    <li><a href="{{service.url}}">{{service.title}}</a></li>    
  </ul>                         
  {% endfor %}
  
      {% for casestudy in site.casestudies %}
  <ul>
    <li><a href="{{casestudy.url}}">{{casestudy.title}}</a></li>        
  </ul>                     
  {% endfor %}