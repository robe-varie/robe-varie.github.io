---
layout: page
title: biscotti
permalink: /biscotti/
---

### biscotti

forse non faremo una tabella come per le tortillas, forse si, vedremo..

apprezziamo molto i gran cereale originali ma stiamo provando anche le varie "copie"

solitamente uso latte di riso per inzuppare i biscotti


<div id="archives">

  <div class="archive-group">

    <div id="#{{ Biscotti | slugize }}"></div>
    <p></p>
    
    <h3 class="category-head">{{ Biscotti }}</h3>
    <a name="{{ Biscotti | slugize }}"></a>
    
    {% for post in site.categories.Biscotti %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></h4>
    </article>
    {% endfor %}
    
  </div>

</div>
