---
title: "News"
layout: textlay
excerpt: "biomolecular-design-workshop"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br> {{ article.headline }}
{% endfor %}
