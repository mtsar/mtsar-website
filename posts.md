---
layout: page
title: Posts
permalink: /posts/
---

<ul>
{% for post in site.posts %}
<li>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
  <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

Also, we have an [RSS feed](/posts.xml).
