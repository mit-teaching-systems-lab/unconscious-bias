---
layout: small
title: Teacher behaviors
---
[Edit this page]({{site.github.repository_url}}/edit/master/_data/behavior_sets.yaml)

# How bias can surface in teaching

### Teachers' uniquely important role
Teachers have a unique ability influence our society in the classroom communities that they create and the individual relationships they build with students.  This also means they are uniquely positioned to model equity and awareness of potential bias.

Here are some ways that bias might surface in teaching.  These are a starting point for creating interactive case studies that can be used as part of teacher preparation programs.

We'd love your feedback.  And if you have stories of your own experience as a student or teacher, please get in touch so that we can include your experience here.

{% for behavior_set in site.data.behavior_sets %}
### {{ behavior_set.name }}

<ul>
  {% for behavior in behavior_set.behaviors %}
  <li>{{ behavior }}</li>
  {% endfor %}
</ul>
{% endfor %}
