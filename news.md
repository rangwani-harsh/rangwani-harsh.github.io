---
title: "Home"
layout: grid_lay
excerpt: "Harsh Rangwani"
sitemap: false
permalink: /news
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
