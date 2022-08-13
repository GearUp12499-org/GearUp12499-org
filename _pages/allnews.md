---
title: "News"
layout: textlay
excerpt: "Gear Up 12499 - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
    <p>{{ article.date }}</p>
    <p><em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
