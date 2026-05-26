<h2 id="service" style="margin: 2px 0px 8px;">Academic Service</h2>

<p style="margin-bottom: 4px;"><strong>Reviewer for:</strong></p>
<ul style="margin-top: 0;">
{% for entry in site.data.service.reviewer %}
  <li><em>{{ entry.venue }}</em>, {{ entry.year }}</li>
{% endfor %}
</ul>
