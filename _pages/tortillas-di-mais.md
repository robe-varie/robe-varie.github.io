---
layout: page
title: Tortillas di mais
permalink: /tortillas-di-mais/
---

### la continua ricerca della tortilla di mais croccante perfetta

continua la ricerca della tortilla di mais perfetta, quella croccante, i nachos

requisiti: no additivi tipo sapore o gusti buffi, no salsine (sono optional), solo noiose tortillas "plain"

### recap sintetico

| Marca             | Modello           | Voto Tot (0/5) | Sapore            | Sale              | Consistenza       | Forma             |  gr. | Negozio           |
| ----------------- | ----------------- | -------------- | ----------------- | ----------------- | ----------------- | ----------------- | ----------------- | ----------------- |
| [Don Fernando](../_posts/2023-02-28-TortillasDonFernando.md) | Tortilla Chips (SALT) | 3.5 | 4 - Giusto | 3 - Troppo salate | 4 - Croccante | Tri. equilatero | 200 | Despar (nord) |
| [Pai](../_posts/2023-02-25-TortillasPai.md) | Tortillas | 1 | 1 - Triste | 1 - Sciapo | 1 - Mollacciosa | Tri. Isoscele | 230 | ? |
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |





<div id="archives">

  <div class="archive-group">

    <div id="#{{ Tortillas | slugize }}"></div>
    <p></p>
    
    <h3 class="category-head">{{ Tortillas }}</h3>
    <a name="{{ Tortillas | slugize }}"></a>
    
    {% for post in site.categories.Tortillas %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{post.title}}{% else %}{{post.excerpt |strip_html}}{%endif%}</a></h4>
    </article>
    {% endfor %}
    
  </div>

</div>
