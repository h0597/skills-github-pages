---
title: Welcome to my blog
---

Welcome to my blog all about the 2024 F1 season. For each race weekend there will be a post about the race.


{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}
[Read more...]({{ post.url }})
{% endfor %}
