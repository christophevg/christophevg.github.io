---
layout: site
---

# My CV

This page gives you an overview of my professional life...

{% for position in site.data.cv %}

## {{ position.description }} at {{ position.company }}
{{ position.start }} - {{ position.end }}

{% endfor %}
