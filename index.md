---
title: Test!
---

# test

- foo
- [Tell me more.](about)
- [bar](more)

# Bar

{% for post in site.posts %}
- [{{ post.date }} {{post.title}}]({{ post.url }})
{% endfor %}

