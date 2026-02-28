---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

{% for post in site.posts %}
<div class="list__item">
  <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
    <h2 class="archive__item-title" itemprop="headline">{{ post.title }}</h2>
    <p class="page__date"><strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Accepted:</strong> <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></p>
    <div class="archive__item-excerpt" style="font-size: 1em;" itemprop="description">{{ post.content }}</div>
  </article>
</div>
{% endfor %}
