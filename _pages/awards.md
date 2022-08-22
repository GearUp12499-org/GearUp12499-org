---
title: "News"
layout: textlay
excerpt: "Gear Up 12499 - Awards"
sitemap: false
permalink: /awards.html
---

# News

{% for article in site.data.awards %}
    <p>{{ article.date }}</p>
    <p><em>{{ article.headline | markdownify}}</em></p>
{% endfor %}
