---
# GLOBAL 
layout: casestudies
page_type: casestudies
title: Realizacje

#SEO
seo_title:  SEO Realizacje
seo_description: |-
  MEAT Realizacje

#MENU 
top_line:
  menu_title: Realizacje
  cta_title:

#SETTINGS
show_contact_in_footer: true

#CASE STUDIES layout 
header:
  title: <strong>Realizacje</strong> - chwalimi się naszą pracą
  intro: |-
    Poznaj najnowsze trendy i technologie, które wykorzystujemy, aby Twój biznes nieustannie się rozwijał. Sprawdź ekspercki punkt widzenia.
---
CONTENT Realizacje

  {% for post in site.casestudies %}
  <ul>
    <li><a href="{{post.url}}">{{post.title}}</a></li>          
  </ul>        
  {% endfor %}