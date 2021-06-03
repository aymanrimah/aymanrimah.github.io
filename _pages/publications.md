---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} 
 
{% include base_path %}
  
<!---
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
--->

<h2>Thesis Manuscript </h2>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'thesis' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}

 
<h2>Low regularity change of variables and composition</h2>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'composition' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %} 

<h2> Study of the Flow map of hyperbolic, transport and dispersive type PDEs and applications to the water waves system</h2>
 {% for post in site.publications reversed %} 
    {% if post.pubtype == 'flowregularity' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}
 
 
