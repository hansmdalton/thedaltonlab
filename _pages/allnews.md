---
title: "News"
layout: textlay
excerpt: "Dalton Lab at the University of Kansas."
sitemap: false
permalink: /allnews.html
---



# News

{% for article in site.data.news %}
{{ article.date }}<br>{{ article.headline }}
{% endfor %}

