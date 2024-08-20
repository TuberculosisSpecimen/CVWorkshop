<h2 id="publications" style="margin: 2px 0px -15px;">Fellowships and Grants</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.awards.main %}

<li>
      <div class="title">{{ link.awardtitle }}{% if link.amount %}| {{ link.amount }}{% endif %}</div>
<div class="links">
{% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}</div>
</li>

<br>

{% endfor %}

</ol>
</div>

