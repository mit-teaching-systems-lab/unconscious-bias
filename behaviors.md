---
layout: small
title: Teacher behaviors
---

<a href="{{site.github.repository_url}}/edit/master/_data/behavior_sets.yaml">Edit this page</a>

{% for behavior_set in site.data.behavior_sets %}
  <div>
    <h6>{{ behavior_set.name }}</h6>
    <ul>
    {% for behavior in behavior_set.behaviors %}
      <li>{{ behavior }}</li>
    {% endfor %}
    </ul>
  </div>
{% endfor %}
