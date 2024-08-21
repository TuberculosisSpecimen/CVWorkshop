<h2 id="publications" style="margin: 2px 0px -15px;">Education</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.EducationWork.main %}

{% if link.degree %}
<div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><b>{{ link.degree }}</b></div>
      <div class="periodical"><em>{% if link.thesis %}Thesis: {{ link.thesis }}{% endif %}{{ link.publication }}, {{ link.year }}</em></div>
      <div class="author">{{ link.school }}{% if link.department %} | {{ link.department }}{% endif %}</div></div>
     {% if link.advisors %} <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 30px;"><em>Advisors: {{ link.advisors }}</div><br>{% endif %} <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 30px;">{{ link.years }}</div>
      <div class="links">
      {% if link.notes %}  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 30px;">
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong></div>
      {% endif %}</div>
{% endif %}
<br>
{% endfor %}

<h2 id="publications" style="margin: 2px 0px -15px;">Experience</h2>

{% for link in site.data.EducationWork.main %}
{% if link.title %}
<div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><b>{{ link.title }}</b></div>
      <div class="periodical"><em>{{ link.workplace }}{% if link.department %} | {{ link.department }}{% endif %}{{ link.publication }}, {{ link.year }}</em>
      </div>
      <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 30px;">{% if link.duties %}<em>Duties: <i>{{ link.duties }}</i><br>{% endif %}{{ link.years }}</em>
      <div class="links">
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}</div></div>
    </div>
{% endif %}
  </div>
</div>

<br>

{% endfor %}

</ol>
</div>

