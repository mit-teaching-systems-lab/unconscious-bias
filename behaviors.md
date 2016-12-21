---
layout: post
title: All behaviors
---


<ul>
{% for behavior in site.data.behaviors %}
  <li>{{ behavior }}</li>
{% endfor %}
</ul>

{% for behavior_set in site.data.behavior_sets %}
  {% assign context = behavior_set[0] %}
  {% assign behaviors = behavior_set[1] %}
  <div>
    <h6>{{ context }}</h6>
    <ul>
    {% for behavior in behaviors %}
      <li>{{ behavior }}</li>
    {% endfor %}
    </ul>
    </div>
  </div>
{% endfor %}
