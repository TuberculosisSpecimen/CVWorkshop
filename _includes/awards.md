<h2 id="publications" style="margin: 2px 0px -15px;">Fellowships and Grants</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.awards.main %}

<li>
<ul style="margin:0 0 20px;">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">{{ link.awardtitle }}{% if link.amount %}| {{ link.amount }}{% endif %}</div>
</ul>
<div class="links">
{% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}</div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>

