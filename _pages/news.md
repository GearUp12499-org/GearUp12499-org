---
title: "Gear Up - News"
layout: textlay
excerpt: "Gear Up - News"
sitemap: false
permalink: /news.html
---

# News

{% for article in site.data.news %}

<p><b>{{ article.date}}</b></p>
<p><em>{{ article.headline}}</em></p>

<br>
{% endfor %}