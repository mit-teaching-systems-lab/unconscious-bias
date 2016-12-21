---
layout: post
title: All behaviors
---

<ul>
{% for key in site.data.behavior_sets %}
  {% assign behavior = site.data.behavior_sets[key] %}
  {% for behavior in behavior_set %}
    <li>
      {{ behavior }}
    </li>
  {% endfor %}
{% endfor %}
</ul>
