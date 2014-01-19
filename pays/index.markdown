---
layout: pages
title: "Présentations pays"
---

### La révolution numérique à l'étranger

Les étudiants sont invités, à chaque séance, à présenter
la manière dont un pays anticipe, gère ou subit la révolution
numérique.

La liste envisagée pour cette comparaison internationale comporte
notamment les pays suivants :

 - Estonie
 - États-Unis
 - Chine
 - Royaume-Uni
 - Tunisie
 - Corée du Sud 
 - Canada
 - Danemark
 - Japon
 - Australie
 - Russie

Si vous souhaitez contribuer à ce travail, n'hésitez pas à
[contribuer à ce site][contrib].

### Pays déjà examinés

<ul class="past posts">
  {% for post in site.posts %}
   {% if post.pays %}
 <li style="list-style-type: none;">
   <div class="droite tags">
     {{ post.categories | join: ', '}}
   </div>
   <time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">{{ post.date | date:"%d %b" }} </time>
   ›
   <span itemprop="name"><a href="{{ post.url }}" itemprop="url">{{ post.title }}</a></span>
 </li>
   {% endif %}
  {% endfor %}
</ul>

[contrib]: {% post_url 2013-12-29-premier-billet %}
