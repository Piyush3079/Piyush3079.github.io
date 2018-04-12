---
layout: page
permalink: /categories/
title: Categories
---


<div id="archives">
{% for category in site.categories %}
  <div class="archive-group col-sm-6">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <p class="category-head">{{ category_name }}</p>
    <a name="{{ category_name | slugize }}"></a>
    <ul>
    {% for post in site.categories[category_name] %}
    <article class="archive-item">
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></li>
    </article>
    {% if site.disqus.shortname %}
      {% include disqus_comments.html %}
    {% endif %}
    {% endfor %}
    </ul>
  </div>
{% endfor %}
</div>