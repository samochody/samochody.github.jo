---
layout: page
title : Samochody
---
<ul>
{% for item in site.data.samochody %}
<li style= "{% if item.samochod %}color: red {% endif %}">
{{ item.name }} (<em>{{item.lista}}</em>)
</li>
{% endfor %}
</ul>
