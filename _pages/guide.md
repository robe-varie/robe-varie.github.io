---
layout: page
title: guide
permalink: /guide/
---

### guide


<div id="archives">

  <div class="archive-group">

    <div id="#{{ Guide | slugize }}"></div>
    <p></p>
    
    <h3 class="category-head">{{ Guide }}</h3>
    <a name="{{ Guide | slugize }}"></a>
    
    {% for post in site.categories.Guide %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></h4>
    </article>
    {% endfor %}
    
  </div>

</div>
