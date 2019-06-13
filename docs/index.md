---
title: My Test
---

# pages:

{% for page in site.pages %}
  {% if page.type == 'doc' %}
* [{{page.title}}]({{page.url}})
  {% endif %}
{% endfor %}
