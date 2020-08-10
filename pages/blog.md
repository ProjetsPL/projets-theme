---
# GLOBAL 
layout: blog
title: Blog
seo_title:  SEO Blog
seo_description: |-
  MEAT Blog
menu_title: Blog
cta_title:
show_contact_in_footer: true
---
CONTENT Blog

  {% for post in site.posts %}
  <ul>
    <li><a href="{{post.url}}">{{post.title}}</a></li>          
  </ul>        
  {% endfor %}