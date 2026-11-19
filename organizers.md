---
---

# Organizers

{% include profile_list.html people=site.data.organizers %}

{% if site.edition.open_organizer_slots > 0 %}
<div class="container" style="margin-bottom: 30px;">
{% include profile_grid.html people=empty open_slots=site.edition.open_organizer_slots %}
</div>
{% endif %}

# Program Committee

{% if site.data.program_committee.size > 0 %}
{% assign pc = site.data.program_committee | sort: 'name' %}
<div class="pc-grid">
  {% for m in pc %}<div class="pc-member"><div class="pc-name">{{ m.name }}</div><div class="pc-affiliation">{{ m.affiliation }}</div></div>{% endfor %}
</div>
{% else %}
The program committee will be announced.
{% endif %}
