---
layout: events
title: Events
excerpt: ""
search_omit: true
image:
  feature: About_img.jpg
---


{% for post in site.categories.events %} 


 <div class="row rect" style="background: {% if post.status == 'Finished' %} #fc6f4c {% elsif post.status == 'Nearest'%} #8cff41 {% elsif post.ststus= 'Future'  %}  #e8faff {% endif %}">
 <a href="{{ site.url }}{{ post.url }}">
  <div class="col-sm-1"></div>
  <div class="col-sm-2">
   <div class="date">
   	<p>{{ post.day }}<span>{{ post.month }}</span></p>
   </div>
  </div>
  <div class="col-sm-9">
   <p class="event"> {{post.title}}  </p>
  </div>
  </a>
 </div>
 
 


{% endfor %}

