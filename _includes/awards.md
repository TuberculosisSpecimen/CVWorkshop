<h2 id="publications" style="margin: 2px 0px -15px;">Awards</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.awards.main %}



  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><b>{{ link.awardtitle }}</b>, {{ link.source }}{% if link.amount %} | {{ link.amount }}{% endif %}</div>. <div class="author">{% if link.italics %}<i>{% endif %}{%if link.quotes %}"{% endif %}{{ link.awardproject }}{% if link.italics %}</i>{% endif %}{%if link.quotes %}"{% endif %}</div>.<div class="periodical"><em>{{ link.publication }} {{ link.year }}</em>.
      </div>
    <div class="links">
      {% if link.notes %} 
      <strong> <i style="color:#e74d3c">{{ link.notes }}</i></strong>
      {% endif %}
    </div>
  </div>


<br>

{% endfor %}

</ol>
</div>

