<h2 id="publications" style="margin: 2px 0px -15px;">Fellowships and Grants</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">{{ link.awardtitle }}{% if link.amount %}| {{ link.amount }}{% endif %}</div>
</div>
</li>

<br>

{% endfor %}

</ol>
</div>

