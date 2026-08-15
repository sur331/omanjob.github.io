---
layout: page
title: "قسم الوظائف"
permalink: /jobs/
---

### أحدث إعلانات الوظائف
{% for post in site.categories.وظائف %}
* [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
