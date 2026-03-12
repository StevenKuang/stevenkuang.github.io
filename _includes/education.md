<h2 id="education" style="margin: 2px 0px -15px;">Education</h2>

<div class="publications">
<ol class="bibliography">

{% for education in site.data.education %}

<li>
<div class="pub-row">
  <div class="col-sm-3" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if education.logo %}
    <img src="{{ education.logo }}" class="teasereducation img-fluid z-depth-1" style="width: 150px; height: auto; object-fit: contain;">
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><strong>{{ education.institution }}</strong></div>
      <div><strong>Degree:</strong> {{ education.degree }}</div>
      <div><strong>Duration:</strong> {{ education.duration }}</div>
      {% if education.supervisors %}
      <div><strong>Supervisors:</strong> {{ education.supervisors }}</div>
      {% endif %}
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
