---
title: Menu
show_profile: true
# permalink: "/"
---

{% for item in site.data.nav %}
- [{{ item.title }}]({{ "/" }}{{ item.href }})
{% endfor %}