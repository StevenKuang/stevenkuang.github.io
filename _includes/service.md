<h2 id="services">Services</h2>

<h4 style="margin:0 10px 0;">Conference Reviewers</h4>

<ul style="margin:0 0 5px;">
{% for entry in site.data.service.conference_reviewers %}
  <li>{{ entry.venue }}{% if entry.year %}, {{ entry.year }}{% endif %}</li>
{% endfor %}
</ul>

<h4 style="margin:0 10px 0;">Journal Reviewers</h4>

<ul style="margin:0 0 20px;">
{% for entry in site.data.service.journal_reviewers %}
  <li>{{ entry.venue }}{% if entry.year %}, {{ entry.year }}{% endif %}</li>
{% endfor %}
</ul>
