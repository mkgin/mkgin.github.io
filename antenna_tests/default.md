---
layout: "page"
category: antennae
collections:
  - antenna_test
---
some contents

{% for test in site.antenna_test %}
  <h2>{{ antenna_test.name }} - {{ antenna_test.position }}</h2>
  <p>{{ antenna_test.content | markdownify }}</p>
{% endfor %}
