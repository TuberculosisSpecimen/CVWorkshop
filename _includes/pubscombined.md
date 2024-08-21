<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>


{% for link in site.data.pubscombined.main %}


{% if link.type contains "essay" %}
essay
title: {{ link.title }}
author: {{ link.author }}
{% endif %}

{% if link.type contains "conference" %}
presentation
title: {{ link.title }}
author: {{ link.author }}
{% endif %}

{% endfor %}



