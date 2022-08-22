---
title: "News"
layout: textlay
excerpt: "Gear Up 12499 - News"
sitemap: false
permalink: /news.html
---

# News

{% for article in site.data.news %}
<p><b>{{ article.date }}</b></p>
<p><em>{{ article.headline | markdownify}}</em></p>
<br>
{% endfor %}