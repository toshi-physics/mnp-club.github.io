---
layout: events
title: Events
excerpt: ""
search_omit: true
image:
  feature: About_img.jpg
---


{% for post in site.categories.events %} 


 <div class="row rect" style="background: {% if post.status == 'Finished' %} #516878 {% elsif post.status == 'Nearest'%} #7cbf5b {% elsif post.status == 'Future'  %}  #ffffff {% endif %}">
 <a href="{{ site.url }}{{ post.url }}">
  <div class="col-sm-1"></div>
  <div class="col-sm-2">
   <div class="date">
   	<p>{{ post.day }}<span>{{ post.month }}</span></p>
   </div>
  </div>
  <div class="col-sm-9">
   <p class="event"> {{post.pseudo_title}}  </p>
  </div>
  </a>
 </div>
 
 


{% endfor %}

