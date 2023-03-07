---
layout: page
permalink: /pat/
title: Sopravvivere la paternita'
---


<div id="archives">

  <div class="archive-group">

    <div id="#{{ pat | slugize }}"></div>
    <p></p>
    
    <h3 class="category-head">{{ pat }}</h3>
    <a name="{{ pat | slugize }}"></a>
    
    {% for post in site.categories.pat %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></h4>
    </article>
    {% endfor %}
    
  </div>

</div>
