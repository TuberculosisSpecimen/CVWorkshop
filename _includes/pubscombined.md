<h2 id="publications" style="margin: 2px 0px -15px;">Publications</h2>


{% for link in site.data.pubscombined.main %}


{% if link.type.essay %}
title: {{ link.title }}
author: {{ link.author }}
{% endif %}

Presentations
{% if link.type.essay %}
title: {{ link.title }}
author: {{ link.author }}
{% endif %}

{% endfor %}



