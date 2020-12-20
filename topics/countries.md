---
layout: template
---

# Relation Details

{% for item in site.data.countries %} 

{{ item.name }} was born in {{ item.year }} and he is the {{ item.relation }}.

{% endfor %}