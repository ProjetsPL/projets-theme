---
# GLOBAL 
layout: blog
title: Blog
seo_title:  SEO Blog
seo_description: |-
  MEAT Blog
visibility_in_menu: true
position_in_menu: 3
cta_in_menu: false
cta_text_in_menu:
show_contact_in_footer: true
---
CONTENT Blog

  {% for post in site.posts %}
  <ul>
    <li><a href="{{post.url}}">{{post.title}}</a></li>          
  </ul>        
  {% endfor %}