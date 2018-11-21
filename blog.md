---
layout: default
title: My Blog
permalink: /blog/
type: Blog
---

<h1 class="page-title">{{ page.title }}</h1>
<div class ="page-content">
<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> » <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
	  <div class="post-meta">{{ post.excerpt }}</div>
    </li>
  {% endfor %}
</ul>
</div>