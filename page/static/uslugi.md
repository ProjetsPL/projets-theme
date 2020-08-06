---
# GLOBAL 
layout: page
title: Usługi
seo_title:  SEO Usługi
seo_description: |-
  MEAT Usługi
visibility_in_menu: true
position_in_menu: 1 
cta_in_menu: false
cta_text_in_menu: 
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