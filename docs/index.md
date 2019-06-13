---
title: My Test
---

# pages:

{% for page in site.pages %}
  {% if page.type == 'doc' %}
* [{{page.title}}]({{page.url | relative_url}})
  {% endif %}
{% endfor %}
